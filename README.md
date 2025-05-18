# Adult Income Prediction using CRISP-DM Methodology

This project applies the CRISP-DM methodology to the **Adult Income Dataset** from the UCI Machine Learning Repository. The objective is to build a machine learning model that predicts whether an individual earns more than \$50K/year based on demographic data.


- Understand and preprocess the data
- Explore different ML classification models
- Evaluate model performance
- Deploy the best model (prototype phase)



- File: `adult.data`
- Source: UCI Machine Learning Repository
- Features: 14 input variables (age, education, workclass, etc.) + 1 target


- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Google Colab
- Matplotlib, Seaborn
- GitHub for version control


- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (Best performing model: ~87% accuracy)


- Accuracy, Precision, Recall, F1-score
- Confusion Matrix


Can be deployed via Flask or FastAPI as a web service prototype for salary prediction.


- `adult_income_prediction.ipynb`: Main notebook (Google Colab)
- `requirements.txt`: Python dependencies
- `README.md`: Project summary



