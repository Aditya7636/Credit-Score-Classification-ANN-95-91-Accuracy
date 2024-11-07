
# Credit Score Classification using Artificial Neural Networks (ANN) 🏦

In the world of finance, your credit score acts as a financial fingerprint, indicating your creditworthiness and influencing your access to loans, credit cards, and other financial products. This project aims to leverage machine learning to predict a person's credit score based on their financial habits and credit history, using a high-performing Artificial Neural Network (ANN) model.

## Project Overview

Financial institutions often need to assess the creditworthiness of individuals to make informed lending decisions. With years of credit-related information and banking data, this project builds an intelligent model to classify credit scores into different brackets. By automating this process, the model can assist in reducing manual efforts, enhancing decision-making, and supporting risk management strategies in finance.

## Dataset

The dataset contains various features related to a person's financial history and banking habits, which contribute to their overall credit score. Each entry represents an individual's credit information and other financial attributes used as predictors for credit score classification.

### Problem Statement

As a data scientist working in a global finance company, you have been tasked with creating a machine learning model to classify credit scores based on this dataset. The ultimate goal is to predict credit scores accurately, enabling the company to categorize clients efficiently and streamline lending processes.

## Solution Approach

Using a supervised learning approach, we developed an Artificial Neural Network (ANN) model capable of classifying credit scores with high accuracy. The model achieved approximately **95% training accuracy** and **91% validation accuracy**, demonstrating its effectiveness in predicting credit scores based on the provided financial data.

## Model Architecture

The ANN model is designed with a series of hidden layers that allow it to learn complex patterns from the input data. The architecture includes:
- Input layer corresponding to the features in the dataset
- Multiple hidden layers to capture underlying relationships and interactions
- Output layer representing the credit score classification

Hyperparameters such as the number of neurons, learning rate, and activation functions were fine-tuned to achieve optimal performance.

## Installation and Requirements

To run this project, you'll need the following libraries:
- Python 3.x
- TensorFlow or Keras for building the ANN model
- Pandas for data manipulation
- Scikit-learn for preprocessing and evaluation

Install the required libraries using:
```bash
pip install tensorflow pandas scikit-learn
```

## Project Structure

The repository is organized as follows:

```
├── data/                       # Dataset files
├── notebooks/                  # Jupyter notebooks for exploratory data analysis and model training
├── README.md                   # Project README file

## Usage

1. **Data Preprocessing**: Start by loading the data and performing preprocessing steps, including handling missing values, scaling features, and encoding categorical variables.

2. **Model Training**: The ANN model is trained on the preprocessed data, with a training-validation split to assess performance.

3. **Evaluation**: The model's accuracy is evaluated on validation data. Fine-tuning can further improve the model's accuracy if needed.

4. **Prediction**: Once trained, the model can predict credit scores for new data inputs, assisting in classifying individuals into various credit score brackets.

## Results

The model achieved:
- **95% training accuracy**
- **91% validation accuracy**

These results demonstrate the model's potential as an effective tool for automating credit score classification tasks.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.
