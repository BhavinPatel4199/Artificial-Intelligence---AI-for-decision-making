# Text Classification using Machine Learning Models : IMBD dataset analysis

This repository contains a project focused on classifying text data using various machine learning models. The goal is to build an efficient classifier that can accurately predict the sentiment of the text.

## Project Overview

- Text classification is a critical task in natural language processing (NLP). This project aims to classify text data into different categories using machine learning algorithms. 
- The focus is on comparing the performance of models like Random Forest, Gradient Boosting, and XGBoost, and selecting the most efficient model based on accuracy and computation time.

## Dataset : "IMBD_dataset.csv"

## Project Structure

1. **Data Preprocessing**:
   - Cleaning the text data by removing noise, tokenization, and other preprocessing steps to make the data suitable for model training.

2. **Model Selection**:
   - Implementing various machine learning models, including Random Forest, Gradient Boosting, and XGBoost, to classify the text data.

3. **Hyperparameter Tuning**:
   - Using GridSearchCV to optimize the model parameters and improve performance.

4. **Evaluation**:
   - Comparing the models based on accuracy, classification reports, and computation time. 
   - The project considers the trade-off between model performance and computational efficiency.

5. **Conclusion**:
   - Based on the evaluation, the Random Forest model was chosen due to its balance between performance and computational efficiency.

## How to Run

To run this project, clone the repository and ensure you have the necessary dependencies installed. The project is implemented in a Jupyter notebook.

### Dependencies

	•	Python 3.x
	•	Jupyter Notebook
	•	Scikit-learn
	•	Pandas
	•	NumPy
	•	XGBoost
	•	Matplotlib
	•	Seaborn
