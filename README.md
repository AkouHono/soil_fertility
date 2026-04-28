# 🌍 Soil Fertility Prediction System

### 🚀 Machine Learning for Smart Soil Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge\&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)



## 📌 Overview

This project focuses on predicting **soil fertility levels** using Machine Learning techniques.
The system classifies soil into **three fertility categories**, helping improve agricultural decision-making.

📖 This work is part of my **baseline research study**, where I implemented and extended existing approaches.



## 🎯 Objectives

✔ Predict soil fertility into 3 classes
✔ Handle imbalanced datasets effectively
✔ Compare multiple machine learning models
✔ Improve performance using advanced techniques



## 🌱 Problem Statement

Soil fertility plays a critical role in agricultural productivity.
However, real-world datasets are often:

* Imbalanced
* Non-linear
* Complex to model

👉 This project addresses these challenges using **data balancing and ensemble learning**.



## 📊 Dataset

*  Source: Soil Fertility Dataset
*  Target: Fertility classification (3 classes)
*  Features include:

  * Soil nutrients
  * Physical and chemical properties



## ⚙️ Tech Stack

* Python
* Scikit-learn
* XGBoost
* Pandas & NumPy
* Matplotlib / Seaborn



##  Methodology



A[Dataset] --> B[Data Preprocessing]
B --> C[Class Imbalance Problem]
C --> D[SMOTE Balancing]
D --> E[Model Training]
E --> F[Model Comparison]
F --> G[Best Model: XGBoost]

### Key Steps:

* Implementation of baseline model
* Identification of **class imbalance issue**
* Application of **SMOTE (Synthetic Minority Over-sampling Technique)**
* Training multiple models on balanced data
* Evaluation and comparison



## 🧠 Models Tested

* Decision Tree
* KNN
* Logistic Regression
* SVM
* Ensemble Methods



##  Key Technique: SMOTE

* Used to handle **imbalanced dataset**
* Generates synthetic samples for minority classes
* Helps improve model generalization

---

## Results

* Significant improvement after applying **SMOTE**
* Better handling of non-linear relationships
* **XGBoost** achieved the best performance among all models
* More balanced and reliable predictions across all classes



## 🗂️ Project Structure

```bash
soil_fertility/
│── README.md
│── soil_fertility_model.ipynb
```

## ▶️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/soil_fertility.git
```

### 2️⃣ Navigate to the project

```bash
cd soil_fertility
```

### 3️⃣ Run the notebook

```bash
Google Colab
```

---

## 💡 Future Improvements

* 🔌 Integration with IoT sensors for real-time soil data
* 🌐 Deployment as a web-based system
* 🧠 Deep learning approaches for higher accuracy
* 📡 API integration for real-time predictions



## 🌍 Real-World Impact

This system can support:

* Smart Agriculture 🌱
* Soil monitoring systems
* Precision farming decisions



## 👩‍💻 Author

**GBADABIZO Akouvi Yemima Honorine**
🎓 M.Sc. Software Engineering


## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!

---

## 📌 Note

This project highlights the importance of **handling imbalanced datasets** and demonstrates how combining **SMOTE with ensemble models (XGBoost)** can significantly improve performance.
