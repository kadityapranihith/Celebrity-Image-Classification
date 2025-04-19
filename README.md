# 🧠 Celebrity Image Classification

A machine learning project to classify images of five popular personalities:

- **Sundar Pichai**  
- **Elon Musk**  
- **Mukesh Ambani**  
- **Satya Nadella**  
- **Jeff Bezos**  

---

## 📌 Steps Followed

### 1. 📥 Image Collection  
- Collected images using the **Fatkun Batch Downloader** Chrome extension  
- Gathered ~200+ images 

### 2. 🧹 Data Cleaning  
- Used **OpenCV and Haar Cascade** for face and eye detection  
- Filtered images to include only those with clearly visible faces  

### 3. 📐 Feature Extraction  
- Applied **PyWavelets (Discrete Wavelet Transform)**  
- Combined wavelet features with raw pixel data  

### 4. 🤖 Model Building  
- Used **GridSearchCV** to optimize hyperparameters  
- Tried the following classifiers:
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  

### ✅ Results  
- **Best Model**: Logistic Regression  
- **Accuracy Achieved**: ~81%

---

## 🧪 Tech Stack

- Python  
- OpenCV  
- scikit-learn  
- PyWavelets  
- NumPy & Pandas  

---



