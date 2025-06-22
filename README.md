# Student Performance Prediction
This project uses machine learning to predict whether a student will pass or fail based on their background and demographic information. The dataset includes features such as gender, race/ethnicity, parental education level, lunch type, and test preparation course, along with math, reading, and writing scores.

🔍 Problem Statement
Can we predict student success without directly using their scores — just based on their profile?
We define a student as "Pass" if their average score across all subjects is ≥ 60, otherwise "Fail".

🧠 What I Did
🔎 Exploratory Data Analysis (EDA) using Pandas, Seaborn, and Matplotlib

🛠️ Feature Engineering: Calculated average scores, created binary pass column

🔢 Label Encoding of categorical variables

🤖 Model Training: Tried Random Forest and XGBoost classifiers

📊 Evaluation: Used Accuracy, Precision, Recall, F1-score, and Confusion Matrix

🧪 Experimented with multi-class classification but reverted to binary for better performance

📊 Final Results
Best Model: XGBoost Classifier

Accuracy: ~66%

Key Insight: Predicting student outcomes from profile-only data is hard. Model performed better at predicting who will pass than who will fail.


📌 Tools & Libraries
-Python
-Pandas
-Matplotlib
-Seaborn
-Scikit-learn
-XGBoost

🎓 Key Takeaways
Machine Learning needs strong signal; profile data has limited predictive power

Accuracy is not everything — understanding recall, precision, and F1 is crucial

Simpler binary classification worked better than over-complicating with multi-class

Sometimes you have to roll back to move forward (and that’s okay)

💡 Future Ideas
Try using raw scores as features to improve model accuracy

Apply hyperparameter tuning (GridSearchCV)

Test with a neural network (like using Keras)

🙋‍♂️ Author
Vishwajeet Survase
First-year B.Tech CSE Student | Aspiring ML Engineer
Connect with me on LinkedIn
