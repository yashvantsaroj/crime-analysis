# Chicago Crime Data Analysis

## 📌 Project Overview
This project involves cleaning, analyzing, and exploring the **Chicago Crime dataset** to identify crime patterns, trends, and insights.  
The analysis focuses on predominant crime types, temporal distribution, arrest patterns, and geographic hotspots.

## 🎯 Objective
- Perform **data cleaning and preprocessing** (handling missing values, removing duplicates, type conversions).
- Conduct **exploratory data analysis (EDA)** using statistical summaries and visualizations.
- Identify key crime patterns:
  - Predominant crime categories
  - Temporal analysis (monthly, daily trends)
  - Arrest and domestic incident patterns
  - Geographic distribution of crimes

## 📂 Dataset
The dataset is sourced from the [City of Chicago Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2).  
It contains ~20 columns including:

- **Primary Type** – Crime category  
- **Description** – Detailed description of crime  
- **Date / Year** – When the incident occurred  
- **Location Description** – Place of occurrence  
- **Arrest / Domestic** – Indicators for arrests and domestic violence cases  
- **Geographic details** – Beat, District, Ward, Coordinates  

*(Note: Due to size constraints, only a sample dataset is included in this repo. The full dataset can be accessed from the City of Chicago repository link above.)*

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas** – Data cleaning & wrangling  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Analysis environment  

## 📊 Analysis & Tasks
1. **Data Cleaning**
   - Handle missing values  
   - Drop unnecessary columns  
   - Standardize data types  
   - Remove duplicates  

2. **Exploratory Data Analysis (EDA)**
   - Identify most frequent crime types  
   - Temporal distribution (month, day trends)  
   - Arrest and domestic violence patterns  
   - Identify crime hotspots (districts/wards/locations)  

## 📈 Sample Insights
- Theft and Battery are among the most reported crime types.  
- Crime rates show seasonal patterns with spikes in summer months.  
- Domestic incidents and arrest patterns vary significantly across crime types.  
- Certain districts consistently show higher crime rates.  

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/crime-analysis.git
   cd crime-analysis
