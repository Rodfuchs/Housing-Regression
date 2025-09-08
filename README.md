# 🏠 House Pricing Regression

Predict house prices using a **machine learning pipeline** with the Ames Housing dataset.

---

## 🚀 Features

- Handles missing values and cleans data
- Encodes categorical variables:
  - Ordinal for ordered categories
  - Target encoding for high-cardinality variables
- Scales numerical features
- Selects top 30 features with **RFE**
- Model: **XGBoost Regressor** with **GridSearchCV**
- Evaluates with **MAE, RMSE, MAPE, R²**

---

## 📂 Repo Structure

house-pricing-regression/
│
├── notebooks/ # Notebook with full exploration
├── src/ # Scripts for preprocessing, training, evaluation
├── requirements.txt # Dependencies
└── README.md


---

## 💻 Quick Start

1️⃣ Clone the repo:


git clone https://github.com/YOUR_USERNAME/house-pricing-regression.git
cd house-pricing-regression

2️⃣(Optional) Create a virtual environment:

python -m venv venv
-Activate Linux/Mac
source venv/bin/activate

-Activate Windows
venv\Scripts\activate

3️⃣ Install dependencies:

pip install -r requirements.txt

4️⃣ Run notebook for exploration:

jupyter notebook notebooks/house-pricing.ipynb


5️⃣ Train and evaluate via scripts:

python src/train.py
python src/evaluate.py
⚡ Example Results
yaml
Copy code
Train metrics:
MAE: 15000 | RMSE: 22000 | MAPE: 7.5% | R²: 0.95

Test metrics:
MAE: 18000 | RMSE: 25000 | MAPE: 9.2% | R²: 0.88
Metrics may vary depending on execution.

🛠️ Libraries
Python, Pandas, Scikit-learn, XGBoost, Category Encoders
