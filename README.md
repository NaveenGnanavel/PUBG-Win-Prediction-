# PUBG Win Prediction Using Machine Learning

## 1. Project Overview

The **PUBG Win Prediction** project focuses on analyzing player gameplay statistics and developing Machine Learning models to predict final match placement. The primary objective is to identify the key factors influencing player performance and estimate the probability of achieving better match outcomes.

This project involves data preprocessing, Exploratory Data Analysis (EDA), feature engineering, model development, performance evaluation, and prediction analysis using Python.

## 2. Project Objectives

- Perform comprehensive Exploratory Data Analysis on PUBG gameplay data.
- Identify important gameplay factors affecting player performance.
- Clean and preprocess the dataset for Machine Learning.
- Develop multiple predictive models.
- Compare model performance using evaluation metrics.
- Select the best-performing model for prediction.
- Save the trained model for future use.

## 3. Technologies and Tools Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Jupyter Notebook |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Algorithms | Linear Regression, Decision Tree, Random Forest, Gradient Boosting |
| Model Serialization | Pickle |
| Version Control | Git and GitHub |
| Large File Storage | Git LFS |

## 4. Dataset Description

The dataset contains PUBG player-level gameplay statistics and match information.

Important features include:

- Kills and assists
- Damage dealt
- Survival time
- Distance travelled
- Weapons acquired
- Healing and boost items used
- Match type
- Final placement percentage

**Target Variable:** `winPlacePerc`

The target variable represents the player's final placement percentage in a match.

## 5. Project Workflow

### Data Preprocessing
- Loaded and inspected the dataset.
- Identified missing values and duplicate records.
- Handled missing values using appropriate techniques.
- Removed unnecessary identifier columns.
- Converted categorical variables using One-Hot Encoding.

### Exploratory Data Analysis
- Analyzed player gameplay statistics.
- Studied relationships between gameplay features and winning performance.
- Identified important patterns and correlations.
- Visualized feature distributions and relationships.

### Model Development
Developed and evaluated multiple Machine Learning regression algorithms:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

### Model Evaluation

The following evaluation metrics were used:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

The models were compared to identify the most suitable algorithm based on predictive performance.

## 6. Project Files

| File Name | Description |
|---|---|
| `Pubg Win Prediction.ipynb` | Complete project implementation, EDA, preprocessing, model training and evaluation |
| `pubg_win_prediction_model.pkl` | Serialized trained Machine Learning model |
| `PUBG_Model_Comparison.csv` | Performance comparison of different Machine Learning models |
| `PUBG_Prediction_Results.csv` | Actual and predicted win placement results |
| `PUBG_Feature_Importance.csv` | Feature importance analysis |
| `README.md` | Project documentation |
| `requirements.txt` | Required Python libraries |
| `.gitattributes` | Git LFS configuration for large files |

## 7. Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/NaveenGnanavel/PUBG-Win-Prediction-.git
```

### Step 2: Navigate to the Project Directory

```bash
cd PUBG-Win-Prediction-
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Download the Git LFS Model

```bash
git lfs pull
```

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Pubg Win Prediction.ipynb` and execute the cells sequentially.

## 8. Key Outcomes

- Performed data analysis to understand PUBG player performance.
- Identified gameplay patterns associated with match placement.
- Developed multiple Machine Learning regression models.
- Evaluated and compared model performance using standard metrics.
- Generated predicted placement results.
- Saved the trained model in Pickle format for reuse.

## 9. Future Enhancements

- Improve prediction accuracy through hyperparameter optimization.
- Develop an interactive prediction dashboard.
- Deploy the trained model using Flask or Streamlit.
- Explore additional Machine Learning and ensemble techniques.
- Integrate real-time gameplay statistics for prediction.

## 10. Author

**Naveen Gnanavel**

B.Tech – Artificial Intelligence and Data Science

GitHub: https://github.com/NaveenGnanavel

## 11. Conclusion

This project demonstrates the application of Data Analysis and Machine Learning techniques to PUBG gameplay data. By performing data preprocessing, exploratory analysis, model development, and evaluation, the project aims to predict player match placement and identify the gameplay factors that contribute to winning performance.

---

**Technologies:** Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Jupyter Notebook | Git | GitHub

⭐ Thank you for visiting this repository!
