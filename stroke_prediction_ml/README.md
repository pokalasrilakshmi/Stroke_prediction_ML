# 🧠 Stroke Risk Prediction Dashboard Using Machine Learning

🚀 **Live Application:** [Stroke Prediction Dashboard](https://stroke-prediction-ai.streamlit.app/)

## 📌 Project Overview

Stroke Risk Prediction is a Machine Learning-based application that estimates the probability of stroke based on health and lifestyle factors.

The system analyzes patient information such as age, BMI, average glucose level, hypertension, heart disease, and smoking habits to estimate stroke risk.

The project demonstrates an end-to-end Machine Learning workflow, integrated with an interactive Streamlit dashboard.

## ✨ Key Features

- Data preprocessing and cleaning
- Handling missing values
- Encoding categorical variables
- Machine Learning model training
- Stroke risk prediction
- Interactive Streamlit dashboard
- Risk visualization using charts and progress bars
- Health and lifestyle recommendations

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Scikit-learn | Machine Learning |
| Matplotlib | Data visualization |
| Streamlit | Web application |

## 📊 Dataset

The project uses a healthcare stroke prediction dataset containing patient health and lifestyle information.

### Main Features

- Age
- Gender
- Hypertension
- Heart disease
- Average glucose level
- BMI
- Smoking status
- Residence type
- Work type

## ⚙️ Machine Learning Workflow

1. Load the dataset.
2. Perform data preprocessing and cleaning.
3. Handle missing values.
4. Encode categorical features.
5. Split data into training and testing sets.
6. Train the Machine Learning model.
7. Predict stroke risk based on user inputs.
8. Display results through an interactive dashboard.

## 📂 Project Structure

```text
stroke_prediction_ml/
│
├── dataset/
├── models/
├── app.py
├── main.py
├── heart_model.py
├── streamlit_app.py
├── requirements.txt
└── README.md
```

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/pokalasrilakshmi/Stroke_prediction_ML.git
```

### 2. Navigate to the project directory

```bash
cd Stroke_prediction_ML
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run stroke_prediction_ml/streamlit_app.py
```

## 🌐 Deployment

The application is deployed using Streamlit Community Cloud.

**Live Demo:** https://stroke-prediction-ai.streamlit.app/

## 🎯 Project Goal

The goal is to demonstrate how Machine Learning can be applied to healthcare data to estimate stroke risk and support awareness of preventive healthcare.

## ⚠️ Disclaimer

This project is developed for educational and demonstration purposes only. Its predictions are not medical diagnoses and should not replace professional medical advice or clinical evaluation.

## 📌 Conclusion

This project demonstrates an end-to-end Machine Learning application, covering data preprocessing, model development, prediction, visualization, and deployment through an interactive web dashboard.