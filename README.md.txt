# 🏠 Airbnb NYC 2019 - Exploratory Data Analysis

This project explores the Airbnb listing dataset from New York City (2019) to identify patterns in **price**, **room type**, **availability**, and **guest behavior**.

## 📊 Objective

- Analyze listing distribution by borough
- Compare pricing across different room types
- Understand guest behavior via reviews
- Identify outliers and pricing patterns using box/violin plots
- Examine feature relationships through correlation heatmaps

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Files in This Repository

- `airbnb_eda_project.ipynb` – Complete Jupyter Notebook for analysis
- `README.md` – Project summary and description
- `requirements.txt` – List of Python libraries used
- `AB_NYC_2019.csv` – NYC Airbnb listings dataset (source: Kaggle)


## 📌 Key Insights

- 🗺️ Manhattan has the highest number of listings; Bronx and Staten Island the least
- 🛏️ Entire homes are most expensive (avg ~$180); shared rooms the cheapest
- 📦 Box and violin plots show wide variation in prices, with many outliers
- 📈 Lower-priced listings attract more reviews
- 🌡️ Correlation reveals:
  - Negative link between price and number of reviews
  - Longer minimum stays lead to fewer reviews
  - Slight positive correlation between availability and minimum nights

## 🚀 How to Run

1. Clone this repo  
2. Install dependencies  
```bash
pip install -r requirements.txt
