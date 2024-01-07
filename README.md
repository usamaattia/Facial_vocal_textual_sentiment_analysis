# Vision Sentiment Analysis Project

This project aims to perform sentiment analysis on visual and audio and textual data using various libraries and tools in Python.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Training files](#training)
- [Libraries Used](#libraries-used)


## Introduction

Sentiment analysis is the process of determining the emotional tone behind a series of words, used to gain an understanding of the attitudes, opinions, and emotions expressed within an online mention. This project extends sentiment analysis to include visual and audio data, providing a more comprehensive analysis.


## Features

- Perform sentiment analysis on textual data.
- Analyse facial expressions and gestures for sentiment analysis and produce one of the 6 basic emotions.
- Analyse audio data, such as voice tone, for sentiment analysis and produce one of the 6 basic emotions.

## Usage

1. open the file F_V.ipynb (jupyterLab file) with all .h5 files (pre-trained files) and and with the test.wav file then hit Run.
2. ensure you have all libraries installed and the training files with this file.
3. give access to the camera and start analysing.
4. Review the generated sentiment analysis results at the end.

## Training

# vision:
1. FER-2013 https://www.kaggle.com/datasets/msambare/fer2013 
# vocal:
1. SAVEE http://kahlan.eps.surrey.ac.uk/savee/
2. RAVSESS https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio  
3. Toronto https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess  


## Libraries Used

This project relies on the following libraries:

- TensorFlow
- NumPy
- Matplotlib
- OpenCV
- Librosa
- Pandas
- PyDub
- SpeechRecognition
- Wavio
- SciPy
- SoundDevice
- NLTK
Look how to install them in Linux or Mac below



## Dependencies and libraries for facial sentiment analysis work:
## Install the following libraries by using the following commands:
pip install tensorflow
pip install numpy
pip install matplotlib
pip install opencv-python

## Then install all libraries for voice and textual sentiment analysis:
pip install librosa
pip install numpy
pip install pandas
pip install pydub
pip install SpeechRecognition
pip install scipy
pip install wavio
pip install sounddevice
pip install nltk
import nltk
nltk.download('vader_lexicon')
