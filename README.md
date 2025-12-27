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
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
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
- Filled missing **rating** and **duration** using **mode()**
- Filled missing **date_added** using **mode()**
- Converted column types where needed  
- Removed outliers using **IQR technique**

---

## 🛠 Tools & Technologies Used

- **Python**
- **Jupyter Notebook / Google Colab**
- **Pandas** for data cleaning and preprocessing  
- **NumPy** for numerical operations  
- **Matplotlib** for visualization  
- **Seaborn** for advanced visualizations  

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
- TV-MA  
- TV-14  
- TV-PG  
- R  

### ✔ Unique Values
- Directors: 4528  
- Cast Members: 7693  
- Titles: 8807  
- Release Years: 74  

---

## 🔍 Key Insights & Queries

### 1️⃣ **Movies Released Per Year**
Shows rapid growth after 2010, peaking around 2018–2020.

### 2️⃣ **Movies vs TV Shows**
Movies make up **69%** of Netflix’s library.

### 3️⃣ **Country-wise Content**
USA and India contribute the most.

### 4️⃣ **Ratings Popularity**
Most titles fall under **TV-MA** and **TV-14**.

---

## 📈 Visualizations Included

- Line charts (Year-wise movie releases)  
- Bar charts (Movies vs TV Shows)  
- Heatmaps (Correlation)  
- Count plots (Ratings, Genres)  
- Boxplots (Rating vs Release Year)  

---

## 🧠 Conclusion

- ✔ **Movies dominate** Netflix’s content library (over 69%).  
- ✔ Most titles are rated **TV-MA** or **TV-14**, showing focus on adult and teen audiences.  
- ✔ **USA and India** produce the maximum content on Netflix.  
- ✔ Netflix’s content has seen **major growth after 2015**.  
- ✔ **Dramas, Documentaries, and Comedies** are the most common genres.  
- ✔ Newer movies tend to be **shorter**, with a weak negative correlation between release year and duration.  
- ✔ Netflix adds titles frequently, maintaining its global content diversity.  

These insights can help Netflix enhance content strategy, improve recommendations, and target the right audience.

---

## 📁 Project Structure
📦 Netflix-Data-Analysis
│
├── 📁 data
│ └── netflix.csv
│
├── 📁 notebooks
│ └── netflix_analysis.ipynb
│
├── 📁 sql
│ └── netflix_queries.sql
│
├── 📁 reports
│ └── Netflix__Project.pdf
│
└── README.md


