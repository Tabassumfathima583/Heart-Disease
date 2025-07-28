# ❤️ Heart Disease Statistical Analysis

A complete exploratory and predictive analysis using **statistical tests** and **logistic regression** to detect heart disease risk. This project uses Python and core statistical concepts to extract meaningful healthcare insights.

---

## 📘 Overview

**Objective**: Use a statistician’s lens to explore relationships in the dataset, test medical hypotheses, and build an interpretable prediction model.

Key questions addressed:
- Do men have higher cholesterol levels than women?
- Is exercise-induced angina associated with heart disease?
- Which features contribute most to prediction?
- Can we accurately predict heart disease based on patient data?

---

## 📁 Dataset

- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Rows**: 303 records
- **Features**: 14 clinical attributes (e.g., age, cholesterol, chest pain, etc.)
- **Target**: `1` = presence of heart disease, `0` = absence

---

## 🛠 Tools & Libraries

| Category        | Stack Used                      |
|----------------|----------------------------------|
| Data Handling   | `pandas`, `numpy`                |
| Statistics      | `scipy.stats`                   |
| Modeling        | `scikit-learn` (LogisticRegression) |
| Visualization   | `matplotlib`, `seaborn`         |
| Notebook        | Jupyter Notebook                |

---

## 📊 Statistical & ML Analyses

- ✅ Descriptive statistics
- ✅ T-test (cholesterol by gender)
- ✅ Chi-square test (angina vs disease)
- ✅ Correlation matrix
- ✅ Logistic regression
- ✅ Model metrics: classification report, ROC-AUC
- ✅ Feature importance
- ✅ Predictive probability analysis by age

---

## 🖼️ Visualizations

### 🧪 Correlation Matrix
![Correlation Matrix](https://github.com/Tabassumfathima583/Heart-Disease/blob/main/Images/Correlation%20Matrix.png)
> `cp`, `thalach`, and `oldpeak` show strong correlation with the target.

---

### 📊 Feature Importance (Model Coefficients)
![Feature Importance](https://github.com/Tabassumfathima583/Heart-Disease/blob/main/Images/Feature%20Importance.png)
> Chest pain, max heart rate, and ST depression were top predictive features.

---

### 🧠 Predicted Probability vs Age
![Age vs Predicted Probability](https://github.com/Tabassumfathima583/Heart-Disease/blob/main/Images/Age%20vs%20Predicted%20probability%20of%20heart%20disease.png)
> Probability of heart disease increases significantly with age (especially over 50).

---

### 📉 Confusion Matrix
![Confusion Matrix](https://github.com/Tabassumfathima583/Heart-Disease/blob/main/Images/Confusion%20Matrix.png)
> The model performs well on both classes, with high true positives.

---

## 📈 Model Performance

| Metric           | Score   |
|------------------|---------|
| **Accuracy**     | 81%     |
| **Recall (1)**   | 92%     |
| **Precision (0)**| 90%     |
| **ROC-AUC**      | **0.93** ✅ |

> 💡 The model prioritizes correctly identifying heart disease (high recall), which is crucial in medical settings.

---

## 🧠 Key Insights

- Males and females showed no significant cholesterol difference (p > 0.05)
- Angina is statistically linked to heart disease (chi-square p < 0.01)
- Logistic regression performs well with few assumptions
- Interpretability is maintained without sacrificing performance

---

## 💼 Project Skills Demonstrated

- Hypothesis-driven statistical thinking
- End-to-end pipeline: data cleaning → testing → modeling → visualization
- Professional documentation for stakeholders or recruiters
- Deployment-ready code for health data analytics

---

## 🚀 How to Run

```bash
git clone https://github.com/Tabassumfathima583/Heart-Disease.git
cd Heart-Disease
pip install -r requirements.txt
jupyter notebook
