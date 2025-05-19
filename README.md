# 🤖 MLP Classifier: Predicting Facebook Post Performance

This project applies a **Multilayer Perceptron (MLP)** neural network using `scikit-learn` to predict the popularity of Facebook posts based on metadata such as reach, likes, and interactions. The goal is to classify whether a post will be widely shared.

---

## 📌 Project Highlights

- Implemented `MLPClassifier` for binary classification
- Preprocessed data using `LabelEncoder` and `StandardScaler`
- Classified posts based on median `num_shares`
- Visualized training, cross-validation, and loss curves
- Evaluated model using accuracy and confusion matrix

---

## 📁 Dataset Description

The dataset includes Facebook live post metrics such as:
- Post type (Photo, Status, Video)
- Lifetime reach, impressions, consumptions
- Total interactions and engagement

Target variable:  
`is_popular_post` – derived from whether `num_shares` exceeds the dataset's median.

---

## 🛠️ Tech Stack

- Python
- scikit-learn
- pandas
- matplotlib
- numpy

---
