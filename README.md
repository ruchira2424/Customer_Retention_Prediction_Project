# Customer Churn Prediction using Machine Learning 📊

This project is a **machine learning model to predict customer churn** using telecom data.  
Churn prediction helps businesses identify customers likely to leave and take proactive steps to improve retention.

---

## 🚀 Project Overview
- **Goal**: Predict whether a customer will churn (leave) or stay.
- **Dataset**: `churn-bigml-80.csv` (training) and `churn-bigml-20.csv` (testing).
- **Tech Stack**: Python, Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn (if used).
- **Steps in the Notebook**:
  1. Import necessary libraries.
  2. Load training & testing datasets.
  3. Data preprocessing:
     - Dropping irrelevant columns (`State`, `Area code`).
     - Handling categorical variables.
     - Encoding labels.
     - Scaling features if required.
  4. Model building using classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, etc.).
  5. Model evaluation using metrics such as Accuracy, Precision, Recall, and F1-score.
  6. Test set predictions.

---

## 📂 Project Structure
📦 Customer-Churn-Prediction
┣ 📜 Task10.ipynb # Main Jupyter Notebook
┣ 📜 churn-bigml-80.csv # Training dataset
┣ 📜 churn-bigml-20.csv # Testing dataset
┗ 📜 README.md # Documentation


---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
  git clone https://github.com/ruchira2424/customer-churn-prediction.git
cd customer-churn-prediction

