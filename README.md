# **Skin Lesion Classification Using Machine Learning**  

## **📌 Project Overview**  
This project classifies skin lesions using **multiple machine learning models**, comparing their performance on **dermoscopic images**.  

🔹 **Feature Extraction:** GLCM & LBP  
🔹 **Preprocessing:** Hair removal, contrast enhancement  
🔹 **Classifiers:**  
✅ **Support Vector Machine (SVM)**  
✅ **Logistic Regression (LR)**  
✅ **Random Forest (RF)**  
✅ **K-Nearest Neighbors (K-NN)**  
🔹 **Platform:** Google Colab  

---

## **📂 Dataset**  
The dataset contains images categorized into:  
- **BCC (Basal Cell Carcinoma)**  
- **SCC (Squamous Cell Carcinoma)**  
- **MEL (Melanoma)**

The dataset used in this repository: https://drive.google.com/drive/folders/1budKcRq732JuZRc8kOWHzgDRQGRcHOXf?usp=sharing


📌 **Dataset Location:**  
- Stored in **Google Drive** (`/content/drive/My Drive/SkinLesion_dataset_aug`)  
- Preprocessed images saved in `/content/drive/My Drive/SkinLesion_Preprocessed_aug`  

## **🚀 How to Run the Project**  
Each model has its own Google Colab notebook. Click the google colab link in each file



### **1️⃣ Install Dependencies**  
Each notebook requires the same dependencies. Run this in a Colab cell:  
```python
!pip install numpy pandas scikit-learn opencv-python
```

---

### **2️⃣ Preprocess Images**  
Run the preprocessing function to apply **hair removal and contrast enhancement** in each notebook.  

---

### **3️⃣ Extract Features (GLCM & LBP)**  
Each notebook extracts texture features from the images using **GLCM & LBP**.  

---

### **4️⃣ Train & Evaluate Models**  
Each notebook trains a different classifier and evaluates it:  

- **SVM (Support Vector Machine)**
- **Logistic Regression (LR)**
- **Random Forest (RF)**
- **K-Nearest Neighbors (K-NN)**  


## **📌 Project Structure**  
```
📂 Google Colab Notebooks
│── 📂 /content/drive/My Drive/SkinLesion_dataset_aug/    # Original dataset
│── 📂 /content/drive/My Drive/SkinLesion_Preprocessed_aug/ # Preprocessed images
│── 📄 SVM.ipynb         # SVM Model Notebook
│── 📄 LR.ipynb          # Logistic Regression Notebook
│── 📄 RF.ipynb          # Random Forest Notebook
│── 📄 KNN.ipynb         # K-NN Model Notebook
```

---

## **📜 License**  
This project is open-source under the **MIT License**.  

---
