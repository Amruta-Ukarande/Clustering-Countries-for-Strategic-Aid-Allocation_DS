# Clustering-Countries-for-Strategic-Aid-Allocation_DS

📌 Problem Statement

HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities.

HELP International have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. So, CEO has to make decision to choose the countries that are in the direst need of aid. Hence, your Job as a Data scientist is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.


🎯 Objectives
Strategic Resource Allocation: Direct funds to countries facing the most severe challenges.

Data-Driven Decision Making: Replace intuition-based allocation with systematic analysis.

Targeted Intervention: Tailor aid strategies to specific socio-economic and health needs.

Resource Optimization: Ensure every dollar contributes to poverty alleviation effectively.

📂 Dataset
The dataset includes socio-economic and health indicators for multiple countries.

Features:

Country: Name of the country

Child_mort: Child mortality (per 1000 live births)

Exports: Exports (% of GDP per capita)

Health: Health spending (% of GDP per capita)

Imports: Imports (% of GDP per capita)

Income: Net income per person

Inflation: Annual GDP growth rate

Life_expec: Life expectancy at birth

Total_fer: Fertility rate (children per woman)

Gdpp: GDP per capita

🔎 Exploratory Data Analysis (EDA)
Data Cleaning: Handle missing values and outliers.

Visualization: Scatter plots, histograms, and correlation heatmaps to identify trends.

Hypothesis Testing: Example – Higher child mortality correlates with lower GDP per capita.

🤖 Machine Learning Modeling
We use unsupervised learning to categorize countries:

Preprocessing
Missing value imputation (mean/median).

Normalization of numerical features.

Feature engineering (ratios, binary indicators).

Algorithms
K-Means Clustering

Hierarchical Clustering

DBSCAN

Evaluation
Elbow Method (optimal k).

Silhouette Score (cluster quality).

PCA Visualization (2D cluster plots).

🚀 Deployment (Flask API)
The clustering model is deployed via a Flask API for real-world use.

Steps:
Model Serialization: Save trained model with joblib.

API Endpoints: Accept country data in JSON format.

Prediction: Return cluster/category indicating aid priority.

Web Interface (Optional): Simple UI for stakeholders to input data and view results.

Example Workflow:

Input: Country data (GDP, child mortality, health spending).

Processing: API preprocesses and predicts cluster.

Output: Country classified as High Need, Medium Need, or Low Need.

✅ Benefits
Maximized Impact: Aid reaches the most vulnerable populations.

Efficient Resource Utilization: Funds directed to initiatives with highest potential.

Improved Accountability: Transparent, evidence-based allocation builds donor trust.
