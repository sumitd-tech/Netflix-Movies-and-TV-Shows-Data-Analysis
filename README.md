# Netflix Movies and TV Shows Data Analysis

## Project Description

This project analyzes Netflix content data using Python to understand trends in movies and TV shows. The focus is on cleaning the dataset, exploring release patterns over time, identifying popular genres, and finding which countries contribute the most content to Netflix. The analysis helps understand how Netflix’s content library has evolved over the years.

---

## Dataset Overview

- File: Netflix Dataset (8).csv
- Initial records: 7,789
- Records after cleaning: 7,777
- Columns: 11 (cleaned and standardized)

Main columns include title, category, director, cast, country, release date, rating, duration, genre/type, and description.

---

## Tools & Libraries Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Plotly  

---

## Data Cleaning Summary

- Removed duplicate rows (2 duplicates found)
- Normalized column names (lowercase, underscores)
- Trimmed whitespace in text columns
- Handled missing values in important fields
- Extracted **release_year** from release_date
- Standardized content into **Movie** and **TV Show**
- Converted genre column into a list for multi-genre analysis
- Cleaned country column to keep the primary country
- Saved cleaned and aggregated datasets

---

## Business Questions & Answers We get

### 1. How has Netflix content changed over time?
Netflix content increased significantly after 2016.  
The highest number of releases were seen in:
- **2019: 2,153 titles**
- **2020: 2,009 titles**
This shows rapid content expansion before and during this period.

---

### 2. Are movies or TV shows more common on Netflix?
Movies dominate the platform overall, but TV shows have steadily increased over the years.  
Both content types saw strong growth after 2017.

---

### 3. What are the most popular genres on Netflix?
Top genres by number of titles:
- International Movies: **2,437**
- Dramas: **2,106**
- Comedies: **1,471**
- International TV Shows: **1,199**
- Documentaries: **786**

This shows Netflix strongly focuses on international and drama-based content.

---

### 4. Which countries contribute the most content?
Top contributing countries:
- United States: **2,883 titles**
- India: **956 titles**
- United Kingdom: **577 titles**
- Canada: **259 titles**
- Japan: **237 titles**

Netflix has a strong global presence, with significant content from outside the US.

---

### 5. What is the average number of genres per title?
- **Average genres per title: ~2.19**

Most titles belong to more than one genre, indicating mixed or hybrid content categories.

---

### 6. When was Netflix most active in releasing content?
Netflix was most active between **2017 and 2020**, with peak releases in **2019 and 2020**.

---

## Key Insights

- Netflix content growth accelerated after 2016
- Movies are more common, but TV shows are growing steadily
- International content plays a major role in Netflix’s library
- Drama and international genres dominate
- The US, India, and the UK are the largest content producers

---

## Outputs

- Cleaned Netflix dataset (CSV)
- Aggregated dataset: Movies vs TV Shows by release year
- Visualizations using Matplotlib, Seaborn, and Plotly

---

## Project Purpose

This project was created to strengthen skills in:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Working with real-world datasets
- Data visualization
- Converting analysis results into meaningful insights

---

## How to Run the Project

1. Clone the repository
2. Install required Python libraries
3. Run the notebook or Python script step by step

---

## License

This project is for learning and educational purposes only.  
The dataset belongs to its original source.
