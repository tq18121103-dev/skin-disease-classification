# Diagnosis-of-Erythemato-Squamous-Skin-Diseases-by-Machine-Learning-Algorithms
Developed a machine learning pipeline for classifying erythemato-squamous skin diseases using clinical and histopathological features, incorporating outlier removal to achieve 100% accuracy with Gaussian Naive Bayes.

## Project Overview
This project focuses on the classification of erythemato-squamous skin diseases, which are difficult to distinguish clinically due to similar symptoms. The goal is to build a machine learning pipeline that leverages clinical and histopathological features to improve diagnostic accuracy.

---

## Dataset
- Source: Dermatology dataset  
- Samples: 366 instances  
- Features: 34 attributes (clinical + histopathological)  
- Target: 6 classes of erythemato-squamous diseases  

The dataset contains ordinal features (scaled 0–3) representing the severity of symptoms.

---

## Methodology

### 1. Data Preprocessing
- Handled missing values (age feature)
- Applied data cleaning and normalization
- Developed a custom **outlier removal algorithm** to improve data quality

### 2. Models Applied
The following machine learning algorithms were implemented and compared:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Gaussian Naive Bayes  
- Decision Tree  
- Random Forest  

---

## Results
- Best model: **Gaussian Naive Bayes**
- Achieved accuracy: **100%** after outlier removal  

The results indicate that removing noisy data significantly improves classification performance.

---

## Key Insights
- Histopathological features play a crucial role in distinguishing between similar skin diseases  
- Outlier removal helps enhance model performance and stability  
- Gaussian Naive Bayes performs exceptionally well on this structured medical dataset  

---
## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---
## Future Improvements
- Apply cross-validation to ensure model generalization
- Investigate potential overfitting (due to perfect accuracy)
- Deploy as a web-based diagnostic tool using Streamlit

---
## Author
Ngo Thuy Quynh
