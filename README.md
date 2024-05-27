Project Title: Sentiment Analysis using Logistic Regression on Twitter Dataset

Description

This project involves performing sentiment analysis on a dataset using Logistic Regression. Two different text representation techniques are utilized: Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF). The goal is to predict sentiment labels for given text data and evaluate the performance using the F-1 Score metric.

Files

main.ipynb: The main Jupyter Notebook containing all the code for data loading, preprocessing, model training, and evaluation.
result.csv: The CSV file containing the prediction results of the model.

Installation

To run this project, you need to have the following installed:
Python 3.x
Jupyter Notebook

Required Python libraries (specified in requirements.txt)
You can install the necessary libraries using:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/sentiment-analysis-logistic-regression.git
cd sentiment-analysis-logistic-regression
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook main.ipynb
Run the cells in the notebook to execute the code step by step.

Notebook Contents
Data Loading and Preprocessing
The dataset is loaded and preprocessed to remove any irrelevant information and prepare it for model training.
Text Representation
The text data is transformed using two techniques:
Bag of Words (BoW)
Term Frequency-Inverse Document Frequency (TF-IDF)
Model Training and Evaluation
Logistic Regression models are trained using the transformed text data.
The performance of the models is evaluated using the F-1 Score metric.

Results
The prediction results are saved in result.csv.

Summary of model performance:
F-1 Score using Bag of Words: 0.5315
F-1 Score using TF-IDF: 0.5559

Conclusion
This project demonstrates the application of Logistic Regression for sentiment analysis using different text representation techniques. The TF-IDF representation yielded a slightly better F-1 Score compared to the Bag of Words approach.
