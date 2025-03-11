# Fake-News-Classification
## Overview
This project focuses on classifying news articles as either "fake" or "real" based on their titles. The dataset used for this project is the WELFake dataset, which contains news articles labeled as either fake (label 1) or real (label 0). The goal is to build a machine learning model that can accurately predict whether a news article is fake or real based on its title.

### Dataset
The dataset used in this project is the WELFake_Dataset.csv, which contains the following columns:  
title: The title of the news article.  
text: The full text of the news article.  
label: The label indicating whether the news is fake (1) or real (0).  

## Usage
To run this project, follow these steps:  
### Install Required Libraries:
``` pip install kaggle pandas matplotlib seaborn nltk scikit-learn ```

### Download the Dataset:
The dataset can be downloaded from Kaggle using the following command:  
kaggle datasets download `saurabhshahane/fake-news-classification`

### Run the Jupyter Notebook:  
Open the provided Jupyter Notebook (fakeNewsClassificationBasedOnTitle.ipynb) and execute the cells to preprocess the data, train the model, and evaluate its performance.
