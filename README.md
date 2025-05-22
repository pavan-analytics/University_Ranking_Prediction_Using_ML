# University_Ranking_Prediction_Using_ML

This project predicts global university rankings based on multiple performance parameters using machine learning models. The dataset is inspired by the **Quacquarelli Symonds (QS)** ranking framework.

---

## 📌 Objective

To predict the *world_rank* of universities by applying different regression models and evaluating their performance using metrics such as MAE, MSE, and RMSE.

---

## 🧠 Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 🗂️ Dataset

- Source: `https://www.kaggle.com/code/shubham8983/university-ranking-prediction`
- Description: Includes features such as `institution`, `country`, `broad_impact`, and others relevant to academic ranking.

---

## ⚙️ Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost

---

## 📊 Model Evaluation

| Model             | MAE       | MSE         | RMSE      |
|------------------|-----------|-------------|-----------|
| Linear Regression| 54.56     | 6612.63     | 81.32     |
| Random Forest     | 7.18      | 230.74      | 15.19     |
| XGBoost           | 7.84      | 187.12      | 13.68     |

---

## 📝 Observations

- **XGBoost** achieved the best performance with the lowest RMSE and MSE, making it the most suitable for this regression task.
- **Random Forest** performed well, slightly behind XGBoost.
- **Linear Regression** showed poor performance, indicating it was not able to capture the complex patterns in the data.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/pavan-analytics/university-ranking-prediction.git
