# Rainfall Prediction in Australia

## 📌 Project Overview
This project predicts whether it will rain **tomorrow** based on historical weather data from Australian weather stations. It is a **binary classification** problem.

## 🎯 Business Value
Predicting rainfall accurately helps farmers plan irrigation, transport companies avoid delays, and event organizers make better decisions.

## 📊 Dataset
- **Source:** Australian weather data (public dataset)
- **Time period:** ~10 years of daily observations
- **Key features:** Temperature, humidity, pressure, wind speed, sunshine hours, evaporation, cloud cover

## ⚙️ Tech Stack
| Category | Tools |
|----------|-------|
| Language | Python 3.11 |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |

## 🧠 Machine Learning Workflow
1. **Data Cleaning** – Handled missing values, removed irrelevant columns
2. **EDA (Exploratory Data Analysis)** – Visualized feature distributions and correlations
3. **Feature Engineering** – Encoded categorical variables, scaled numerical features
4. **Model Training** – Tested multiple classification algorithms
5. **Evaluation** – Compared models using accuracy, precision, recall, F1-score

## 📈 Models Tested & Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~85% |
| Random Forest | ~85% |
| XGBoost | ~85% |

> 📌 *Note: Detailed metrics and confusion matrices are available in the notebook.*

## 🚀 How to Run Locally
```bash
# 1. Clone the repository
git clone https://github.com/Mohamed-AboArab/Rainfall-Prediction-Australia.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook rainfall_prediction.ipynb
📁 Repository Files
File	Description
rainfall_prediction.ipynb	Main analysis and modeling notebook
requirements.txt	All Python dependencies
firstpython.py	Utility helper script
.githubignore	Git ignore rules
📌 What I Learned / Improved
Building a complete ML pipeline from data cleaning to evaluation

Using GridSearchCV for hyperparameter tuning

Interpreting classification metrics beyond just accuracy

👨‍💻 Author
Mohamed AboArab
Junior Data Scientist & AI Engineer
GitHub | LinkedIn
