# Music Genre Classification From Audio Files

### Objective:
- To analyse & extract the features from Audio Files
- To implement deep artificial neural network to classify the genres
- To implement traditional machine learning algorithms for classification 


### Data Set
The GTZAN Genre Collection dataset is used to develop genre classification algorithm. The dataset consists of 1000 audio tracks each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format. The size of the dataset is 1.2GB

### Data Set Source
The dataset has been procured from Marsyas (Music Analysis, Retrieval and Synthesis for Audio Signals) is an open source software framework for audio processing with specific emphasis on Music Information Retrieval applications. 

### A Brief Description about features in Audio Files:
#### - Spectrogram:
A visual representation of frequencies over time
![image](https://user-images.githubusercontent.com/47745543/82191807-b5fcee00-9910-11ea-89ef-57bdbec33743.png)
![image](https://user-images.githubusercontent.com/47745543/82429830-21c68e80-9aaa-11ea-8352-5b0588149122.png)

#### - Zero Crossing Rate:
Rate at which the signal changes signs (that is positive to negative)
![image](https://user-images.githubusercontent.com/47745543/82192387-8ef2ec00-9911-11ea-9f60-89ee628490bb.png)

#### - Spectral Centroid: 
This parameter indicates where the center of mass of the signal is located
![image](https://user-images.githubusercontent.com/47745543/82192450-a336e900-9911-11ea-86b1-da2d253c64a6.png)

#### - Spectral Rolloff:
The measure of shape of signal, frequency below which a specified percentage of the total spectral energy
![image](https://user-images.githubusercontent.com/47745543/82192488-b21d9b80-9911-11ea-8c9c-21a759917dd2.png)

#### - Mel- Frequency Cepstral Coefficients:
Small set of features which describe the shape of spectral signal
![image](https://user-images.githubusercontent.com/47745543/82192531-c1044e00-9911-11ea-9f2b-7f26e5d368db.png)

#### - Chroma Frequencies:
Describes entire spectral in 12 distinct semitones of musical octave
![image](https://user-images.githubusercontent.com/47745543/82192577-cd88a680-9911-11ea-9d5a-6059b2179a7d.png)

### Implementation of Artificial Neural Network:
A deep ANN was implemented, the test accuracy of 0.62 was achieved

### Implementation of Traditional Machine Learning Models for Multi-Class Classification:
ROC-AUC Scores of Classifiers: 
- Logistic Regression:	0.8949
- KNN Classifier:	0.8301
- Decision Tree:	0.7060
- Random Forest:	0.8441
- Ada Boost Classifier:	0.5515
- Gradient Boost Classifier:	0.8406
- XG Boost Classifier:	0.8406

![image](https://user-images.githubusercontent.com/47745543/82200716-fd897700-991c-11ea-9c6f-7b6b7ab0b5e1.png)


#### References:
- https://cse.iitk.ac.in/users/cs365/2015/_submissions/archit/report.pdf
- http://cs229.stanford.edu/proj2018/report/21.pdf
- https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8
- https://librosa.github.io/librosa/
