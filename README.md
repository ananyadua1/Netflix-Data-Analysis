# 🎬 Netflix Dataset Analysis

### 📊 Exploratory Data Analysis & Insights

This project analyzes the **Netflix Dataset** to uncover trends in movies and TV shows available on the platform. The goal is to explore how content varies by category, genre, country, and release year, and to visualize these patterns using modern data visualization tools.

---

## 📘 Project Overview

The analysis focuses on understanding:

* The proportion of **Movies vs TV Shows**
* Yearly trends in Netflix content growth
* The **most popular genres** on the platform
* Country-wise contribution to Netflix’s library
* Ratings and duration distribution
* Overall key insights about Netflix’s content strategy

---

## 🧰 Tools & Technologies

* **Python**
* **Pandas** – Data loading, cleaning, and analysis
* **Matplotlib & Seaborn** – Static visualizations
* **Plotly Express** – Interactive charts
* **NumPy** – Data manipulation and calculations
* **Google Colab** – Notebook environment

---

## 🧹 Data Preprocessing

Key data cleaning and preparation steps:

* Removed duplicate entries
* Filled missing values in *Country*, *Director*, and *Cast* with “Unknown”
* Converted `release_date` to proper datetime format
* Extracted `year` from release dates for trend analysis
* Standardized column names for consistency

---

## 📈 Exploratory Analysis

1. **Category Distribution**

   * Movies dominate the dataset with around 69% of total content.
   * TV Shows make up the remaining 31%.

2. **Content Trends Over Time**

   * Netflix saw a sharp rise in new releases after 2015.
   * TV Shows gained significant traction in the late 2010s.

3. **Top Genres**

   * *Documentaries*, *Dramas*, and *Comedies* are among the most common genres.

4. **Country Contributions**

   * The **United States** produces the highest number of titles.
   * Other major contributors include India, the UK, and Canada.

5. **Ratings Distribution**

   * “TV-MA” and “TV-14” are the most frequent ratings, indicating mature and teen-oriented content.

6. **Duration Insights**

   * Most movies range between **80–120 minutes**.
   * TV shows typically have **1–4 seasons**.

7. **Yearly Genre Trends**

   * Documentaries and dramas have remained consistently popular across years.

---

## 💡 Key Insights

* **Total titles analyzed:** 7,789
* **Movies:** 5,379
* **TV Shows:** 2,410
* **Most common genre:** Documentaries
* **Top contributing country:** United States

---

## 🗺️ Future Enhancements

* Build an interactive **dashboard** to filter content by genre or country.
* Use **NLP techniques** to analyze descriptions and extract keywords.
* Predict content type or rating using **machine learning models**.
* Explore correlations between **cast/director popularity** and content ratings.

---

## 🙏 Acknowledgements

* **Netflix Dataset (Open Source)** for providing data for analysis.
* **Google Colab** for enabling seamless cloud-based execution.
* **Plotly, Matplotlib, Seaborn** for visualization support.
