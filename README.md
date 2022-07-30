# Music-Genre-Classification
This is a DeepLearning Major Project on Music Genre Classification using GTZAN dataset.<br/>
# About the GTZAN dataset used:
[GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) dataset has features extracted (example features; fast-fourier transformation, short-time-fourier transformation, MFCCs, etc) from .wav/audio files as images on 10 different music genres with 100 audio samples(3 seconds each) per genre, making it a 10,000 X 60 (row X column) dataset generated/made by kaggle (in my knowledge).<br/>
# About the Classification Algorithm and Model:
I've used CNN algorithm with a [Sequential](https://keras.io/guides/sequential_model/) model to classify the music samples after:<br/>
i. Pre-processing the dataset by scaling features and label encoding,<br/>
ii. Data Visualization and<br/>
iii. Splitting the dataset for training and testing.<br/>
# About the Model Evaluation:
Accuracy and Loss were calculated as evaluation metrics.
