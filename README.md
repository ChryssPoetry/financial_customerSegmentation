# financial_customerSegmentation

Customer Segmentation and Insights Dashboard
This project is a Streamlit application designed for customer segmentation and insights analysis, specifically tailored for financial transaction data. It incorporates data cleaning, visualizations, machine learning, and actionable insights to assist in understanding customer behavior and risk patterns.

Features
1. Data Cleaning
Handles duplicate entries and missing values by using median imputation.
Prepares the dataset for advanced analysis.
2. Data Visualizations
Histogram: Distribution of transaction amounts to understand financial activity trends.
Boxplot: Risk scores and transaction amounts segmented by customer clusters.
Scatterplot: Visual clustering of customers based on key features.
3. Machine Learning
Implements a Random Forest Classifier to predict fraud risk (risk_flag).
Provides:
Confusion Matrix for performance evaluation.
Classification Report with precision, recall, and F1 scores.
4. Actionable Insights
Summarizes customer segmentation and provides recommendations for:
High-risk customers.
High-value transactions.
Engagement improvement strategies for low-frequency users.
Installation and Setup
Prerequisites
Python 3.8 or higher
Streamlit
Pandas
Matplotlib
Seaborn
Scikit-learn
Installation Steps
Clone or download this repository.
Install the required Python packages:
bash
Copy code
pip install streamlit pandas matplotlib seaborn scikit-learn
Place the dataset cleaned_metaverse_transactions.csv in the appropriate directory (default: ~/downloads/).
Running the Application
Navigate to the project directory.
Run the Streamlit app:
bash
Copy code
streamlit run customer_segmentation_dashboard.py
Open the provided URL (default: http://localhost:8501) in your web browser.
Project Structure
customer_segmentation_dashboard.py: Main Streamlit app script.
cleaned_metaverse_transactions.csv: Input dataset containing financial transaction data.
Visualizations: Plots generated dynamically in the app to analyze and interpret data.
Insights Provided
Cluster-Based Analysis
High-risk customers with high risk_score.
High-value customers with high amount.
Low-engagement users with low login_frequency.
Machine Learning
Fraud risk predictions using a Random Forest model.
Statistical evaluation of model performance.
Future Improvements
Add advanced clustering techniques (e.g., k-means++ or hierarchical clustering).
Enhance UI/UX with better interactive features.
Integrate the app with cloud storage for real-time data updates.
License
This project is open-source and available for educational or professional use. Feel free to adapt and extend as needed.

