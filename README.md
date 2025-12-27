# Netflix-Project-Data-Analysis
This project analyzes the Netflix dataset to explore trends in movies and TV shows. It includes data cleaning, visualization, and insights on genres, ratings, and content distribution.
# 🎬 Netflix Data Analysis Project

This project focuses on performing **Data Cleaning**, **Exploratory Data Analysis (EDA)**, and **Visualization** on the Netflix dataset. The goal is to understand Netflix’s content trends, audience preferences, and distribution of movies and TV shows.

---

## 📌 Project Overview

Netflix is one of the world’s largest streaming platforms, offering thousands of Movies and TV Shows across various genres, languages, and countries.  
This project explores the dataset to uncover insights such as:

- Growth of content over the years  
- Movie vs TV Show distribution  
- Most contributing countries  
- Popular genres and ratings  
- Trends in release years  
- Data cleaning and preprocessing steps  

---

## 📂 Dataset Description

The dataset contains **8807 rows** and **12 columns** with features such as:

- `show_id`
- `type` (Movie / TV Show)  
- `title`  
- `director`  
- `cast`  
- `country`  
- `date_added`  
- `release_year`  
- `rating`  
- `duration`  
- `listed_in` (genre)  
- `description`

---

## 🧹 Data Cleaning Performed

Missing values were found in:

- `director`
- `cast`
- `country`
- `date_added`
- `rating`
- `duration`

### Cleaning Steps:
- Filled missing **director**, **cast**, and **country** with `"Unknown"`
- Filled missing **rating** and **duration** with their **mode**
- Filled missing **date_added** with the **most frequent date**
- Ensured all columns have consistent data types

---

## 📊 Non-Graphical Analysis

### ✔ Content Type Count
- **Movies:** 6131  
- **TV Shows:** 2676  

### ✔ Top Contributing Countries
- United States  
- India  
- United Kingdom  
- Japan  

### ✔ Ratings Distribution
Most common ratings:
- **TV-MA**
- **TV-14**
- **TV-PG**
- **R**

### ✔ Unique Values
- **Directors:** 4528  
- **Cast Members:** 7693  
- **Titles:** 8807  
- **Release Years:** 74  

---

## 🔍 Key Insights & Queries

### 📌 1. Movies Released Per Year (Last 30 Years)
A line chart shows a massive increase in movies added to Netflix especially between **2015–2019**.

### 📌 2. Movies vs TV Shows Comparison
Movies dominate the platform with more than **69%** share.

### 📌 3. Country-wise Content Distribution
USA and India produce the highest number of titles on Netflix.

### 📌 4. Most Popular Ratings Category
**TV-MA** is the most common rating on Netflix.

---

## 📈 Visualizations (Python Code Included)

The project uses:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

## Graphs you can generate include:
Line chart of movies per year.
Bar chart of movie vs TV show count.
Heatmaps.
Genre distribution.
Ratings distribution.

🛠 Tools & Technologies:
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab

🎯 Conclusion:
This analysis helps understand Netflix’s:
Content growth patterns.
Viewer preferences.
Most frequent countries, genres, and ratings.
TV Show vs Movie share.
These insights can support better content strategy, recommendation engines, and business decisions.
