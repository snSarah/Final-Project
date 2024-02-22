# Breast Cancer Classification with Deep Learning

## Overview
This repository contains the code and resources for a deep learning-based classification model for breast cancer. 
The model is designed to analyze Breast Histopathology images and classify whether a given image is IDC-positive (cancer) or IDC-negative (non-cancer).

## Code
https://www.kaggle.com/code/sitinursarah/deep-learning-classification-on-breast-cancer

Above is the link to the Kaggle page where the whole code is executed.

## Features of the Kaggle Notebook

- **Data Collection:** Describes the dataset used, Importing the necessary modules and data, Visualises the dataset
- **Data Preprocessing:** Describes how the data was preprocessed, including resizing, normalization, shuffling and splitting of dataset
- **Model Architecture:** Outlines the chosen neural network structure, specifying layers, activations, and unique features
- **Hyperparameter Tuning:** Describes the process of optimizing model performance through fine-tuning hyperparameters
- **Model Training:** Details the training procedure, including the choice of loss function, optimizer, and key training settings
- **Model Evaluation:** Evaluates model performance with key metrics (accuracy, precision, recall), accompanied by relevant visualizations like confusion matrices
- **Fine Tuning:** Explores post-training refinement techniques, such as transfer learning, specifying layers adjusted and observed improvements
- **Analysis:** Conducts a succinct analysis of model behavior and performance, highlighting key findings and challenges faced.
- **Discussion:** Engages in a brief discussion, addressing broader implications, limitations, and potential future work inspired by the project.
- **Conclusion:** Summarizes the notebook's contributions, emphasizing its impact on breast cancer classification. Offers concise recommendations for future research and development.
  
## Dataset
The Dataset that is going to be used for training and testing for the image classification model will be the Breast Histopathology Images dataset.

The dataset was originally uploaded on the Gleason Case website: http://gleason.case.edu/webdata/jpi-dl-tutorial/IDC_regular_ps50_idx5.zip

However, the website is not accessible as of now, thus we are using the dataset uploaded by Paul Mooney (https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images?datasetId=7415).

In this dataset, it consists a total of 277,524 patches of images sized 50 x 50, which was broken down from 162 whole mount images. 
Within these patches, there are 198, 738 IDC negative and 78,786 IDC positive.

## License
This project is licensed under the MIT License - see the LICENSE file for more details.

## Contact
For any enquiries, you may contact me at sitinursarahb@gmail.com
