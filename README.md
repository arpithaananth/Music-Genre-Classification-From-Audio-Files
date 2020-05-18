# Music Genre Classification From Audio Files

### Objective:
- To analyse & extract the features from Audio Files
- To implement deep artificial neural network to classify the genres
- To implement traditional machine learning algorithms for classification 
- To implement convolutional neural network (CNN) Model

### Data Set
The GTZAN Genre Collection dataset is used to develop genre classification algorithm. The dataset consists of 1000 audio tracks each 30 seconds long. It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format. The size of the dataset is 1.2GB

### Data Set Source
The dataset has been procured from Marsyas (Music Analysis, Retrieval and Synthesis for Audio Signals) is an open source software framework for audio processing with specific emphasis on Music Information Retrieval applications. 

### A Brief Description about features in Audio Files:
#### - Spectrogram:
A visual representation of frequencies over time
![Spectrogram](C:\Users\Arpitha Ananth\Documents\Programming in Data Science\Practice Py\Knowledge Base\GTZAN Dataset\Spectrogram.jpg)

#### - Zero Crossing Rate:
Rate at which the signal changes signs (that is positive to negative)

#### - Spectral Centroid: 
This parameter indicates where the center of mass of the signal is located

#### - Spectral Rolloff:
The measure of shape of signal, frequency below which a specified percentage of the total spectral energy

#### - Mel- Frequency Cepstral Coefficients:
Small set of features which describe the shape of spectral signal

#### - Chroma Frequencies:
Describes entire spectral in 12 distinct semitones of musical octave

### Implementation of Artificial Neural Network:
A deep ANN was implemented, the test accuracy of 62% was achieved

### Implementation of Traditional Machine Learning Models for Multi-Class Classification:
ROC-AUC Scores of Classifiers: 
- Logistic Regression	0.8949
- KNN Classifier	0.8301
- Decision Tree	0.7060
- Random Forest	0.8441
- Ada Boost Classifier	0.5515
- Gradient Boost Classifier	0.8406
- XG Boost Classifier	0.8406





