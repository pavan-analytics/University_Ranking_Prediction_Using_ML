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

- **Source:** [Kaggle - CWUR University Rankings Dataset](https://www.kaggle.com/datasets/saurabhshahane/university-ranking-by-cwur)
- Description: Includes features such as `institution`, `country`, `broad_impact`, and others relevant to academic ranking.

The dataset includes performance metrics of global universities. This project draws inspiration and structure from the reference notebook.

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

2. Install dependencies:
   ```bash
pip install -r requirements.txt

3. Run the Jupyter Notebook or Python script:
   ```bash
jupyter notebook University_Ranking_Prediction.ipynb


🚀 Future Enhancements
📊 Feature Engineering:
Explore and create additional features from raw data (e.g., student-faculty ratio, research score per capita) to improve model accuracy.

🔍 Hyperparameter Tuning:
Use Grid Search or Randomized Search CV to fine-tune the hyperparameters of models like XGBoost and Random Forest for optimal performance.

📈 Advanced Models:
Experiment with advanced machine learning algorithms such as:

LightGBM

CatBoost

Neural Networks (e.g., MLPRegressor, TensorFlow/Keras models)

📤 Web Application Deployment:
Build a web app (e.g., using Streamlit or Flask) where users can input university features and get predicted global rankings instantly.

📂 Real-Time Data Integration:
Integrate live university datasets from APIs or web scraping to keep the prediction system up to date.

📁 Clustering & Classification:
Use unsupervised learning (e.g., K-Means) to group similar universities and help in segment analysis or categorization.

🌐 Multi-year Trend Prediction:
Expand the model to predict future ranking trends by training on historical ranking data across multiple years.

📊 Interactive Dashboards:
Use tools like Power BI or Tableau to create visual dashboards showing trends, insights, and predictions.
