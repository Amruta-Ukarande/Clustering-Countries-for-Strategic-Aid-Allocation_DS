# Clustering-Countries-for-Strategic-Aid-Allocation_DS

📌 Problem Statement

HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities.

HELP International have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. So, CEO has to make decision to choose the countries that are in the direst need of aid. Hence, your Job as a Data scientist is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.

Need and Use of Solving the Problem Statement

Need
Strategic Resource Allocation:
HELP International aims to maximize the impact of its $10 million funds by strategically allocating aid to countries most in need. Determining which countries require assistance the most is crucial for optimizing the utilization of resources and effectively combating poverty.
Data-Driven Decision Making:
Traditional methods of aid allocation may lack precision and objectivity. Leveraging data science techniques allows for a more systematic and evidence-based approach to identifying countries in dire need, ensuring that resources are allocated where they can make the most significant impact.
Targeted Intervention:
By categorizing countries based on socio-economic and health factors, HELP International can tailor interventions to address specific challenges faced by different regions. This targeted approach enhances the effectiveness and efficiency of aid delivery, leading to better outcomes for the communities served.

Use
Country Categorization:
Utilizing socio-economic and health factors, data scientists will categorize countries into distinct groups based on their level of development and need for aid. This segmentation enables HELP International to prioritize assistance to countries facing the most severe challenges.
Strategic Decision Support:
The data-driven insights provided by the analysis will inform the CEO's decision-making process regarding aid allocation. By highlighting countries with the greatest need, data science empowers HELP International to make informed, strategic decisions that maximize the impact of available resources.
Resource Optimization:
By focusing aid efforts on countries identified as being in the direst need, HELP International can optimize the allocation of its $10 million funds. This ensures that resources are directed where they can have the most significant positive impact on poverty alleviation and community development.
Benefits
Maximized Impact:
By targeting aid to countries with the greatest need, HELP International can maximize the impact of its resources, effectively addressing poverty and improving living conditions for vulnerable populations.
Efficient Resource Utilization:
Data-driven aid allocation enables HELP International to optimize the utilization of its funds, ensuring that every dollar is directed toward initiatives that have the greatest potential for positive change.
Improved Accountability:
Using objective criteria to prioritize aid allocation enhances transparency and accountability in decision-making. This helps build trust with stakeholders and donors by demonstrating a commitment to evidence-based practices and results-driven outcomes.



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
