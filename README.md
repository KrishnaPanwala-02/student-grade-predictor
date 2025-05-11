#  Student Grade Predictor

This project predicts a student's final grade (`G3`) based on features such as:
- Study time
- Failures
- Absences
- First period grade (`G1`)
- Second period grade (`G2`)
- Other personal and academic attributes

## Features
- Linear Regression model
- Handles categorical and numerical features
- Preprocessing with scaling and encoding
- Cross-validation for model robustness
- Model saved using `joblib`

##  Dataset
The dataset used is the [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance) (`student-mat.csv`).

##  How to Run

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the script:
python grade_predictor.py

Model Evaluation

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score
Custom accuracy (predictions within ±2 grade points)

 Future Work

Add Streamlit or Flask web interface
Use more advanced regression algorithms (e.g., Random Forest)
Support input from users directly via GUI






