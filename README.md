# 🎓 Academic Success Prediction Using Machine Learning and Neural Networks

## 📖 Overview

This project was developed for the **CSE422 – Artificial Intelligence** course at **BRAC University**. The objective is to predict students' academic outcomes using Machine Learning and Neural Network models based on demographic, academic, and socioeconomic features. The model classifies students into one of three categories:

* Graduate
* Dropout
* Enrolled

The project aims to help educational institutions identify students who are at risk of dropping out and provide timely academic support.

---

## 📂 Repository Contents

```
.
├── CSE422_project.ipynb      # Jupyter Notebook containing the implementation
├── Project_Report.pdf        # Complete project documentation
└── README.md                 # Project overview
```

---

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

---

## 📊 Dataset

The dataset consists of **4,424 student records** with **24 input features**. It is a multiclass classification problem where the target variable contains three classes:

* Graduate
* Dropout
* Enrolled

The dataset was preprocessed by:

* Handling missing values
* Label encoding
* Feature scaling using StandardScaler
* Handling imbalanced data
* Train-test splitting using Stratified Sampling

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Neural Network

---

## 📈 Results

| Model          | Accuracy |
| -------------- | -------- |
| Random Forest  | **85%**  |
| Decision Tree  | 79%      |
| Neural Network | 75%      |
| KNN            | 60%      |

Among all the models, **Random Forest** achieved the best performance with the highest accuracy and AUC score, making it the most suitable model for predicting student academic success.

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/fuadifti/Academic_Success_Prediction.git
```

2. Install the required Python libraries.

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

3. Open the notebook.

```bash
jupyter notebook CSE422_project.ipynb
```

4. Run all cells sequentially.

---

## 📄 Project Report

A detailed explanation of the project, preprocessing steps, model implementation, and performance evaluation is available in the accompanying PDF report.

---

## 👨‍💻 Authors

* **Moutasim Fuad Ifti**
* **Sagar Sarker**

---

## 📚 Course Information

**Course:** CSE422 – Artificial Intelligence

**Institution:** BRAC University

---

## ⭐ Acknowledgements

This project was completed as part of the Artificial Intelligence coursework to explore and compare different Machine Learning and Neural Network models for student academic success prediction.

