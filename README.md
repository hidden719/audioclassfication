# audioclassfication
Toyproject from HumanCenteredAI class

# Summary
Time series is a set of observations where each of them was made at a specific time. One can be analyzed to understand the pattern of dependencies in the past of the series and exploit them to predict the future. The others can be analyzed to find the patterns that are similar with each other and be classified into certain categories. Audio classification is one of the trending time series related problems where you listen to and analyze audio recordings and find some patterns in audio data. Bu using the data, machines learn to develop the ability to differentiate between sounds to complete specific tasks. Music classification is one of those tasks where the machine needs to classify music based on factors such as genre, instruments played, tempos and more. This classification plays a key role in organizing audio libraries by genre, improving recommendation algorithms, and discovering trends and listener preferences. 
In this project, the goal is to go through the process of music classification using traditional Machine Learning based methods where analysis on the data should be done to extract features and then describe basic comprehension of each feature used in the ML pipeline. The features that are to be extracted as time domain features are Amplitude Envelope, RMS Energy, ZCR. Then from frequency domain Spectral Centroid, Bandwidth, MFCC and chroma feature will be extracted. Then, mean values and standard deviation values will be used to be trained. RandomForestClassifier, SVM and LogisticRegression will be used and get accuracy.

# References
H. Bahuleyan, “Music genre classification using machine learning techniques,” arXiv preprint arXiv:1804.01149, 2018.
B. McFee et al., “librosa: Audio and music signal analysis in Python,” in Proc. 14th Python Sci. Conf., 2015.

