# Customer Churn Prediction

This project presents a machine learning approach to predict **customer churn** using multiple classification models including Random Forest, Support Vector Machine (SVM), Gradient Boosting, and also a regression-based analysis using Linear Regression for exploratory insight.

The objective is to identify customers who are likely to leave a bank based on various attributes, which can help the business improve customer retention strategies.

---

## 📊 Dataset

The dataset (`cust_churn_data.csv`) includes customer-level information such as:

- Credit Score
- Geography (France, Germany, Spain)
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Credit Card Ownership
- Active Membership Status
- Estimated Salary
- Churn Label (`Exited`)

---

## 🔄 Workflow

### 🧹 1. Data Preprocessing
- Handled missing and duplicate records
- Encoded categorical variables using:
  - `LabelEncoder` for binary categories
  - One-Hot Encoding for multi-class categories
- Feature scaling using `StandardScaler`

### 📊 2. Feature Selection
- Selected relevant features based on business and model relevance

### 🤖 3. Model Building
Built and evaluated the following models:

- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **Gradient Boosting Classifier**
- **Linear Regression** (for exploratory trend analysis)

Each model was trained using a train-test split (80-20) and evaluated using standard metrics.

### 📈 4. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- Visual performance comparison (bar plots or heatmaps if applicable)

---

## 🛠️ Tech Stack

- **Languages & Tools**: Python, Jupyter Notebook
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (`RandomForestClassifier`, `SVC`, `GradientBoostingClassifier`, `LinearRegression`, etc.)

---
