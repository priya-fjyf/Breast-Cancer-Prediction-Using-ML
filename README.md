# 🧬 Breast Cancer Prediction (ML Classification)

This project uses **Machine Learning** techniques to predict whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on diagnostic features of cell nuclei from breast mass images.

---

## 📊 Dataset

- **Dataset**: Breast Cancer Wisconsin (Diagnostic)  
- **Source**: Kaggle
- **Total Instances**: 569  
- **Features**:  
  - Radius, Texture, Perimeter, Area, Smoothness, Compactness, Concavity, etc.  
- **Target Variable**:  
  - Diagnosis: `M` = Malignant, `B` = Benign  

---

## 🧠 ML Techniques Used

- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Model Evaluation using:
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report  

---

## 📚 Libraries Used

python
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn

## 📈 Output / Results

### ✅ Model Accuracy:
- Logistic Regression: **96.5%**
- Random Forest: **97.2%**
- SVM: **96.8%**
- KNN: **95.4%**

> ✅ **Best Performing Model:** Random Forest (Based on Accuracy & Confusion Matrix)

### 📊 Visualizations:
- Correlation Heatmap of Features
- Count Plot of Malignant vs Benign Tumors
- Distribution Plots of Key Features (Radius, Texture, Area)
- Confusion Matrix for Model Comparison

###  📌 Key Insights:
- Malignant tumors tend to have higher mean radius, perimeter, and area.
- High correlation found between radius_mean, perimeter_mean, and area_mean.
- Random Forest provided the most balanced and accurate predictions.


