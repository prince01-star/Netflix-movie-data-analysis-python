# 🎬 Netflix / Movie Data Analysis using Python

## 📌 Project Overview

This project performs **End-to-End Exploratory Data Analysis (EDA)** on a movie dataset to identify key trends in movie releases, genres, popularity, and audience ratings.
The goal is to transform raw entertainment data into meaningful insights that can support **business decision-making for streaming platforms like Netflix, Amazon Prime, or Disney+.**

This project demonstrates strong capabilities in:

✔ Data Cleaning
✔ Data Transformation
✔ Feature Engineering
✔ Statistical Analysis
✔ Data Visualization
✔ Business Insight Generation

---

## 🎯 Business Problem

Streaming platforms must continuously decide:

* What type of movies should be produced?
* Which genres attract the highest audience?
* Do higher ratings correlate with popularity?
* Which years had the highest movie releases?
* What characteristics make a movie successful?

This project answers these questions using data-driven analysis.

---

## 📂 Dataset Information

**Dataset Name:** Movie Database (TMDB-based dataset)

### Features Included:

* Release_Date → Movie release date
* Title → Movie name
* Popularity → Popularity score based on user engagement
* Vote_Count → Number of votes received
* Vote_Average → Average rating
* Genre → Movie category
* Original_Language → Language of the movie
* Overview → Movie summary

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

📁 netflix-movie-data-analysis-python
 ├── Netflix_Movie_Data_Analysis.ipynb
 ├── mymoviedb.csv
 ├── README.md
 └── images/


## 🔎 Project Workflow

### ✅ 1. Data Loading

The dataset was imported using Pandas for structured analysis.

### ✅ 2. Data Understanding

Initial exploration included:

* Checking dataset shape
* Inspecting datatypes
* Generating descriptive statistics
* Identifying duplicates

**Result:**
No major null values were found.

---

### ✅ 3. Data Cleaning

Several columns were removed to improve performance and focus on analytical relevance:

* Overview
* Poster_Url
* Original_Language

These fields were not required for trend analysis.

---

### ✅ 4. Feature Engineering

#### ✔ Converting Release Date

The release date column was converted into **year format** to analyze movie production trends over time.

#### ✔ Categorizing Ratings

The `Vote_Average` column was segmented into four performance buckets:

* Not Popular
* Below Average
* Average
* Popular

This helps stakeholders quickly evaluate movie performance.

---

### ✅ 5. Genre Normalization

Movies often belong to multiple genres.

To enable accurate analysis:

* Genre values were split into lists
* Data was exploded to ensure **one genre per row**

👉 This significantly improves visualization accuracy.

---

## 📊 Data Visualization & Key Questions Answered

---

### ⭐ Most Frequent Movie Genre

**Question:** What genre dominates the platform?

✔ A count plot revealed the most produced genres, helping platforms understand content demand.

👉 **Business Insight:**
High-frequency genres indicate consistent viewer interest.

---

### ⭐ Vote Distribution

**Question:** How are movies distributed based on ratings?

✔ Category plots showed how many movies fall into each rating bucket.

👉 **Business Insight:**
Platforms should prioritize producing movies in higher-rated categories.

---

### ⭐ Highest & Lowest Popular Movies

**Question:** Which movies achieved extreme popularity scores?

✔ The analysis identified:

* Most popular movie
* Least popular movie
* Associated genres

👉 **Business Insight:**
Understanding these patterns helps predict blockbuster characteristics.

---

### ⭐ Movie Release Trends

**Question:** Which year saw the highest number of movie releases?

✔ Histogram analysis revealed production spikes across years.

👉 **Business Insight:**
Content production has increased significantly, indicating rising competition among streaming services.

---

## 📈 Key Insights

✔ Certain genres dominate movie production.
✔ Highly rated movies often correlate with stronger popularity.
✔ The movie industry is experiencing rapid growth in content creation.
✔ Viewer preferences can be predicted using genre and rating patterns.

---

## 🚀 Business Impact

This type of analysis can help streaming companies:

* Optimize content strategy
* Invest in high-performing genres
* Improve recommendation systems
* Predict audience behavior
* Reduce production risk

---

## 💡 Future Improvements

* Build a **Power BI Dashboard**
* Perform **Sentiment Analysis** on movie overviews
* Create a **Movie Success Prediction Model**
* Deploy an interactive dashboard
* Integrate live movie APIs

---

## 📸 Project Preview
<img width="917" height="845" alt="Screenshot 2026-02-07 173953" src="https://github.com/user-attachments/assets/8542149d-e52c-47a9-8767-8c13ee602369" />




---

## 👨‍💻 Author

**Prince Kumar**
MBA – Business Analytics

If you found this project useful, feel free to ⭐ the repository!

