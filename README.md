# 🎮 PUBG Win Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analyzing PUBG (PlayerUnknown's Battlegrounds) gameplay data and developing Machine Learning models to predict a player's final match placement (`winPlacePerc`). The project also identifies the important gameplay factors that influence winning performance.

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA) on PUBG gameplay data.
- Clean and preprocess the dataset.
- Identify important features affecting player performance.
- Build Machine Learning models to predict win placement.
- Compare different models using evaluation metrics.
- Identify the best-performing model for prediction.

## 📊 Dataset Description

The dataset contains PUBG player and match statistics, including:

- Player kills and assists
- Damage dealt
- Survival time
- Distance travelled
- Weapons acquired
- Healing and boost items used
- Match type
- Final win placement (`winPlacePerc`)

**Target Variable:** `winPlacePerc`

## 🛠️ Technologies & Tools Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Jupyter Notebook |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Prediction Models | Linear Regression, Decision Tree, Random Forest, Gradient Boosting |
| Model Evaluation | MAE, MSE, RMSE, R² Score |
| Model Saving | Pickle (PKL) |

## ⚙️ Project Workflow

1. **Data Loading:** Import the PUBG dataset into Jupyter Notebook.
2. **Data Cleaning:** Handle missing values and duplicate records.
3. **Exploratory Data Analysis:** Analyze gameplay statistics and identify patterns.
4. **Feature Engineering:** Remove unnecessary columns such as `Id`, `groupId`, and `matchId`, and encode categorical variables using One-Hot Encoding.
5. **Data Splitting:** Split the dataset into training and testing sets (80:20).
6. **Model Building:** Train multiple Machine Learning regression models.
7. **Model Evaluation:** Compare model performance using MAE, MSE, RMSE, and R² Score.
8. **Prediction:** Predict the final player placement and examine winning probability where applicable.
9. **Model Saving:** Save the trained model as a `.pkl` file using Pickle.

## 🤖 Machine Learning Algorithms Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

The models are compared to identify the most suitable model based on prediction performance.

## 📈 Model Evaluation Metrics

- **MAE:** Measures the average absolute prediction error.
- **MSE:** Measures the average squared prediction error.
- **RMSE:** Measures prediction error in the original target scale.
- **R² Score:** Measures how well the model explains variations in the target variable.

## 📂 Project Structure

```text
PUBG-Win-Prediction/
│
├── PUBG_Win_Prediction.ipynb
├── model.pkl
├── README.md
├── requirements.txt
└── .gitignore
```

## 💻 Installation & Usage

**Step 1: Clone the repository**

```bash
git clone https://github.com/USERNAME/PUBG-Win-Prediction.git
```

**Step 2: Navigate to the project folder**

```bash
cd PUBG-Win-Prediction
```

**Step 3: Install required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

Open `PUBG_Win_Prediction.ipynb` and execute the cells in sequence.

## 🏆 Key Outcomes

- Analyzed PUBG gameplay data to understand player performance.
- Identified gameplay features influencing final match placement.
- Developed and evaluated multiple Machine Learning models.
- Compared model performance to identify the best-performing algorithm.
- Generated predicted win-placement values.

## 🔮 Future Enhancements

- Develop a web application for real-time predictions.
- Improve model performance through hyperparameter tuning.
- Add interactive visualizations.
- Deploy the trained model using Flask or Streamlit.

## 👨‍💻 Author

**Naveen Gnanavel**

B.Tech – Artificial Intelligence and Data Science

GitHub: https://github.com/Naveen0625
