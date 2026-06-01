# Spam Email Classifier

## Overview

This project is a Machine Learning-based Spam Email Classifier that detects whether an email is **Spam** or **Ham (Not Spam)**. The model uses Natural Language Processing (NLP) techniques and the Naive Bayes algorithm to classify email messages.

## Features

* Email text preprocessing
* TF-IDF feature extraction
* Spam/Ham classification
* Machine Learning model training and testing
* Performance evaluation using accuracy score

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Dataset

The dataset used contains email messages labeled as:

* Spam
* Ham (Not Spam)

Dataset File: `spamham.csv`

## Project Workflow

### 1. Data Collection

Load the dataset containing email messages and their labels.

### 2. Data Preprocessing

* Handle missing values
* Separate features and target labels
* Convert text data into numerical format using TF-IDF Vectorization

### 3. Train-Test Split

Split the dataset into:

* Training Data (75%)
* Testing Data (25%)

### 4. Model Training

Train the classifier using:

* Bernoulli Naive Bayes

### 5. Model Evaluation

Evaluate the model using:

* Accuracy Score
* Predictions on test data

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/spam-email-classifier.git
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Run the Project

Open Jupyter Notebook and execute:

```bash
spam_email_classifier.ipynb
```

## Results

The model successfully classifies emails as Spam or Ham using Natural Language Processing and Machine Learning techniques.

## Future Improvements

* Use advanced algorithms such as SVM and Random Forest
* Deploy the model using Flask or Streamlit
* Improve accuracy with additional preprocessing techniques

## Author

Bellaganti Harika

## License

This project is created for educational and internship purposes.
