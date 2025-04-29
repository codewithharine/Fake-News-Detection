# Fake News Detection using Machine Learning

## Overview
This project uses Natural Language Processing (NLP) and Machine Learning to classify news articles as **real** or **fake**. The model uses a dataset containing labeled news articles (fake and real) to train a classification model and predict the authenticity of new articles.

## Dataset
The project requires two datasets:
- `Fake.csv`: Contains fake news articles.
- `True.csv`: Contains real news articles.

These datasets are labeled and are used to train the model.

## Libraries Used
- **pandas**: For data manipulation.
- **scikit-learn**: For machine learning models and feature extraction.
- **matplotlib & seaborn**: For data visualization.
- **numpy**: For numerical operations.

## Steps
1. **Data Loading**: The datasets are loaded and labeled.
2. **Preprocessing**: The text data is preprocessed using TF-IDF Vectorization.
3. **Model Training**: A Logistic Regression model is trained on the vectorized data.
4. **Model Evaluation**: The model's performance is evaluated using accuracy, confusion matrix, and classification report.
5. **Prediction**: The trained model can predict whether a new news article is real or fake.

## How to Use
1. Download or clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn


Example Usage
You can test the model on a new news article:

news_text = "NASA Discovers New Earth-Like Planet"
print(predict_news(news_text))

Results
The model provides predictions on whether the input news article is real or fake.
