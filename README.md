🏡 Real Estate Listings: EDA, Classification & Dashboard

This project analyzes Airbnb-style listing data using Exploratory Data Analysis, Classification Modeling, and a Power BI Dashboard. It provides data-driven insights and predicts price categories through machine learning techniques.

🧭 Step-by-Step Breakdown

🧹 Preprocessing (listingsML.ipynb)

1. Removed target leakage (price, price_class)
2. Retained only informative features
3. No categorical conversion for numeric features
4. Dataset prepared for classification algorithms

📊 Exploratory Data Analysis (EDA Project.ipynb)

1. Explored price distribution, availability, and reviews
2. Analyzed location-wise patterns and trends
3. Identified feature relationships using heatmaps and pairplots
4. Detected missing values and outliers

🤖 Classification Modeling (classification.ipynb)

1. Applied Logistic Regression to predict price classes
2. Used only numerical features (as per dataset context)
3. Visualized decision boundaries using contour plots
4. Evaluated model with accuracy and confusion matrix

📈 Dashboard & Reporting (Cleaned.pbix)

1. Built an interactive Power BI dashboard
2. Visual filters for availability, location, and price ranges
3. KPIs for average price, minimum nights, number of reviews
4. Map visualizations for geographic insights

✅ Key Features

🧼 Clean and ready-to-model dataset
📊 Professional Power BI Dashboard
🧠 ML-driven price class prediction
🔎 Insightful EDA for decision-making
🛠️ Reusable pipeline for similar listings datasets

🛠 Technologies Used

Component	Tools / Libraries
Data Handling	Python, Pandas, NumPy
Visualization	Matplotlib, Seaborn, Power BI
Modeling	scikit-learn (Logistic Regression)
Dashboarding	Power BI Desktop
Environment	Jupyter Notebook

DASHBOARD

![Final1](https://github.com/user-attachments/assets/419e7dbc-edf6-4683-8359-08361762b30f)
![Final2](https://github.com/user-attachments/assets/1b999eb2-75f3-4268-a79f-a0eeec0d0edd)


🔍 Actionable Insights

High-price areas can be identified using location-based KPIs
Logistic model predicts if a listing falls in a high or low price category
Dashboard helps non-technical users explore real estate trends

📁 Files Included

1. Filename	Description
2. EDA Project.ipynb	Exploratory data analysis
3. classification.ipynb	Logistic regression classifier
4. listingsML.ipynb	Preprocessing & model preparation
5. Cleaned.pbix	Interactive dashboard built in Power BI
