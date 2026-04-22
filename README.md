# 🚨 Violence Detection using Deep Learning (Webcam + File Input)

## 📌 Project Overview

This project detects violent activities using deep learning.
It supports **two modes of detection**:

1. 🎥 **Real-time detection using webcam**
2. 📂 **Detection using uploaded videos (Violence / Non-Violence classification)**

The system is designed for applications like **CCTV surveillance and security monitoring**.

---

## 🎯 Objectives

* Detect violence in real-time using webcam
* Classify uploaded video/image data into **Violence / Non-Violence**
* Compare performance of **Custom CNN vs Transfer Learning model**
* Utilize GPU for faster training

---

## ⚙️ Project Pipeline

1. Dataset Collection (Merged two datasets)
2. Data Preprocessing
3. Frame Extraction from Videos
4. Model Training

   * Custom CNN
   * Transfer Learning
5. Model Evaluation
6. Real-time Prediction (Webcam)
7. File-based Prediction (Upload input)

---

## 🗂️ Project Structure

Violence_detection/
│── notebooks_cnn/        # Custom CNN notebooks
│── notebooks_tl/         # Transfer Learning notebooks
│── README.md
│── requirements.txt
│── .gitignore

---

## 🧪 Technologies Used

* Python
* TensorFlow (GPU supported)
* OpenCV
* NumPy
* Matplotlib

---

## 💻 Environment Details (GPU Compatible)

* Python: 3.10.9
* TensorFlow: 2.10.0
* NumPy: 1.23.5
* OpenCV: 4.7.0

---

## 📊 Results

### 🔹 Transfer Learning Model

* Training Accuracy: **94.31%**
* Validation Accuracy: **91.70%**
* Loss: 0.1278

### 🔹 Custom CNN Model

* Training Accuracy: **99.94%**
* Validation Accuracy: **90.75%**
* Loss: 0.0017

👉 Transfer learning provides **better generalization**, while custom CNN shows **high training accuracy (possible overfitting)**.

---

## 📁 Dataset

* Combined dataset from multiple sources
* Classes:

  * Violence
  * Non-Violence

* Kaggle Dataset : https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset
* Github Dataset: https://github.com/airtlab/A-Dataset-for-Automatic-Violence-Detection-in-Videos


---

## 📁 H5 file link 
Custom CNN : https://drive.google.com/file/d/1ADa9In1K3BvYgGN6zVPaS2O9RxZG9fM4/view?usp=drive_link

Transfer learning : https://drive.google.com/file/d/1fB8KsOPR26463B-l6Saf9Q3-CtY03KDh/view?usp=drive_link

---

## ▶️ How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/your-username/Violence_detection.git
cd Violence_detection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

```bash
jupyter notebook
```

---

## 🎥 Features

### 🔴 Real-Time Detection

* Uses webcam
* Detects violence frame-by-frame

### 📂 File-Based Detection

* Upload video
* 
* Classifies as Violence / Non-Violence

---

## 📸 Sample Outputs

https://drive.google.com/file/d/1IVcfSxdjC1Zh8stmtW0mFkZB4WFvG2bb/view?usp=sharing

---

## 🚀 Future Improvements

* Real-time alert system (SMS/Email)
* Deploy as web application
* Improve accuracy using larger dataset

---

## 👩‍💻 Author

Sania Mirza
