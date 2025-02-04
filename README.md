# Predicting Internet Addiction through Depression, Anxiety, and Stress Levels: A Classification Model

This repository contains the source codes and resources for the research paper *"Predicting Internet Addiction through Depression, Anxiety, and Stress Levels: A Classification Model."*

## Repository Structure

- **pre-process/**  
  Contains scripts for data preprocessing, including handling missing values and normalizing data.
  
- **data_exploration/**  
  Includes code for regression analysis and data visualization to understand initial trends and relationships in the dataset.
  
- **classification/**  
  Implements various classification models for predicting internet addiction based on Depression, Anxiety, and Stress Scale (DASS-21) scores.
  
- **proposed_model/**  
  Stores the final proposed neural network model in `.h5` format, along with Keras model files.
  
- **dataset/**  
  Contains the processed dataset (`.csv` format) after cleaning and handling missing values.

## Dataset

The dataset used in this study consists of 724 effective samples collected independently. It is preprocessed to remove null values and is used to train and evaluate the machine learning models.

A link to the dataset on Kaggle -  https://kaggle.com/datasets/b28543377eda18e79d300914263f2116870bd78c10afdbee74201f5df9efe2e1

## Web Application

A web application was developed to collect user feedback and facilitate continuous model improvement through consent-based data usage.

https://tinyurl.com/IATPREDICTION

## Abstract

With advances in technology use, a large proportion of the world population now has access to the internet. While the internet facilitates education, recreation, and communication, studies have begun to focus on Internet Addiction (IA). This study presents the development of a machine learning classification model to predict internet addiction, leveraging the Depression, Anxiety, and Stress Scale (DASS-21) scores as key predictors.

The research investigates various demographic, psychological, biological, and social factors associated with internet addiction, providing valuable insights into this growing behavioral issue. To the best of our knowledge, this is the first study to apply machine learning techniques to predict internet addiction based on the DASS-21 scores.

Despite the relatively small dataset, a neural network (NN) model was chosen for its ability to capture complex non-linear relationships in the data while utilizing regularization techniques to mitigate overfitting. The developed classification model is publicly available for future use by the research and developer community.

## Citation
If you use this repository or dataset in your research, please cite the paper accordingly.

## Authors
    - Aryaman Pathak
    - Shweta Sunil
    - Madhav Rao
    - Manoj Sharma

