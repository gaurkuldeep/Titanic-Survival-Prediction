🚢 Titanic Survival Prediction using Machine Learning

📘 Overview


This project predicts the survival of passengers on the Titanic using Logistic Regression, a classification algorithm.
It demonstrates how data preprocessing, feature engineering, and model evaluation can be applied to a real-world dataset.



🚀 Features

Data cleaning and preprocessing (handling missing values, encoding, scaling)

Exploratory Data Analysis (EDA) with visualizations

Model training using Logistic Regression

Model evaluation using Confusion Matrix and accuracy metrics

Insightful analysis of key survival factors



🧠 Algorithm Used

Logistic Regression — to classify whether a passenger survived (1) or not (0).

🛠️ Tech Stack
Category	Tools
Programming	Python
Libraries	Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
Dataset	Titanic Dataset (Kaggle)
IDE	Jupyter Notebook / VS Code



📊 Workflow

Load Dataset → Import Titanic dataset using Pandas.

Data Preprocessing → Handle missing values, encode categorical variables, and normalize data.

EDA → Visualize survival rates by gender, class, and age.

Model Training → Train Logistic Regression model on preprocessed data.

Model Evaluation → Assess accuracy and visualize confusion matrix for performance analysis.

Prediction → Predict survival on new/unseen data.



📈 Results
Metric	Value
Accuracy	~82%
Precision	~79%
Recall	~76%

✅ The model achieved strong predictive performance using Logistic Regression with balanced precision and recall.



💡 Insights

Gender and Passenger Class (Pclass) strongly influence survival chances.

Female passengers and those in higher classes had a higher probability of survival.

Confusion Matrix provided a clear view of correct and incorrect classifications.



🏁 Conclusion

This project demonstrates how Logistic Regression can effectively handle binary classification problems.
It highlights the importance of data preprocessing, feature selection, and evaluation metrics in building reliable ML models.

📁 Repository Structure
📂 titanic-survival-prediction
 ┣ 📜 titanic_survival_prediction.ipynb
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📊 dataset.csv
 ┗ 📊 images/ (optional: EDA plots, confusion matrix)

 

🧩 Future Enhancements

Implement Random Forest and SVM models for comparison

Perform Hyperparameter tuning for better accuracy

Build a Streamlit/Flask web app for real-time prediction



🤝 Contributing

Contributions are welcome! Fork the repo, improve the model, and submit a pull request.
