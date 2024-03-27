#  Article Categorization with Natural Language Processing

This project focuses on classifying articles into different categories using Natural Language Processing (NLP) techniques. It involves preprocessing text data, training various machine learning models, and evaluating their performance.

## Introduction

Text classification is a common task in NLP, with applications ranging from sentiment analysis to spam detection. In this project, we aim to classify articles into categories such as sports, economy, culture, politics, and society.

## Setup

To run this project, follow these steps:

1. Install the required Python libraries:
    ```
    pip install -r requirements.txt
    ```

2. Run the Jupyter Notebook `ArticlesClassification.ipynb` to see the code implementation.

## File Structure

- `ArticlesClassification.ipynb`: Jupyter Notebook containing the code for data preprocessing, modeling, and evaluation.
- `labels.txt`: File containing category labels for articles.
- `data`: Folder containing text files of articles.

## Usage

1. Load the article data from text files and preprocess it.
2. Train different machine learning models (e.g., Logistic Regression, Random Forest, Naive Bayes) using the preprocessed data.
3. Evaluate the models' performance using accuracy metrics.
4. Make predictions on new article data using the best-performing model.

## Visualizations

The project includes various visualizations for data exploration, such as:
- Detailed Count Plot of Article Categories
- Word Clouds for Each Category
- Bar Plot of Top 20 Most Frequent Words
- Box Plot of Article Word Counts by Category
- Pie Chart of Category Distribution

## Requirements

The project requires the following Python libraries:
- scikit-learn
- nltk
- seaborn
- matplotlib
- pandas
- wordcloud

These dependencies can be installed using the `requirements.txt` file.

## Author

EL ARGOUBI Chaimaa
