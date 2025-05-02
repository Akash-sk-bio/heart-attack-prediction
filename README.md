
# 🫀 Heart Attack Prediction With 91.8% Accuracy

This project builds a machine learning model that predicts the likelihood of a heart attack based on patient data. The Support Vector Machine (SVM) model achieves up to **91.8% accuracy**, demonstrating strong potential in aiding early detection and prevention.

---

## 📊 Dataset Overview

The dataset used includes various health-related attributes:

| Feature     | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `age`       | Age of the patient                                                          |
| `sex`       | Sex (1 = male, 0 = female)                                                  |
| `cp`        | Chest pain type (0 to 3)                                                    |
| `trtbps`    | Resting blood pressure (mm Hg)                                              |
| `chol`      | Serum cholesterol in mg/dl                                                  |
| `fbs`       | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)                       |
| `restecg`   | Resting electrocardiographic results (0 to 2)                               |
| `thalachh`  | Maximum heart rate achieved                                                 |
| `exng`      | Exercise-induced angina (1 = yes; 0 = no)                                   |
| `oldpeak`   | ST depression induced by exercise                                           |
| `slp`       | Slope of the peak exercise ST segment                                       |
| `caa`       | Number of major vessels colored by fluoroscopy (0–3)                        |
| `thall`     | Thalassemia test result (0 to 3)                                            |
| `output`    | Heart disease presence (1 = yes, 0 = no)                                    |

---

## 🧪 Project Workflow

- ✅ **Data Cleaning** (null check, duplicate removal)
- 📈 **Exploratory Data Analysis**:
  - Count plots, distributions, correlation matrix
  - Violin plots and pair plots for visual insights
- 🔄 **Preprocessing**:
  - Feature scaling with `StandardScaler`
  - No need for label encoding (already numerical)
- 🤖 **Model Training & Testing**:
  - Logistic Regression
  - Gaussian & Bernoulli Naive Bayes
  - **Support Vector Machine (achieved 91.8% accuracy)**
  - Random Forest Classifier
  - K-Nearest Neighbors (optimized with best k)
  - XGBoost Classifier

---

## 🏆 Results

- The best-performing model is **Support Vector Machine (SVM)** with **91.8% accuracy**
- Confusion matrix analysis showed low false-positive/false-negative rates

---

## 🧰 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Project Structure

```
heart-attack-prediction/
│
├── heartattack-prediction-with-91-8-accuracy.ipynb   # Main notebook
├── data/
│   └── heart.csv                                      # Dataset
├── requirements.txt                                   # Python libraries
└── README.md                                          # Project info
```

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/heart-attack-prediction.git
   cd heart-attack-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📌 Future Improvements

- Deploy as a web app using Streamlit or Flask
- Add model explainability with SHAP/LIME
- Use real-time input forms for live predictions
