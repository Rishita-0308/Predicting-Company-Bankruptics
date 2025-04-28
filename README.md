📄 Bankruptcy Prediction Project
🚀 Project Overview
This project aims to build a machine learning model capable of predicting the likelihood of company bankruptcy based on financial indicators. By leveraging historical financial data, the model supports proactive risk management, informed decision-making, and portfolio optimization.

🎯 Objectives
Predict company bankruptcy using financial ratios and metrics.

Identify key financial indicators most strongly associated with bankruptcy risk.

Compare different machine learning models to find the best-performing algorithm.

Develop a robust ensemble model for enhanced prediction accuracy.

Create clear and informative visualizations for data insights and model results.

📊 Dataset
Source: [Internal/Provided dataset — Bankruptcies.csv]

Records: 6,819 companies

Features: 95 financial indicators + 1 target variable (Bankrupt?)

Target Variable:

1: Bankrupt

0: Not Bankrupt

Feature Types: Mostly continuous numerical features (float64), some binary/integer features.

🔍 Project Workflow
Data Exploration (EDA):

Analyze feature distributions and detect patterns.

Visualize relationships using correlation heatmaps, boxplots, and distribution plots.

Feature Selection:

Correlation analysis to select relevant financial indicators.

Removal of redundant or highly correlated features if necessary.

Data Preprocessing:

Address class imbalance using techniques like undersampling or SMOTE.

Standardize/normalize features for model compatibility.

Model Building:

Train multiple classifiers (Logistic Regression, Decision Tree, Random Forest, etc.).

Compare performance across models.

Ensemble Modeling:

Develop a Voting Classifier using top-performing models for better overall accuracy.

Hyperparameter Tuning:

Use Grid Search or Random Search for optimal model parameters.

Performance Evaluation:

Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix.

Visualize results using classification reports and ROC curves.

Insights & Recommendations:

Discuss top predictive features and practical implications.

Highlight risks and considerations for real-world use.

🛠️ Tools and Libraries
Python 3.x

Pandas — data manipulation

NumPy — numerical computation

Matplotlib & Seaborn — visualization

Scikit-learn — machine learning algorithms and evaluation

Imbalanced-learn — handling class imbalance

❓ Key Questions Addressed
Which financial indicators are the strongest predictors of bankruptcy?

Which machine learning model provides the best prediction accuracy?

What are the potential risks and limitations of applying the model in real-world scenarios?

📈 Project Benefits
Improved financial risk assessment.

Informed lending, investment, and portfolio management decisions.

Early warning system for identifying financially distressed companies.

⚠️ Limitations and Risks
Data quality issues (if any) may affect model accuracy.

Economic changes or external market conditions are not accounted for.

Model may require periodic retraining to remain effective.

📎 Deliverables
Fully documented machine learning model.

Data exploration and feature analysis visualizations.

Comparative analysis of multiple models.

Ensemble model with hyperparameter tuning.

Final report with actionable insights.

👩‍💻 Created by: Rishita Shah 📅 Project Date: 2025
