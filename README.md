# Student_score_prediction
This project predicts a student’s final exam score based on key academic and lifestyle factors using Multiple Linear Regression. The goal is to analyze how study habits and past performance influence academic success.

📌 Problem Statement

Academic performance depends on multiple factors like study time, attendance, sleep, and previous performance.
This project aims to:
✔ Understand how each factor affects exam results
✔ Build a regression model to predict student exam scores
✔ Evaluate model accuracy and derive useful insights

📊 Dataset Overview

📌 Source:
[Student Scores Dataset on Kaggle]([https://www.kaggle.com/datasets/mexwell/student-scores](https://www.kaggle.com/datasets/mirzayasirabdullah07/student-exam-scores-dataset))

Total Records: 200

🔹 Features (Independent Variables)

hours_studied

sleep_hours

attendance_percent

previous_scores

🎯 Target Variable (Dependent)

exam_score

All features are numerical, making them suitable for linear regression.

🧠 Tech Stack / Libraries Used
Tool / Library	Purpose
Python	Programming
Pandas	Data handling
NumPy	Mathematical operations
Matplotlib, Seaborn	Data visualization
Scikit-Learn	Model training & evaluation
Jupyter Notebook	Development environment
🔍 Exploratory Data Analysis (EDA)

Insights:

hours_studied and previous_scores show strong positive correlation with exam score

Attendance and sleep show weaker but noticeable relationships

No multicollinearity among features → Good for regression

Visuals included:

Pairplot

Heatmap

Scatter plots

🤖 Machine Learning Model

Model Used: Multiple Linear Regression

📈 Model Performance
Metric	Score
MAE	2.31
RMSE	2.79
R² Score	0.85

📌 Interpretation:

The model explains 85% variation in exam scores — strong performance for real-world academic data.

📌 Key Takeaways

More study hours → Higher expected score

Strong relationship between previous and current performance

Model is accurate enough to be used for academic prediction systems

📎 Project Structure
│── student_score_prediction.ipynb
│── student_exam_scores.csv
│── README.md

🚀 Future Improvements

Try advanced regression models (Random Forest, Ridge, Lasso)

Add more student life features (stress level, motivation, etc.)

Deploy as web app using Streamlit / Flask

🙌 Author

Rehan
Machine Learning Beginner | Data Science Enthusiast
