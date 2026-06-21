# 🛡️ Insurance Purchase Prediction using Logistic Regression

## 📌 Overview
This project applies **Logistic Regression** to predict whether a customer will purchase insurance based solely on their **age**.  
It demonstrates classification modeling, probability curve visualization, evaluation metrics, and interactive prediction.

---

## 🎯 Problem Statement
Insurance companies often need to identify potential customers who are likely to purchase policies.  
The goal of this project is to build a simple classification model that predicts whether a customer will buy insurance, helping optimize marketing and sales strategies.

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, scikit‑learn, Matplotlib  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset
The dataset (`data-insurance.csv`) contains:
- `age` → Age of the customer  
- `bought_insurance` → Target variable (1 = purchased, 0 = not purchased)  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Insurance-Prediction.git
2. Navigate to the folder:

bash
cd Insurance-Prediction
Install dependencies:

bash
pip install -r requirements.txt
Open the notebook:

bash
jupyter notebook InsurancePrediction.ipynb
Run cells step by step:

3. Import libraries

4.Load dataset

5. Train logistic regression model using age

6. Print test data, predictions, and accuracy score

7. Visualize logistic curve (probability vs. age)

8. Enter age → get prediction (Yes/No for insurance purchase)

## 📊 Results
Accuracy: ~85% (varies depending on train/test split)
Example Prediction:

Enter age: 45
✅ At age 45, customer is likely to buy insurance.
Logistic Curve: Blue scatter points show actual data, red curve shows predicted probability of purchase vs. age.

## 🎯 Key Learnings

Understanding classification vs. regression.
Applying Logistic Regression to a simple binary classification problem.
Evaluating models using accuracy.
Visualizing probability curves.
Building an interactive ML pipeline with user input.

## 📎 Future Scope
Add more features (BMI, smoker status, region, etc.).

Evaluate with confusion matrix and classification report.

Try advanced models (Random Forest, XGBoost).

Deploy as a web app for insurance agents to use interactively.

## 👤 Author
Sagar Joshi  
B.Tech CSE (AI & ML)
📧 Email: sj471846@gmail.com
🔗 LinkedIn: [(www.linkedin.com/in/sagar-joshi-775b15343)]
