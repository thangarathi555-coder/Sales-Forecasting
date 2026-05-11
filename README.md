📊 Predictive Analytics Project: Sales Forecasting Using Python
🧾 Overview

This project focuses on analyzing historical sales data to understand sales performance and predict future trends using machine learning techniques. The workflow follows a structured data analysis pipeline including preprocessing, exploratory analysis, visualization, and forecasting.

The main goal is to study sales patterns over time and build a simple predictive model to forecast future sales.

📁 Dataset Source

Sales dataset (CSV file)
Features include:

Order Date
Sales
Region
Other related business fields
🎯 Objectives
Analyze historical sales performance
Identify total, average, maximum, and minimum sales
Study sales trends over time
Compare sales across regions
Build a predictive model to forecast future sales
Visualize insights for better decision-making
🔧 Project Highlights
📌 Data Preprocessing
Loaded dataset using pandas
Converted Order Date into datetime format
Removed duplicate records
Handled missing values
Sorted data based on date for time-series analysis
📊 Exploratory Data Analysis (EDA)
Displayed dataset structure using info()
Checked first few records
Calculated:
Total sales
Average sales
Maximum sales
Minimum sales
📈 Data Visualization
📉 Line Chart: Sales Over Time
Shows how sales change across dates
Helps identify trends and fluctuations
📊 Bar Chart: Sales by Region
Compares total sales across different regions
Helps identify top-performing regions
🤖 Predictive Modeling (Machine Learning)
Created a time-based feature (Days) from order date
Used Linear Regression model from sklearn
Trained model using past sales data
Predicted next 30 days of sales
📉 Forecast Visualization
Plotted actual sales data
Compared with predicted future sales
Visualized trend continuation using dashed line
🛠 Tools and Technologies
Python
pandas
numpy
matplotlib
scikit-learn (Linear Regression)
Google Colab / Jupyter Notebook
<img width="752" height="575" alt="image" src="https://github.com/user-attachments/assets/a947ab58-3249-403c-889b-6485f1b560ce" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a6bc9105-f223-4771-aaf9-ff614321f5fc" />
<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/118489b8-fcdb-488e-8deb-b82a451ba4c1" />

