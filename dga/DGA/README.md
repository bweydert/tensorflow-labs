# anomaly-detection
Anamoly Detection use case

## Goal

The goal is to develop a classifier that can differentiate between fraudulent and real websites

## Notebooks:

1. dga.ipynb : Some Data Prep, also contained in the script dga-prep
2. dga-tfidf.ipynb : Does some feature extraction with tfidf and trains a support vector machine classifier

## Scripts

1. cleanup.sh : does some rough cleanup
2. dga-prep.py : Extracts contents of dga.ipynb into a script. 


## Results

I trained with the data, did some feature extraction and feature engineering, and got some results of our classifier. Some future steps might be to try better feature extraction (e.g. word2vec), and some better models than SVM.

