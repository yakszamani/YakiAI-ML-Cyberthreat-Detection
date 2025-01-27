# YakiAI-Intelligent-Cyberthreat-Detection
An advanced machine learning project for User &amp; Entity Behavior Analytics (UEBA) that leverages AI to classify and detect suspicious activities in real-time, enhancing cybersecurity through data-driven insights.

## 🛡️ Project Overview
- Objective: To classify user behavior as Normal or Suspicious based on logs of activities such as logins, file access, and system changes.
- Dataset: A curated dataset capturing various user activities, timestamps, and labels for behavior classification.

## 📚 Key Features
**1. Data Preprocessing:**

- Timestamp conversion and normalization.
- Categorical column encoding using `LabelEncoder`.
- Feature scaling with `StandardScaler`.

**2. Machine Learning Models:**

- Random Forest Classifier
- Decision Tree
- CatBoost Classifier
K-Nearest Neighbors (KNN)


**3.Evaluation Metrics:**

- Accuracy, Precision, Recall, and F1-Score for model performance.
- Mean Squared Error (MSE) and R-squared values for prediction reliability.

## 🚀 Workflow
1. **Data Loading:** Imported user activity logs and structured them for ML training.
2. **Data Preparation**:
- Converted timestamps to numerical formats.
- Encoded and scaled features for uniformity.
3. **Model Training:** Trained multiple algorithms on the processed dataset.
4. **Model Evaluation:**
- Compared models based on metrics to identify the best-performing algorithm.
- Visualized predictions with scatter plots and regression lines.
5. **Insights & Improvements:**
- Optimized hyperparameters to reduce overfitting in Random Forest and CatBoost models.





📊 Results
Model	Accuracy	Precision	Recall	Training MSE	Test MSE	R² Score (Test)
Random Forest	80%	80%	80%	0.0	0.2	0.12
Decision Tree	70%	68.7%	70%	0.2875	0.3	-0.31
CatBoost	75%	76%	75%	0.0875	0.25	-0.09
KNN	80%	80%	80%	0.3875	0.2	0.12
Best Performer: Random Forest with a balanced performance across metrics.

## 🔮 Future Enhancements
- Implement advanced ensemble techniques to improve classification accuracy.
- Explore feature engineering to identify more robust behavioral patterns.
- Deploy the model in a real-time monitoring system to detect threats dynamically.

## 🔗 Getting Started
1. **Clone the Repository:**

```bash
git clone https://github.com/your-repo/cybersecurity-ml-project.git
```

2. **Install Dependencies:**

```bash
pip install -r requirements.txt
````

3. **Run the Notebook**: Open and execute `ML-Project.ipynb` for the full workflow.

## 📈 Visualizations
### Actual vs Predicted Behavior Scatter Plot
- A detailed plot showcasing model predictions against actual labels.
### Hyperparameter Tuning Results
- Comparison of various models and their metrics to identify the best fit

##  🤝 Contribute
Feel free to fork this repository and contribute by:

- Suggesting improvements to preprocessing and modeling.
- Adding new ML models or techniques.
- Enhancing visualizations and reporting.

✉️ Contact
For questions, feedback, or collaboration opportunities, reach out to:

- LinkedIn: [[LinkedIN Profile ](https://www.linkedin.com/in/sodunke-olasunkanmi/)]
