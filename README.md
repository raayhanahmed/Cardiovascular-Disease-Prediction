# Cardiovascular Disease Prediction

A machine learning mini project for predicting cardiovascular disease using patient health data.

##  Project Overview

This project uses machine learning techniques to analyze cardiovascular health data and predict the presence of cardiovascular disease.

The project follows a complete machine learning workflow:

* Data Loading & Understanding
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Train-Test Split
* Feature Scaling
* Model Implementation
* Model Evaluation
* Visualization & Reporting
* Feature Importance Analysis

##  Machine Learning Models

Two classification models are implemented:

### 1. Logistic Regression

Logistic Regression is used as a classification model for predicting cardiovascular disease.

### 2. Decision Tree

A Decision Tree Classifier is used with:

```python
max_depth=5
random_state=42
```

The maximum depth is limited to help reduce overfitting.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

##  Dataset

The project uses:

```text
cardio_data_processed.csv
```

The target variable is:

```text
cardio
```

The dataset is loaded into a Pandas DataFrame and basic information such as shape, data types, summary statistics, and missing values is analyzed.

##  Exploratory Data Analysis

The project performs the following EDA:

* Cardiovascular disease distribution
* Feature histograms
* Correlation heatmap
* Dataset shape analysis
* Data type analysis
* Summary statistics
* Missing value analysis

The target variable distribution is visualized using a count plot, while numerical relationships are explored using a correlation heatmap.

##  Data Preprocessing

The preprocessing steps include:

1. Removing the `id` column
2. Replacing `no` values with missing values
3. Converting selected columns to numeric values
4. Converting age from days to years
5. Handling missing values using median values
6. Encoding categorical variables
7. Separating features and target variable
8. Splitting the dataset into training and testing sets
9. Applying StandardScaler for feature scaling

The dataset is divided using an 80/20 train-test split with `random_state=42`.

##  Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

The project also generates confusion matrices and ROC curves for model evaluation.

##  Visualization

The project generates:

* Cardiovascular Disease Distribution
* Feature Histograms
* Correlation Heatmap
* Logistic Regression Confusion Matrix
* Decision Tree Confusion Matrix
* ROC Curve Comparison
* Decision Tree Feature Importance

The ROC curves of both models are plotted for comparison, and feature importance is visualized for the Decision Tree model.

##  How to Run

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd Cardiovascular-Disease-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Python Project

```bash
python final_project.py
```

##  Project Structure

```text
Cardiovascular-Disease-Prediction/
│
├── cardio_data_processed.csv
├── final_project.py
├── README.md
├── requirements.txt

```

##  Project Objective

The main objective of this project is to demonstrate how machine learning can be applied to cardiovascular health data through data analysis, preprocessing, classification, model evaluation, and visualization.

##  Author

** Md. Abu Rayhan Ahmed **

Department of Computer Science & Engineering  
Daffodil International University

---

⭐ If you find this project useful, feel free to star the repository.
