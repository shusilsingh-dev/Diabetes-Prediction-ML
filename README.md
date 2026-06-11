# 🩺 Diabetes Prediction using Machine Learning

A Machine Learning project that predicts whether a person is diabetic or non-diabetic using medical attributes. This project uses the **PIMA Indians Diabetes Dataset** and applies **Logistic Regression** for classification.

---

## 📌 Project Overview

The objective of this project is to build a predictive model that can determine the likelihood of diabetes based on several health-related features such as glucose level, blood pressure, insulin, BMI, and age.

The project includes:

* Data preprocessing
* Handling invalid values
* Feature scaling using StandardScaler
* Model training using Logistic Regression
* Accuracy evaluation
* Diabetes prediction system

---

## 📂 Dataset Information

The dataset used in this project is the **PIMA Indians Diabetes Dataset**.

### Features Used

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

### Target Variable

* **Outcome**

  * `0` → Non-Diabetic
  * `1` → Diabetic

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Data preprocessing and handling missing/invalid values
4. Feature selection and standardization
5. Split data into training and testing sets
6. Train Logistic Regression model
7. Evaluate model accuracy
8. Build prediction system

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction-ML.git
```

### 2. Navigate to the Project Folder

```bash
cd Diabetes-Prediction-ML
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```txt
diabetes_prediction.ipynb
```

---

## 📊 Model Used

**Logistic Regression**

Logistic Regression is used as the classification algorithm to predict whether a patient is diabetic or not based on medical input values.

---

## 📁 Project Structure

```txt
Diabetes-Prediction-ML/
│── diabetes_prediction.ipynb
│── diabetes.csv
│── requirements.txt
│── README.md
│── LICENSE
```

---

## 📈 Future Improvements

* Add more ML algorithms for comparison
* Deploy as a web application using Flask or Streamlit
* Improve model accuracy through hyperparameter tuning

---

## 👨‍💻 Author

**Shusil Singh**

If you found this project useful, feel free to ⭐ the repository.
