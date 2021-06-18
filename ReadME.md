# Project Details

## Objective
The aim was to create a neural network that can demonstrate potential ability classify songs into various genre. Ten genres have been taken here

## Model
The core of the model is a 2d CNN that takes in the spectrogram as input and gives the one-hot-encoded class as output
Although the model has a lot of params, the dataset is quite small, my computer can handle it.

## Logic
The raw audio was converted to spectrogram using the librosa package. 
The neural network model does the classification. 

## File manifest
MusicFilterWeights.h5: The weights of the model
MusicGenreFilter: The folder containing the model
Music Classification.ipynb: My code
Data: Folder containing the processed data
