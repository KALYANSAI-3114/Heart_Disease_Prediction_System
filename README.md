# Heart Disease Prediction

A machine learning project that predicts the presence of heart disease using logistic regression, achieving **88.20% accuracy**.

## 📋 Project Overview

This project was developed as part of a Kaggle competition focused on predicting heart disease. The model analyzes various medical attributes to determine the likelihood of heart disease in patients, providing a valuable tool for early detection and intervention.

## 🎯 Objective

The primary goal is to build a classification model that can accurately predict whether a patient has heart disease based on clinical parameters such as age, sex, cholesterol levels, blood pressure, and other relevant medical indicators.

## 📊 Dataset

**Dataset Link:** [https://www.kaggle.com/competitions/playground-series-s6e2/data]

The dataset contains various medical attributes including:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia
- Target variable (presence of heart disease)

## 🔧 Technologies Used

- **Python 3.x**
- **Libraries:**
  - pandas - Data manipulation and analysis
  - numpy - Numerical computing
  - scikit-learn - Machine learning implementation
  - matplotlib - Data visualization
  - seaborn - Statistical data visualization

## 🚀 Model Performance

- **Algorithm:** Logistic Regression
- **Accuracy:** 88.20%

## 💻 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/KALYANSAI-3114/Heart_Disease_Prediction_System.git
cd Heart-Disease-Prediction_System
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 🔍 Usage

```python
Run all the cells 
```

## 📈 Methodology

1. **Data Loading & Exploration**
   - Load the dataset
   - Explore data structure and statistics
   - Check for missing values

2. **Data Preprocessing**
   - Handle missing values (if any)
   - Encode categorical variables
   - Feature scaling/normalization
   - Split data into training and testing sets

3. **Model Training**
   - Train Logistic Regression model
   - Hyperparameter tuning (if applicable)

4. **Model Evaluation**
   - Calculate accuracy score
   - Generate confusion matrix
   - Compute precision, recall, and F1-score
   - ROC-AUC curve analysis

## 📊 Results

The Logistic Regression model achieved an accuracy of **88.20%** on the test dataset, demonstrating strong predictive performance for heart disease classification.

### Performance Metrics:
- **Accuracy:** 88.20%
- 
## 🔮 Future Improvements

- Experiment with other algorithms (Random Forest, SVM, Neural Networks)
- Perform feature engineering to create new predictive features
- Implement ensemble methods for improved accuracy
- Conduct more extensive hyperparameter tuning
- Develop a web application for real-time predictions

## 👨‍💻 Author

[Kalyan Sai Atchi]
- GitHub: [KALYANSAI-3114](https://github.com/KALYANSAI-3114)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/kalyan-sai-atchi-45539926a/)
- Kaggle: [Kaggle Profile](https://www.kaggle.com/akalyansai)


⭐ If you found this project helpful, please consider giving it a star!
