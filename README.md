# Spam Mail Classifier
This project is a Spam Mail Classifier designed to categorize email messages as either Spam or Not Spam using Logistic Regression. The classifier analyzes the text of emails to determine the likelihood of them being spam based on various features.

## Project Overview

The objective of this project is to provide an efficient and lightweight spam detection system using Logistic Regression. By applying natural language processing (NLP) techniques and statistical methods, the classifier identifies common patterns in spam messages and accurately distinguishes them from legitimate emails.

## Features

Preprocessing of text data (e.g., tokenization, stopword removal, stemming/lemmatization).

Feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency).

Logistic Regression for binary classification.

Lightweight and interpretable model.

Accuracy evaluation metrics such as Precision, Recall, F1-score, and Confusion Matrix.

## Technologies Used
<ul>
<li>Python</li>

<li>scikit-learn</li>

<li>NumPy</li>

<li>pandas</li>
</ul>

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/username/spam-mail-classifier.git
```
Navigate to the project directory:
```bash
cd spam-mail-classifier
```
Set up a virtual environment (optional but recommended):
```bash
python -m venv env
source env/bin/activate  # For Unix/MacOS
env\Scripts\activate    # For Windows
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```
Place the dataset file in the data/ directory or update the data_path variable in the script to the location of your dataset.

## Dataset

The classifier requires a labeled dataset of emails, with each entry indicating whether a message is Spam or Not Spam. 

## How It Works

Text Preprocessing: The input emails undergo cleaning steps, including removing punctuation, numbers, and stopwords. Words are tokenized and processed through lemmatization or stemming.

Feature Extraction: The cleaned text is converted into numerical data using the TF-IDF vectorization technique.

Model Training: The Logistic Regression model is trained to optimize weights that minimize classification errors.

Prediction: For new emails, the model calculates the likelihood of the email being spam and assigns the appropriate label.

## Accuracy:96.68%

## Images
![image](https://github.com/user-attachments/assets/cdac64dc-b0f7-419a-bc0a-193a53bb4ced)
![image](https://github.com/user-attachments/assets/ec5ef8fb-8fa4-45eb-8be2-b885de485280)

## License

This project is licensed under the Apache 2.0 License. Refer to the LICENSE file for complete details.
