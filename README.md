# 🏥 Medical Insurance Cost Prediction using Machine Learning

This project aims to predict **medical insurance costs** using multiple machine learning models. The pipeline includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation based on common regression metrics like MAE, MSE, and R² Score.

---

## 📁 Dataset

- **File**: `insurance.csv`
- **Features**:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`
- **Target**:
  - `charges` (Medical Insurance Cost)

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values and data types
- Visualized correlations using heatmaps
- Plotted distributions for `charges`, `age`, and `bmi`
- Analyzed categorical impacts like `smoker` and `region` on `charges`

---

## ⚙️ Data Preprocessing

- Handled categorical variables using **Label Encoding**
- Feature scaling applied using **StandardScaler**
- Train-test split applied to prepare data for modeling

---

## 🤖 Machine Learning Models Used

1. **Linear Regression**
2. **Support Vector Regressor (SVR)**
3. **Random Forest Regressor**

---

## 🧪 Evaluation Metrics

| Model                    | MAE     | MSE         | R² Score        |
|-------------------------|---------|-------------|-----------------|
| Linear Regression        | 4063.08 | 35,229,015  | 0.681           |
| Random Forest Regressor | 2637.43 | 22,806,341  | 0.848           |
| Support Vector Regressor| 6930.46 | 191,975,722 | -12.40 ❌       |

✅ **Random Forest Regressor** performed the best among all models.

---

## 📊 Visualizations

- Heatmap of feature correlation
- Count plots for categorical features
- Regression plots for prediction vs. actual values
- Residual distribution plots

---

## 📌 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 How to Run

```bash
git clone https://github.com/BrijeshRakhasiya/Medical-Insurance-Cost-Prediction.git
cd medical-insurance-cost-ml
```

## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**

