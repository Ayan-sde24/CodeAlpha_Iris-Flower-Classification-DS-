# 🌸 Iris Flower Classification with Hyperparameter Tuning

A complete **end-to-end Machine Learning project** that classifies Iris flowers into three species — *Setosa, Versicolor, Virginica* — using supervised learning techniques.

This project goes beyond basic classification by incorporating:

* Data visualization
* Feature scaling
* Model comparison
* Hyperparameter tuning using GridSearchCV
* Custom prediction system
* File upload support (real-world usability)

---

## 🚀 Project Overview

The goal of this project is to build a robust ML pipeline that can accurately predict the species of an Iris flower based on its physical measurements.

### 📊 Input Features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### 🎯 Output:

* Predicted Species (Setosa / Versicolor / Virginica)

---

## 🧠 Machine Learning Workflow

This project follows a **complete ML lifecycle**:

1. Data Loading (Built-in + Custom Upload)
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing (Scaling)
4. Model Training (Baseline)
5. Hyperparameter Tuning (GridSearchCV)
6. Model Evaluation
7. Model Comparison
8. Prediction System
9. Model Saving

---

## ⚙️ Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Joblib
* Google Colab

---

## 🔥 Key Features

### ✅ Baseline Model

* Logistic Regression for initial performance benchmark

### ⚡ Hyperparameter Tuning

* GridSearchCV used for:

  * Regularization tuning (`C`)
  * Solver selection
  * Iteration optimization

### 🌲 Model Comparison

* Logistic Regression vs Random Forest

### 📂 File Upload Support

* Users can upload their own dataset in Colab
* Makes the project flexible and real-world ready

### 📈 Visualization

* Pairplots for feature relationships
* Confusion Matrix heatmaps

### 💾 Model Persistence

* Save trained model using Joblib

---

## 📊 Results

* Achieved **~95–100% accuracy** on test data
* Tuned models provide **better generalization**
* Clean dataset leads to near-perfect classification

---

## 🧪 Hyperparameter Tuning Example

```python
param_grid = {
    'C': [0.01, 0.1, 1, 10],
    'solver': ['lbfgs', 'liblinear'],
    'max_iter': [100, 200]
}
```

GridSearchCV evaluates all combinations using **cross-validation** to find optimal parameters.

---

## 📁 Project Structure

```
📦 Iris-Classification
 ┣ 📜 iris_classification.ipynb
 ┣ 📜 README.md
 ┣ 📜 best_iris_model.pkl
 ┣ 📜 scaler.pkl
```

---

## ▶️ How to Run

1. Open Google Colab
2. Upload the notebook
3. Run all cells

### Google Colab(link):

https://colab.research.google.com/drive/16zzWJFiu6161Cg0FoEnNGKDMBopjHsbu?usp=sharing

---

## 📂 Dataset Format (For Upload)

```
sepal length (cm),sepal width (cm),petal length (cm),petal width (cm),species
5.1,3.5,1.4,0.2,setosa
```

---

## 💡 Future Improvements

* Deploy using Streamlit (interactive UI)
* Convert into REST API (Flask/FastAPI)
* Add real-time prediction dashboard
* Integrate with cloud deployment

---

## 🎯 What I Learned

* End-to-end ML pipeline design
* Importance of feature scaling
* Model evaluation techniques
* Hyperparameter tuning using GridSearchCV
* Real-world usability with file upload

---

## 👨‍💻 Author

**Ayan Mukhoapdhyay**
Master’s in Computer Science
Aspiring Software Engineer & ML Enthusiast

---

## ⭐ If you found this useful

Give this repo a ⭐ and share it on LinkedIn!
