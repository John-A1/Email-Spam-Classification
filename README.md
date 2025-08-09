# Email-Spam-Classification

## 📌 Overview
This project implements a **Machine Learning model** to classify emails as **Spam** or **Not Spam** (Ham) using a labeled dataset.  
It uses **Natural Language Processing (NLP)** techniques to preprocess email text, extract features using **TF-IDF**, and trains a **Naive Bayes classifier** for accurate spam detection.

---

## 📂 Project Structure/
├── spam and ham classification.csv # Dataset (spam/ham labeled)/ 
├── Preprocess the datasetspam_classifier_model.pkl # Saved trained model
├── Feature extraction using TfidfVectorizer
├── Train model using Naive Bayes (MultinomialNB)
├── predict
├── Evaluate the model  
\


Accuracy: 0.9644644644644644

Confusion Matrix:

 [[1012   46]
 [  25  915]]
 
Classification Report:

               precision    recall  f1-score   support

           0       0.98      0.96      0.97      1058
           1       0.95      0.97      0.96       940

    accuracy                           0.96      1998
   macro avg       0.96      0.96      0.96      1998
weighted avg       0.96      0.96      0.96      1998


[ ]
Colab paid products - Cancel contracts here
