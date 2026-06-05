# Titanic Survival Predictor

## About
A machine learning web app that predicts whether a Titanic passenger survived or not.

## Technologies Used
- Python
- XGBoost
- Scikit-learn
- Streamlit
- Pandas, NumPy

## Steps Followed
- EDA + Visualization
- Missing Value Handling
- Feature Engineering (Title, Family Size, Is Alone)
- One Hot Encoding
- Train Test Split
- StandardScaler
- Logistic Regression, Random Forest, XGBoost

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 79% |
| Random Forest | 77.8% |
| XGBoost | 80.1% |

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
```