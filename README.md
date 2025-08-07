# Design-and-analysis-of-Human-Activity-Recognition-system-using-Machine-Learning-Techniques
🤖 Classifies human activities using smartphone sensor data with ML models like Random Forest, Logistic Regression, and k-NN. Accuracy: 95%+
# 🤖 Human Activity Recognition (HAR) using Machine Learning

This project focuses on building a machine learning pipeline to classify human physical activities (like walking, sitting, standing, etc.) using smartphone sensor data. It combines real-world dataset handling, model evaluation, and comparative analysis of classification algorithms.

---

## 📊 Dataset Overview

- **Source:** UCI HAR Dataset (via Kaggle / direct download)
- **Files Used:** `train.csv`, `test.csv`
- **Type:** Multivariate time series data from smartphone inertial sensors

### Key Features:
- Body acceleration signals (X, Y, Z)
- Gyroscope angular velocity
- Total acceleration
- Extracted time and frequency domain features

### Target Labels:
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

---

## 🌐 Technologies Used

| Category | Tools |
|---------|-------|
| Language | Python 3.x |
| Libraries | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| ML Models | Logistic Regression, Random Forest, k-Nearest Neighbors |

---

## 🛠️ Step-by-Step Workflow

### 1. Data Handling & Preprocessing
- Loaded `train.csv` and `test.csv`
- Checked for missing values (none found)
- Verified class balance across all activity types
- Standardized feature values using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Visualized activity distribution
- Correlation heatmap of selected features
- Optional dimensionality reduction using PCA (if required for better performance)

### 3. Model Building

#### Logistic Regression:
- Trained on scaled data
- Good performance on linearly separable features

#### Random Forest:
- Used for non-linear pattern recognition
- Tuned number of trees and max depth
- Output: Feature importance visualization

#### k-NN:
- Distance-based classifier
- Hyperparameter tuning via cross-validation for best `k`

### 4. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- Time taken by each model (training + prediction)

---

## 🌟 Model Comparison Summary

| Model | Accuracy | Time Taken | Notes |
|-------|----------|------------|-------|
| Logistic Regression | 92% | Fast | Good baseline |
| Random Forest | 95%+ | Medium | Best performer |
| k-NN | 93% | Slow | Sensitive to `k` |

---

## 📊 Key Insights
- Random Forest achieved the best accuracy with stable generalization.
- Logistic Regression is fast and interpretable.
- k-NN performs well but is resource-intensive.
- Smartphone sensors + ML can effectively detect human activities.

---

## 🎨 Visualizations
- Activity distribution bar chart
- Confusion matrix heatmaps
- Accuracy comparison plot
- Feature importance (Random Forest)

---

## 📁 Repo Structure

```
├── train.csv
├── test.csv
├── har_model_comparison.ipynb
├── activity_visuals/
│   ├── confusion_matrix.png
│   └── accuracy_plot.png
└── README.md
```

---

## 🌟 What I Learned
- Applied full machine learning cycle on a real-world dataset
- Understood strengths/weaknesses of classic classifiers
- Improved skills in data scaling, evaluation, visualization
- Validated models with robust metrics & practical comparisons

---

## 📄 Ideal For
- Resume & ML project portfolio
- Showcasing ML workflow skills (preprocessing, modeling, evaluation)
- Highlighting interest in wearable tech / real-world data applications

---

## 👋 Let’s Connect

- 📧 harsh201130@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/harsh-sharma-354379294/)

---
