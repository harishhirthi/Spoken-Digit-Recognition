# Spoken-Digit-Recognition
Recognising digits from the spoken audio.

## Description:
Building the Deep Learning model to recognise the digits(0-9) from the human spoken audio and performing some data augmentation for improvising the recognition.

### Dataset Ref: https://github.com/Jakobovski/free-spoken-digit-dataset (recordings folder)

## Results:
| Data | Model | Test_F1_Score |
|---- |---- | ----- |
|Original - Raw Data|Model - 1| 0.1517 |
|Original - Spectogram|Model - 2 | 0.805|
|Augmented - Raw Data|Model - 3 | 0.1795|
|Augmented - Spectogram|Model - 4 | 0.8658|

## Contains one file:
Speech_detection.ipynb - Data prepartion, Data augmentation and Recognition.
