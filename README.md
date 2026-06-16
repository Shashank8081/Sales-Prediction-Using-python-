# 📊 Sales Prediction Using Python

Predicting product sales using **Machine Learning** based on advertising expenditure across different media platforms such as **TV, Radio, and Newspaper**.

---

## 📌 Project Overview

Sales prediction is one of the most important applications of Machine Learning in business analytics. Companies invest heavily in advertising through various channels, and predicting future sales helps them make informed marketing decisions.

In this project, a **Linear Regression** model is built to predict product sales using advertising budgets. The project also includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and future sales prediction.

---

## 🎯 Project Objectives

- Analyze advertising data
- Perform Exploratory Data Analysis (EDA)
- Understand relationships between advertising channels and sales
- Build a Machine Learning model using Linear Regression
- Evaluate model performance using regression metrics
- Predict future sales based on advertising budget

---

## 📂 Dataset Information

The dataset contains advertising expenditure on different platforms and corresponding sales.

### Features

| Feature | Description |
|----------|-------------|
| TV | TV advertising budget |
| Radio | Radio advertising budget |
| Newspaper | Newspaper advertising budget |
| Sales | Product sales (Target Variable) |

- Number of Records: **200**
- Number of Features: **4**

---

## 🛠 Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📁 Project Structure

```
Sales-Prediction-Using-Python/
│
├── Advertising.csv
├── Sales_Prediction_Using_Python.ipynb
├── sales_prediction_model.pkl
├── requirements.txt
├── README.md
│
├── images/
│   ├── heatmap.png
│   ├── pairplot.png
│   ├── sales_distribution.png
│   ├── actual_vs_predicted.png
│   ├── residual_plot.png
│   └── feature_importance.png
│
└── LICENSE
```

---

## 📊 Exploratory Data Analysis (EDA)

The following analysis was performed:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Duplicate Value Check
- Correlation Matrix
- Heatmap
- Pair Plot
- Sales Distribution
- Feature Importance Analysis

---

## 🤖 Machine Learning Model

### Algorithm Used

**Linear Regression**

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values by learning the relationship between independent variables and the target variable.

---

## 🔄 Project Workflow

```
Dataset Collection
        │
        ▼
Load Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split
        │
        ▼
Linear Regression Model
        │
        ▼
Model Training
        │
        ▼
Prediction
        │
        ▼
Model Evaluation
        │
        ▼
Future Sales Prediction
```

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Sample Results

| Metric | Value |
|---------|--------|
| MAE | 1.46 |
| MSE | 3.17 |
| RMSE | 1.78 |
| R² Score | 0.90 |

> **Note:** Results may vary depending on the train-test split and random state.

---

## 📉 Visualizations

The project includes several visualizations:

- Correlation Heatmap
- Pair Plot
- Sales Distribution Plot
- Actual vs Predicted Sales
- Residual Plot
- Feature Importance Bar Chart

---

## 💻 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Sales-Prediction-Using-Python.git
```

### Navigate to the Project Folder

```bash
cd Sales-Prediction-Using-Python
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the notebook using **Google Colab** or **Jupyter Notebook**.

Run all cells sequentially.

---

## 🔮 Example Prediction

### Input

```python
TV = 150
Radio = 25
Newspaper = 30
```

### Output

```
Predicted Sales = 16.78
```

---

## 📦 Save the Trained Model

```python
import joblib

joblib.dump(model, "sales_prediction_model.pkl")
```

Load the saved model:

```python
model = joblib.load("sales_prediction_model.pkl")
```

---

## 💡 Key Insights

- TV advertising has the highest impact on sales.
- Radio advertising also contributes positively.
- Newspaper advertising has relatively less influence.
- Linear Regression provides high prediction accuracy for this dataset.
- Businesses can use this model to optimize advertising budgets and improve decision-making.

---

## 🚀 Future Enhancements

- Random Forest Regressor
- Decision Tree Regressor
- XGBoost Regressor
- Hyperparameter Tuning
- Streamlit Web Application
- Flask API Deployment
- Interactive Dashboard
- Cloud Deployment (Render / Hugging Face)

---

## 📚 Learning Outcomes

After completing this project, I learned:

- Data preprocessing
- Data visualization
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature selection
- Regression algorithms
- Model evaluation techniques
- Machine Learning workflow
- Model saving and loading using Joblib

---

## 📸 Project Screenshots

Add screenshots of:

- Dataset Preview
- Correlation Heatmap
- Pair Plot
- Sales Distribution
- Actual vs Predicted Graph
- Feature Importance Graph

Example:

```
images/
├── heatmap.png
├── pairplot.png
├── prediction.png
```

---

## 📋 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👨‍💻 Author

**Shashank Singh Chauhan**

**Machine Learning | Data Science | Python**

Email: chauhanshashank8081@gmail.com

---

## ⭐ Show Your Support

If you found this project useful, please give it a ⭐ on GitHub.

It motivates me to build more Machine Learning and Data Science projects.

---

## 📜 License

This project is licensed under the **MIT License**.

Feel free to use this project for learning and educational purposes.
