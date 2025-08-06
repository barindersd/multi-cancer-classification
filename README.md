# 🧬 Multi-Cancer Classification Using Deep Learning

Early and accurate cancer detection remains one of the most critical challenges in modern healthcare. Leveraging advances in medical imaging and Artificial Intelligence (AI), this project aims to develop a **comprehensive Multi-Cancer Classification System** that utilizes **Deep Learning and Transfer Learning** to detect and differentiate between **12 distinct cancer types** spanning various organs.

---

## 🎯 Objectives

- ✅ Build a **unified multi-class deep learning model** capable of classifying multiple cancer types across organs  
- ✅ Utilize **state-of-the-art architectures** such as ResNet, EfficientNet, DenseNet, and Vision Transformers  
- ✅ Evaluate model performance using metrics like **Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrices**  
- ✅ Design a **modular, extensible pipeline** allowing easy integration of new cancer types  
- ✅ Share transparent progress and insights via **GitHub, LinkedIn, and Instagram**

---

## 📂 Dataset Structure

The dataset comprises images covering 12+ organ systems and cancer conditions, organized into subfolders by cancer type, subtype, or stage.

| Folder Name          | Cancer Type / Condition               | Subtype / Stage          |
|----------------------|-------------------------------------|-------------------------|
| `all_benign`         | Acute Lymphoblastic Leukemia (ALL)  | Benign                  |
| `brain_glioma_tumor` | Brain Cancer                        | Glioma                  |
| `breast_malignant`   | Breast Cancer                      | Malignant               |
| `cervix_koc`         | Cervical Cancer                    | KOC subtype             |
| `colon_aca`          | Colon Cancer                      | Adenocarcinoma          |
| `kidney_tumor`       | Kidney Cancer                     | Tumor                   |
| `lung_lung_scc`      | Lung Cancer                       | Squamous Cell Carcinoma |
| `lymph_cll`          | Lymphoma                         | Chronic Lymphocytic Leukemia (CLL) |
| `oral_scc`           | Oral Cancer                      | Squamous Cell Carcinoma |
| `pancreatic_tumor`   | Pancreatic Cancer                 | Tumor                   |
| `Skin_Melanoma`      | Skin Cancer                      | Melanoma                |
| ...                  | ...                              | ...                     |

---

## 🧭 Cancer Type Grouping Overview

- **Blood**  
  - ALL - Benign  
  - ALL - Early  
  - ALL - Pre  
  - ALL - Pro  

- **Brain**  
  - Glioma  
  - Meningioma  
  - Pituitary  
  - Normal  

- **Breast**  
  - Benign  
  - Malignant  

- **Cervix**  
  - DYK  
  - KOC  
  - MEP  
  - PAB  
  - SFI  

- **Colon**  
  - Adenocarcinoma  
  - Benign Tumor  

- **Kidney**  
  - Cyst  
  - Stone  
  - Tumor  
  - Normal  

- **Lung**  
  - Adenocarcinoma  
  - Squamous Cell Carcinoma  
  - Normal  

- **Lymphoma**  
  - CLL (Chronic Lymphocytic Leukemia)  
  - FL (Follicular Lymphoma)  
  - MCL (Mantle Cell Lymphoma)  

- **Oral**  
  - Squamous Cell Carcinoma  
  - Normal  

- **Pancreas**  
  - Tumor  
  - Normal  

- **Skin**  
  - Acne  
  - Actinic Keratosis  
  - Basal Cell Carcinoma  
  - Chickenpox  
  - Dermato Fibroma  
  - Dyshidrotic Eczema  
  - Melanoma  
  - Nail Fungus  
  - Nevus  
  - Normal Skin  
  - Pigmented Benign Keratosis  
  - Ringworm  
  - Seborrheic Keratosis  
  - Squamous Cell Carcinoma  
  - Vascular Lesion  

---

## 🚀 Planned Workflow

### 🔧 Data Preprocessing & Cleaning
- Image resizing, normalization, and augmentation  
- Train/validation/test splits ensuring balanced class distribution  

### 📊 Exploratory Data Analysis (EDA)
- Analyze class distributions  
- Detect dataset imbalance and potential biases  

### 🧠 Model Development
- Baseline Convolutional Neural Network (CNN)  
- Transfer Learning with EfficientNet, ResNet, DenseNet, and Vision Transformer (ViT) architectures  

### 🧪 Model Evaluation
- Evaluate models using Accuracy, Precision, Recall, F1-score, and ROC-AUC  
- Visualize results with confusion matrices for each cancer type  

### 🌐 Deployment
- Develop a web or desktop application for cancer prediction through image upload  
- Provide interactive confidence scores and user-friendly dashboards  

### 📈 Continuous Learning & Updates
- Regular updates on GitHub including training logs, model checkpoints, and visualizations  
- Incorporate user feedback and new data to improve model performance  

---

## 🧾 Tech Stack (Planned)

- **Languages:** Python 3.10  
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib, OpenCV  
- **Tools:** Jupyter Notebook, Git, Streamlit (for deployment)  
- **Hardware:** GPU-enabled cloud environment or local CUDA setup  

---

## 📣 Stay Tuned

This repository will be regularly updated with EDA charts, training results, deployment features, and more. 

> 💬 **Follow the project**, **contribute ideas**, or reach out if you're passionate about AI in healthcare. Let's build an impactful system — together.

---

## 🔗 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/16barindersingh/)  
- 💻 [GitHub](https://github.com/barindersd)

---

> **Disclaimer:** This project is for educational and research purposes only. It is not intended for clinical use or diagnosis.
