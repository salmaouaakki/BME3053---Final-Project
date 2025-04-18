# BME3053---Final-Project
# Alzheimer's MRI Classification — Final Project

This project trains a Convolutional Neural Network (CNN) to classify MRI brain images into four categories of cognitive impairment using TensorFlow and a public dataset from Kaggle.

## Repository

**Notebook file**: `Alzheimers_Final_Project.ipynb`  
**Repository name**: `BME3053---Final-Project`  
**Author**: Salma Ouaakki (GitHub username: `salmaouaakki`)

## Dataset

The dataset used in this project is publicly available on Kaggle:

**Title**: [Best Alzheimer MRI Dataset (99% Accuracy)](https://www.kaggle.com/datasets/lukechugh/best-alzheimer-mri-dataset-99-accuracy)

## How to Run This Notebook in Google Colab

Follow the steps below to run this project from start to finish in Google Colab:

### 1. Download the notebook

- Go to the GitHub repository: `https://github.com/salmaouaakki/BME3053---Final-Project`
- Download the file `Alzheimers_Final_Project.ipynb` to your local machine

### 2. Open the notebook in Google Colab

- Go to [Google Colab](https://colab.research.google.com/)
- Click on **File > Upload notebook** and select `Alzheimers_Final_Project.ipynb`

### 3. Install Kaggle API

- Run the first cell to install the Kaggle API:
  ```python
  !pip install -q kaggle

### 4. Upload your Kaggle API credentials
- Go to your kaggle account
- Scroll to the API section and click "Create New API Token"
- This will dowload a file named kaggle.json
- Back in Colab, run the second cell which will prompt you to upload the kaggle.json file. The rest of the cell will configure the key and download the dataset

### 5. Run the rest of the notebook
- After the dataset is downloaded and extracted, continue running the remining cells in the notebook sequetially.

### Output
The notebook will display:
- Model accuracy and loss over 5 training epochs
- Classificatio metrics (precision, recall, F1-score)
- Confusion matrix heatmap
- A visual grid of predicted vs. true labels for sample test images
