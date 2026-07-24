# SMS Spam Detection 📱✉️

This project implements a machine learning pipeline to classify SMS messages as **spam** or **ham** (not spam) using Natural Language Processing (NLP) and Logistic Regression.


## 📖 Project Overview
- Dataset: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Preprocessing: Lowercasing, removing punctuation/numbers, optional stopword removal
- Feature Extraction: TF–IDF Vectorization
- Model: Logistic Regression
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix


## ⚙️ Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/RitishM-cloud/SMS-spam-detection.git
   cd SMS-spam-detection
pip install -r requirements.txt
jupyter notebook sms_spam_detection.ipynb
pip install pandas matplotlib scikit-learn nltk
