#  Weather Prediction Using Machine Learning

##  Project Overview

This project predicts whether it will rain tomorrow based on historical weather data using Machine Learning classification algorithms. Multiple models are trained, evaluated, and compared to identify the most effective approach for rainfall prediction.

The project includes data preprocessing, feature encoding, model training, performance evaluation, cross-validation, feature importance analysis, and final prediction generation.

---

##  Features

- Data cleaning and preprocessing
- Handling missing values
- Label encoding of categorical features
- Feature scaling using StandardScaler
- Training multiple Machine Learning models
- Performance comparison using various evaluation metrics
- Confusion Matrix visualization
- ROC Curve analysis
- Cross-validation performance analysis
- Feature importance visualization
- Rainfall prediction for new samples

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

##  Machine Learning Models Implemented

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Support Vector Machine (SVM)
5. Random Forest Classifier

---

##  Project Workflow

### 1. Data Preprocessing

- Load weather dataset
- Remove missing values
- Convert target variable (`RainTomorrow`) into numerical format
- Encode categorical features

### 2. Feature Engineering

- Separate features and target variable
- Split dataset into training and testing sets
- Standardize feature values

### 3. Model Training

Train the following classifiers:

- Logistic Regression
- KNN
- Decision Tree
- SVM
- Random Forest

### 4. Model Evaluation

Evaluate each model using:

- Accuracy
- Precision
- Recall
- Specificity
- F1 Score

### 5. Visualization

- Confusion Matrices
- ROC Curves
- Cross-Validation Accuracy Plots
- Feature Importance Analysis

### 6. Prediction

Generate rainfall predictions on unseen data samples.

---

##  Evaluation Metrics

The models are compared using:

- Accuracy
- Precision
- Recall
- Specificity
- F1 Score
- ROC-AUC Score

These metrics help determine the most reliable model for rainfall forecasting.

---

##  Project Structure

```text
Rainfall-Prediction-ML/
│
├── Machine_Learning_Project.ipynb
├── Dataset
├── README.md
└── requirements.txt
```

---

##  How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/rainfall-prediction-ml.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```text
Machine_Learning_Project.ipynb
```

and execute all cells.

---

##  Results

The project compares five popular machine learning algorithms for rainfall prediction. Performance is evaluated using multiple classification metrics and visualization techniques. Random Forest is used as the final model due to its strong predictive performance and ability to identify important weather features influencing rainfall.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Advanced feature engineering
- Deployment using Flask or Streamlit
- Real-time weather API integration
- Deep Learning-based rainfall prediction

---

##  Author

**Sravika**

B.Tech Computer Science Engineering Student

Interested in Artificial Intelligence, Machine Learning, Generative AI, and Full-Stack AI Development.
