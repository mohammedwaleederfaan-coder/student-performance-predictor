# 🎓 Student Performance Predictor

A Machine Learning project that predicts student exam scores using both Classical ML and Deep Learning approaches.

---

## 📊 Dataset
- **File:** `student_dataset_10000_rows.csv`
- **Rows:** 10,000 students
- **Target:** `exam_score`

---

## 🏗️ Project Structure

student-performance-predictor/

├── main.py                  ← Full pipeline
├── best_model.pkl           ← Best Classical ML model
├── dl_model.pth             ← Deep Learning model
├── scaler.pkl               ← Fitted scaler
├── student_dataset_10000_rows.csv
└── README.md

---

## ⚙️ Models Used

### Classical ML
| Model | Type |
|---|---|
| DummyRegressor | Baseline |
| LinearRegression | Simple |
| RandomForestRegressor | Ensemble |
| XGBRegressor | Boosting |
| LGBMRegressor | Boosting |

### Deep Learning
Input → 64 → 32 → 16 → 1
ReLU + Dropout + AdamW + Early Stopping

---

## 📈 Evaluation Metrics
- R² Score
- MSE
- RMSE  
- MAE
- Residual Analysis
- Loss Curve

---

## 🚀 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/mohammedwaleederfaan-coder/student-performance-predictor.git
cd student-performance-predictor
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Run
```bash
python main.py
```

---

## 📦 2
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
torch
joblib

---

## 👤 Author
**Mohammed Waleed**
[GitHub](https://github.com/mohammedwaleederfaan-coder)
[Linkedin](https://www.linkedin.com/in/mohammed-waleed-0065b9409/)
