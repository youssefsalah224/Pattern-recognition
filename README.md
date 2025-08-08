# 🌸 Pattern Recognition Project

**Machine Learning • Iris Dataset • Classification & Clustering**

A full walkthrough of pattern recognition techniques using the Iris dataset. This project showcases data operations, dimensionality reduction, multiple machine learning models, clustering, and predictions using Python and scikit-learn.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Flow](#project-flow)
- [Machine Learning Models](#machine-learning-models)
- [Clustering Techniques](#clustering-techniques)
- [Predictions](#predictions)
- [Results](#results)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Author](#author)

---

## 🧠 Overview

This notebook-based project demonstrates the core pipeline of pattern recognition:

- Data preprocessing & exploration
- Feature extraction using PCA
- Training multiple machine learning models
- Clustering with unsupervised algorithms
- Making predictions on new samples

---

## 🌼 Dataset

We use the **Iris dataset**, which contains 150 samples from 3 species of Iris flowers (`Setosa`, `Versicolor`, `Virginica`) with 4 features each:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width

---

## 🔁 Project Flow

### 1. **Reading the Data**
- The dataset is loaded and preprocessed using `pandas`.

### 2. **Shuffling the Data**
- Data is shuffled to remove any ordering bias and ensure random distribution.

### 3. **Data Information & Description**
- `.info()` gives us datatype and null value checks.  
- `.describe()` provides statistical metrics such as mean, std, min, and max values.

### 4. **Plotting Labels**
- Bar plots show balanced class distribution (50 samples per class).  
- Pair plots visualize relationships among features.

### 5. **Splitting the Dataset**
- The dataset is split into **80% training** and **20% testing** using `train_test_split`.

### 6. **Data Preprocessing**
- Features are standardized using `StandardScaler` to normalize feature values.

### 7. **Feature Extraction**
- Principal Component Analysis (PCA) is applied to reduce the data to **2 dimensions**.

---

## 🤖 Machine Learning Models

A variety of classification algorithms were applied to the PCA-reduced dataset:

- ✅ **Decision Tree**  
- ✅ **Naive Bayes**  
- ✅ **Random Forest**  
- ✅ **Support Vector Machine (SVM)**  
- ✅ **K-Nearest Neighbors (KNN)**

For each model:
- Accuracy on training and test sets is reported.
- Confusion matrix is printed for performance evaluation.

---

## 📊 Clustering Techniques

Unsupervised clustering algorithms were also used:

- **K-Means Clustering**
- **DBSCAN**

Each algorithm outputs the predicted cluster labels for the samples.

---

## 🔮 Predictions

The trained models were used to **predict 3 different sample inputs**, showing how each classifier identifies the iris class.

---

## 📈 Results

- Accuracy values vary slightly based on the dataset shuffling.
- Some models outperform others in generalization to unseen data.
- Example results (may vary):
  - SVM: 96.6% accuracy
  - KNN: 96.6%
  - Random Forest: 100%
  - Naive Bayes: 100%
  - Decision Tree: 96.6%

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/youssefsalah224/Pattern-recognition.git
cd Pattern-recognition

# (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Run the notebook
jupyter notebook
