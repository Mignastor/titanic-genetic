# Titanic: Disaster Prediction

Based on Kaggle Competition data.

## Idea 

This notebook aims at trying tpot library to train a scikit-learn model to answer Kaggle Competion

## tpot

https://github.com/rhiever/tpot

## Process

The train data will be separated separated into two dataframe with 75% and 25% to have a labeled test set to feed tpot.

Then, when the algortihm will be chosen, it will be trained with the whole dataset before applying it to the kaggle test data and submitted for revision.