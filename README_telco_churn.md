# 📉 Telco Customer Churn Prediction

Predict whether a telecom customer will churn using machine learning — built with real-world IBM Telco dataset, covering full EDA, feature engineering, model comparison, and retention strategy insights.

---

## 👩‍💻 Author

| | |
|---|---|
| **Name** | Anushree R |
| **Email** | anushreerpoojary2611@gmail.com |
| **GitHub** | [github.com/AnushreeRPoojary](https://github.com/AnushreeRPoojary) |

---

## 📌 Problem Statement

Customer churn is one of the biggest challenges in the telecom industry. This project builds a machine learning pipeline to:
- Identify customers likely to churn
- Understand key factors driving churn
- Provide actionable retention strategy insights

---

## 📂 Dataset

**IBM Telco Customer Churn Dataset**
- 📁 File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- 👥 7,043 customers
- 📊 21 features (demographics, services, charges, contract)
- 🎯 Target: `Churn` (Yes / No)

> Download from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) or load directly via URL in the notebook.

---

## 🔬 Project Workflow

```
📥 Load Data
    ↓
🔍 Exploratory Data Analysis (EDA)
    ↓
🛠️ Feature Engineering
    ↓
⚖️ Handle Class Imbalance (SMOTE)
    ↓
🤖 Train 9 ML Models
    ↓
📊 Compare & Evaluate Models
    ↓
🏆 Best Model Selection
    ↓
💡 Retention Strategy Insights
    ↓
📤 Export Predictions CSV
```

---

## 📊 Models Used

| Model | Type |
|---|---|
| Logistic Regression | Linear |
| Decision Tree | Tree-based |
| Random Forest | Ensemble |
| Extra Trees | Ensemble |
| Gradient Boosting | Boosting |
| AdaBoost | Boosting |
| XGBoost | Boosting |
| KNN | Instance-based |
| SVM | Kernel-based |

---

## 📈 Key Visualizations

| Plot | Description |
|---|---|
| `01_eda_dashboard.png` | Churn by contract, tenure, internet, payment |
| `02_charges_senior_gender.png` | Monthly charges & demographic analysis |
| `03_correlation_heatmap.png` | Feature correlation matrix |
| `04_model_comparison.png` | All 9 models — accuracy, F1, AUC-ROC |
| `05_roc_curves.png` | ROC curves for all models |
| `06_feature_importance.png` | Top features driving churn |
| `07_retention_insights.png` | Business strategy visualizations |

---

## 🗂️ Project Structure

```
telco-churn-prediction/
├── telco_churn_prediction.ipynb     ← main notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  ← dataset
├── *.png   /outputs                         ← saved visualizations
├──  csv/xls
|── README.md
```

---

## ⚙️ Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

---

## 🚀 How to Run

### Jupyter Notebook
```bash
jupyter notebook telco_churn_prediction.ipynb
```

### VS Code
1. Open `telco_churn_prediction.ipynb`
2. Place CSV in same folder
3. Click **Run All** ▶▶

### Google Colab
```python
# Replace CSV load line with:
url = 'https://raw.githubusercontent.com/dsrscientist/dataset1/master/Telco-Customer-Churn.csv'
df = pd.read_csv(url)
```

---

## 💡 Key Findings

- **Month-to-month contracts** have highest churn rate (~45%)
- **Fiber optic internet** customers churn more than DSL
- **Short tenure customers** (< 12 months) are high risk
- **Electronic check** payment method linked to higher churn
- **Senior citizens** have higher churn probability

---

## 📤 Output

- Model comparison table with Accuracy, Precision, Recall, F1, AUC-ROC
- Best model selected automatically
- `churn_predictions.csv` — test set with actual vs predicted churn

---

## 📄 License

MIT License — free to use and modify.




*Built by Anushree R — AI & ML Engineer*  
*B.E. Artificial Intelligence & Machine Learning, SMVITM Udupi*