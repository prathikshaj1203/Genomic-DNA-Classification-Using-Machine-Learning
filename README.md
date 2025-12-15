# Genomic DNA Classification Using Machine Learning

## 📌 Project Overview
This project focuses on classifying genomic DNA sequences using machine learning techniques. 
DNA sequences are composed of nucleotide bases (A, T, C, G), which cannot be directly processed by machine learning models. 
Hence, feature extraction is performed using k-mer based encoding, followed by classification using a Random Forest model.

---

## 🎯 Problem Statement
To develop a machine learning model that can automatically classify genomic DNA sequences by learning patterns from nucleotide data.

---

## 🧬 Dataset Description
- Training dataset: 100,000 labeled DNA sequences
- Test dataset: 20,000 unlabeled DNA sequences
- Each DNA sequence consists of characters A, T, C, and G
- Binary classification problem

---

## ⚙️ Methodology
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature extraction using k-mers (k = 3)
4. Numerical encoding using CountVectorizer
5. Model training using Random Forest
6. Model evaluation using F1-score and confusion matrix

---

## 🧠 Machine Learning Flow
DNA Sequence → k-mer Extraction → Numerical Features → Random Forest → Classification

yaml
Copy code

---

## 📊 Results
- Achieved F1-score of approximately **0.98**
- Balanced precision and recall
- Confusion matrix shows minimal misclassification

---

## 🧪 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📁 Project Structure
Genomic-DNA-Classification-ML/
│
├── notebook/
├── data/
├── images/
├── README.md
└── requirements.txt

yaml
Copy code

---

## 🚀 Future Scope
- Extend to multi-class genomic classification
- Apply deep learning models (CNNs, RNNs)
- Integrate confidence scoring for predictions

---

## 📌 Author
Prathiksha J
