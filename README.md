# Binary Classification of Drowsy Drivers' EEG Waves

## Introduction
The project aims to use machine learning to identify EEG signals to warn drowsy drivers against losing concentration. The problem affects road safety, and the analyses carried out provide a crucial source of data for businesses.

## Description of Features
- **Attention** - Proprietary measure of mental focus from 0-100 
- **Meditation** - Proprietary measure of calmness from 0-100 
- **Delta** - 1-3 Hz of power spectrum 
- **Theta** - 4-7 Hz of power spectrum 
- **LowAlpha** - Lower 8-11 Hz of power spectrum 
- **HighAlpha** - Higher 8-11 Hz of power spectrum 
- **LowBeta** - Lower 12-29 Hz of power spectrum 
- **HighBeta** - Higher 12-29 Hz of power spectrum 
- **LowGamma** - Lower 30-100 Hz of power spectrum 
- **HighGamma** - Higher 30-100 Hz of power spectrum 
- **Classification** - (0-drowsy/1-awake)

## Requirements
This project uses the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

The following steps were carried out:

- Data review
- Missing data inspection
- Data preparation
- Trening training – 4 models employed: RidgeClassifier, KNeighborsClassifier, DecisionTreeClassifier and RandomForestClassifier
- All models have been saved and the RandomForestClassifier achieved the highest accuracy with a score of 74% 

## Dataset
[Sleepy Driver EEG Brainwave Data on Kaggle](https://www.kaggle.com/datasets/naddamuhhamed/sleepy-driver-eeg-brainwave-data/discussion/438246)
