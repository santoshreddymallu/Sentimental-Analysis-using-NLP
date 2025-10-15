# Sentimental-Analysis-using-NLP

Certainly! Here's a comprehensive and well-structured README file tailored for your [Sentiment-Analysis-using-NLP](https://github.com/santoshreddymallu/Sentiment-Analysis-using-NLP) GitHub repository:

---

This project demonstrates how to perform sentiment analysis on text data using Natural Language Processing (NLP) techniques. The goal is to classify text into positive or negative sentiments, providing valuable insights for applications such as customer feedback analysis, social media monitoring, and more.

## 🧠 Project Overview

The repository includes:

* **Data Preprocessing**: Cleaning and preparing text data for analysis.
* **Model Training**: Building and training a sentiment analysis model.
* **Model Evaluation**: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score.
* **Deployment**: Creating a user-friendly interface for real-time sentiment prediction.

## 📁 Project Structure

```
Sentiment-Analysis-using-NLP/
├── app.py                   # Streamlit application for user interface
├── best_sentiment_model.pkl # Trained sentiment analysis model
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7 or higher installed. It's recommended to use a virtual environment.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/santoshreddymallu/Sentiment-Analysis-using-NLP.git
   cd Sentiment-Analysis-using-NLP
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

To launch the Streamlit application:

```bash
streamlit run app.py
```

This will start a local server and open the application in your default web browser.

## 🧪 Model Details

The sentiment analysis model is built using:

* **TF-IDF Vectorizer**: Converts text data into numerical format.
* **Logistic Regression Classifier**: Classifies text into positive or negative sentiments.

The model is trained on a dataset of labeled text data and saved as `best_sentiment_model.pkl`.

## 📊 Evaluation Metrics

The model's performance is evaluated using:

* **Accuracy**: Percentage of correct predictions.
* **Precision**: Proportion of positive predictions that are actually positive.
* **Recall**: Proportion of actual positives that are correctly identified.
* **F1-Score**: Harmonic mean of precision and recall.

## 📸 Screenshots


