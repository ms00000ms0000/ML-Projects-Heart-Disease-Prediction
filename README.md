# ❤️ Heart Disease Prediction System — Machine Learning Model  

## 📘 Project Description  
The **Heart Disease Prediction System** is a **Machine Learning-based project** designed to predict the **likelihood of heart disease** in an individual using key **medical attributes** such as **Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), Fasting Blood Sugar (fbs), Resting ECG (restecg), Maximum Heart Rate (thalach), Exercise-Induced Angina (exang), Oldpeak, Slope, CA, and Thal**.  

Using a **Logistic Regression** model, the system achieved an impressive **accuracy of 85%**, making it effective for **early detection and cardiovascular risk assessment**.  
Comprehensive **Exploratory Data Analysis (EDA)** was performed to identify key risk indicators and analyze their correlation with heart disease occurrence.  

This project demonstrates how **machine learning** can assist in **preventive healthcare**, helping medical professionals and patients make informed decisions for better cardiovascular health outcomes.  

---

## 🔍 About the Project  
This project showcases the real-world application of **supervised classification algorithms** in **medical diagnostics**.  
By analyzing clinical data, the model predicts whether a person is likely to have heart disease, aiding in **early intervention** and **risk management**.  
It highlights how **data-driven predictive systems** can complement traditional healthcare approaches for more accurate results.  

---

## 🧠 Model Architecture  
The project utilizes the **Logistic Regression** algorithm, a powerful and interpretable classification model ideal for binary outcomes like disease presence or absence.  

* **Algorithm:** Logistic Regression  
* **Problem Type:** Binary Classification  
* **Evaluation Metrics:** Accuracy, Confusion Matrix, Precision, Recall, F1-score  

---

## 🧾 Dataset Description  
The dataset includes various **medical and physiological parameters** that serve as predictors for heart disease.  

| Feature Name  | Description |
| :------------- | :------------------------------------------------------------ |
| `age` | Age of the patient |
| `sex` | Gender (1 = male, 0 = female) |
| `cp` | Chest pain type (4 types indicating severity) |
| `trestbps` | Resting blood pressure (in mm Hg) |
| `chol` | Serum cholesterol level (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| `restecg` | Resting electrocardiographic results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = yes, 0 = no) |
| `oldpeak` | ST depression induced by exercise relative to rest |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels colored by fluoroscopy |
| `thal` | Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect) |
| `target` | Output variable (1 = heart disease, 0 = no disease) |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and cleaning  
* **Scikit-learn** – Model building and evaluation  
* **Matplotlib / Seaborn** – Data visualization and EDA  

---

## 🚀 Features  
* Predicts **heart disease risk** based on multiple medical factors  
* Performs detailed **EDA** for understanding key health indicators  
* Uses **Logistic Regression** for interpretable and efficient classification  
* Achieves **85% model accuracy** on test data  
* Useful for **preventive healthcare** and **early diagnosis** support  

---

## 📊 Results  
The **Logistic Regression** model achieved an **85% accuracy**, showing strong predictive capability in identifying patients at risk of heart disease.  

---

## 📁 Repository Structure  

```
📦 ML_Project_Heart_Disease_Prediction
│
├── Heart_Disease_Prediction.ipynb                                           # Complete Jupyter Notebook implementation
├── heart_disease_data.csv                                                   # Dataset used for training and testing
└── README.md                                                                # Project documentation
```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Project-Heart-Disease-Prediction.git
   cd ML-Project-Heart-Disease-Prediction
   ```

2. **Install dependencies:**
    ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook heart_disease_prediction.ipynb
   ```

4. **Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Integrate GridSearchCV for hyperparameter tuning

* Develop a Streamlit web app for real-time prediction and user input

* Compare results with other models like Random Forest, SVM, and XGBoost

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
