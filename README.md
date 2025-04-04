IPL Score Prediction 🏏📈
This project aims to predict the final score of a team in an IPL (Indian Premier League) match based on current match statistics using machine learning models. The model is trained on data from IPL seasons 2008–2016 and tested on season 2017, with predictions extended to seasons 2018 and 2019.

📌 Project Objectives
Predict the total score of the batting team during an IPL match innings.

Analyze match-related features such as overs, runs, wickets, recent performance, and team identity.

Compare and evaluate various regression models to find the best-performing one.

📊 Dataset Overview
The dataset (ipl.csv) includes:

Batting and Bowling teams

Overs, Runs, Wickets

Runs & Wickets in the last 5 overs

Date of the match

Final score of the innings

🛠️ Technologies Used
Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

⚙️ Model Development
Data Cleaning: Removed irrelevant columns and filtered consistent team data.

Feature Engineering: One-hot encoded teams, removed early over data, and converted dates.

Models Used:

Linear Regression ✅

Decision Tree Regressor

Random Forest Regressor

AdaBoost Regressor (with Linear as base)

📌 Best Model: Linear Regression showed the lowest MAE, MSE, and RMSE.

📈 Prediction Inputs
Batting Team

Bowling Team

Overs

Runs Scored

Wickets Taken

Runs and Wickets in the last 5 overs

📌 Example Predictions
KKR vs Delhi (2018): Predicted Score – 200/9

MI vs KXIP (2019): Predicted Score – 186/8

✅ Conclusion
Linear Regression effectively predicts IPL scores based on past match data.

The model can be enhanced using feature tuning and more recent IPL data.

🚀 Future Work
Include newer seasons (2020 onwards).

Experiment with advanced models like XGBoost and Neural Networks.

Deploy the model with a web interface for live predictions.

📁 How to Run
Clone the repo

Install requirements: pip install -r requirements.txt

Run the notebook: ipl_score_prediction.ipynb

Explore predictions in the notebook or integrate the model into an app

🙌 Acknowledgements
Dataset sourced from Kaggle and cleaned manually

Project inspired by real-world cricket analytics and sports data science
