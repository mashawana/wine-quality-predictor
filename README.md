# wine-quality-predictor

This project builds a Machine Learning model using a Random Forest Classifier to predict whether a wine is "Good" (sensory score ≥ 7) or "Average/Bad" based on its chemical properties. The dataset is sourced from the famous UCI Machine Learning Repository.

Dataset & Features
The dataset combines both red and white Portuguese "Vinho Verde" wine variants. Key chemical features analyzed include:
* Alcohol content
* Volatile acidity
* Sulphates
* pH levels

Workflow & Tech Stack
* Language:Python
* Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* Process: Data cleaning ➔ Target binarisation ➔ Feature scaling (StandardScaler) ➔ Train/Test splitting ➔ Model fitting ➔ Evaluation

Key Results
* Model Used: Random Forest Classifier
* Top Predictive Feature: Alcohol content was discovered to be the strongest visual and mathematical driver of a higher wine quality rating.
