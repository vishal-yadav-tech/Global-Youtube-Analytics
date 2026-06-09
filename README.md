# Global YouTube Analytics & Performance Prediction using Machine Learning

A Python-based Data Analytics + Machine Learning project that performs complete YouTube channel analysis using a CSV dataset and predicts channel performance using Machine Learning.

This project loads YouTube data, cleans and preprocesses it, performs feature engineering, generates multiple visualizations, and predicts subscriber performance.


# Project Objective

Build an YouTube Analytics system that:

✔ Loads real-world YouTube CSV dataset  
✔ Cleans and preprocesses raw data  
✔ Performs Feature Engineering  
✔ Generates Analytics Charts  
✔ Performs Correlation Analysis  
✔ Predicts Subscribers using Machine Learning  
✔ Produces visual outputs automatically  


# Technologies Used

| Category | Technology |
|----------|-----------|
| Language | Python |
| Notebook | Jupyter Notebook |
| Data Handling | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Statistical Charts | Seaborn |
| Machine Learning | Scikit-Learn |
| File Processing | CSV |
| IDE | VS Code / Jupyter |



# Libraries Used

pandas
numpy
matplotlib
seaborn
scikit-learn
os
 

Install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

or

```bash
pip install -r requirements.txt
```



# 📂 Project Structure

```plaintext
GLOBAL YOUTUBE ANALYTICS
│
├── youtube_analytics_ml.ipynb
│
├── dataset/
│      └── youtube.csv
│
├── outputs/          ( automatically create after run the program )
│      ├── bar_country_domination.png
│      ├── category_growth.png
│      ├── channel_type_distribution.png
│      ├── correlation.png
│      ├── subscriber_growth_trend.png
│      ├── upload_distribution.png
│      ├── views_vs_subscribers.png
│      └── ml_prediction.png
│
│
└── README.txt
```

---

# 📊 Dataset Information

Dataset contains global YouTube channel information.

Columns:

```plaintext
rank
Youtuber
subscribers
video views
category
Title
uploads
Country of origin
Country
Abbreviation
channel_type
video_views_rank
country_rank
channel_type_rank
video_views_for_the_last_30_days
lowest_monthly_earnings
highest_monthly_earnings
lowest_yearly_earnings
highest_yearly_earnings
subscribers_for_last_30_days
created_year
created_month
created_date
Gross tertiary education enrollment (%)
Population
Unemployment rate
Urban_population
Latitude
Longitude
```

---

# ⚙ Data Processing Pipeline

```plaintext
START
│
├── Load CSV Dataset
│
├── Data Cleaning
│      ├── Missing Values
│      ├── Duplicate Removal
│      └── Numeric Conversion
│
├── Data Preprocessing
│      ├── Encoding
│      ├── Formatting
│      └── Transformation
│
├── Feature Engineering
│      ├── Engagement Rate
│      ├── Revenue per Subscriber
│      ├── Growth Metrics
│      └── Upload Efficiency
│
├── Exploratory Data Analysis
│
├── Correlation Analysis
│
├── Machine Learning
│
├── Prediction
│
└── END
```


# 🤖 Machine Learning

Model:

```plaintext
Linear Regression
```

Workflow:

```plaintext
Train-Test Split
↓
Model Training
↓
Prediction
↓
Evaluation
```

Evaluation Metrics:

```plaintext
MAE
R² Score
```



# 📌 Project Outcome

This project successfully:

✔ Cleaned raw YouTube data  
✔ Engineered analytical features  
✔ Generated business insights  
✔ Visualized global YouTube trends  
✔ Predicted subscriber performance  
✔ Produced presentation-ready outputs  

---

# 👨‍💻 Author

Name: Vishal Yadav

Project:
Global YouTube Analytics & Performance Prediction using Machine Learning
