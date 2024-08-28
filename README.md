# Automatic Ticket Classification

## Overview:
This project aims to build an automated system for classifying customer complaints into predefined categories based on the products and services they mention. The goal is to improve customer support efficiency for a financial company by leveraging Natural Language Processing (NLP) and machine learning techniques.

## Problem Statement:
Customer complaints in financial companies are crucial as they reveal potential issues in products and services. Manually evaluating and assigning these complaints to relevant departments is labor-intensive. This project automates this process, allowing for quicker resolution and improved customer satisfaction.

## Business Goal:
Develop a model to classify customer complaints into one of the following categories:
- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others
  
By accurately categorizing complaints, the system will facilitate efficient ticket handling and provide insights into recurring issues.

## Dataset:
The dataset consists of 78,313 customer complaints in JSON format with 22 features. The data needs to be converted into a DataFrame for processing.

## Steps and Implementation:
1. Data Loading:
- Load the JSON data into a pandas DataFrame.

2. Text Preprocessing:
- Clean and preprocess the text data (e.g., remove stopwords, punctuation, and perform tokenization and lemmatization).

3. Exploratory Data Analysis (EDA):
- Analyze the data distribution, word frequency, and other relevant statistics.

4. Feature Extraction:
- Extract features using techniques such as TF-IDF or Count Vectorization.

5. Topic Modelling:
- Apply Non-Negative Matrix Factorization (NMF) to identify and group similar complaints into clusters.

6. Model Building:
- Train and evaluate several supervised learning models (e.g., Logistic Regression, Naive Bayes, Decision Tree, Random Forest).

7. Model Training and Evaluation:
- Evaluate models using metrics such as accuracy, precision, recall, and F1-score to select the best model.

8. Model Inference:
- Classify new complaints using the selected model.

## Dependencies:
- Jupyter Notebook
- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- spacy
- matplotlib
- seaborn
- swifter
- wordcloud

## Contributing
If you'd like to contribute, follow these steps:
1. Fork the repository.
2. Create a new branch for your changes.
3. Make your contributions.
4. Submit a pull request.

## License
This project is open source and available under the Apache License 2.0.

## Contact:

<a href="https://telegram.me/Rkch38" target="_blank"><img src="https://img.shields.io/badge/Messenger-Rkch38-blue?style=for-the-badge&logo=messenger"></a>

<a href="mailto:rkchoudharyritik2@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-rkchoudharyritik2@gmail.com-blue?style=for-the-badge&logo=gmail"></a>

</br>

---

<h5 align="center">© 2024-25 Ritik.</h5>

