# Mushroom-Classification

This is a machine learning classification project aimed to create a model that can predict whether mushrooms are edible or poisonous. The dataset was downloaded from UCI Machine Learning Repository. The dataset can be downloaded here: https://archive.ics.uci.edu/ml/datasets/mushroom

The data came with the actual values of each column being abbreviated, making it impossible to decode by itself. The dataset came with a txt file that describes what each abbreviation represent. Instead of copying and pasting those descriptions into a dictionary and mapping it to the dataframe, I emulated a real-life data extraction situation. I first imported the txt file, then used regular expressions to extract the relevant abbreviations and their actual values. I stored those information into dictionaries, and mapped them to the dataset to construct an interpretable dataset.

After the data was ready to be analyzed, I followed the traditional data science project cycle: EDA, data preprocessing, modeling, and hyperparameter tuning. 

