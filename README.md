#  Health Status Prediction using Machine Learning

##  Project Overview

This project predicts an individual's health status using various Machine Learning classification algorithms. Multiple models were trained, evaluated, and compared to determine the best-performing classifier based on evaluation metrics.

The project follows a complete Machine Learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Model training
- Model evaluation
- Model comparison

---

##  Dataset

The dataset contains health-related attributes used to predict the health status of an individual.

Typical preprocessing steps include:

- Handling missing values
- Removing duplicates
- Feature selection
- Train-test splitting
- Feature scaling using StandardScaler

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- Voting Classifier
- Stacking Classifier

---

##  Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

A comparison table was created to compare the performance of all models.

---

##  Model Performance

| Model | Accuracy |
|--------|----------|
| Voting Classifier | **94.87%** |
| Stacking Classifier | 94.69% |
| Random Forest | 94.35% |
| Gradient Boosting | 93.33% |
| Support Vector Machine | 93.02% |
| K-Nearest Neighbors | 88.03% |
| Decision Tree | 83.07% |
| Logistic Regression | 81.29% |

**Best Performing Model:**  Voting Classifier

---

##  Project Structure

```
HealthStatusPrediction/
│
├── HealthStatusPrediction.ipynb
├── README.md
├── requirements.txt
└── dataset.csv
```

---

##  Installation

Clone the repository

```bash
https://github.com/Sujan-Adhikari875/Health-Status-Prediction.git
```

Move into the project folder

```bash
cd HealthStatusPrediction
```

Install the required libraries

```bash
pip install pandas numpy matplotlib Scikit-learn seaborn
```

Launch Jupyter Notebook

```bash
jupyter notebook or jupyter lab
```

---



The notebook includes:

- Data preprocessing
- Exploratory Data Analysis
- Model training
- Performance comparison table
- Confusion matrices

---

##  Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- ROC-AUC Curve
- Feature importance visualization
- Model deployment using Flask or Streamlit

---

##  Learning Outcomes

This project demonstrates:

- Data preprocessing techniques
- Classification algorithms
- Ensemble learning methods
- Performance evaluation
- Model comparison
- End-to-end Machine Learning workflow

---

##  Author

**Adhikari Sujan**

GitHub: https://github.com/Sujan-Adhikari875

---


