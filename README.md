# 🎬 IMDB Movie Data Analysis — Power BI Project

## 📘 Project Overview
This Power BI project presents an in-depth analysis of the **IMDB Movie Dataset**, showcasing insights into global cinema trends.  
The goal of this project is to analyze how factors such as **ratings, revenues, genres, directors, and metascores** influence the success of movies.  

The dashboard provides interactive visuals that allow users to explore movies by different dimensions such as **genre, release year, director, and audience response**.  
Through this project, I aimed to strengthen my data visualization and storytelling skills using Power BI.

---

## 🎯 Objectives
- Understand the relationship between **movie ratings** and **box-office performance**.  
- Identify **top-performing genres** and **directors**.  
- Examine **year-wise trends** in movie revenue and popularity.  
- Create an interactive dashboard for **quick insights** and **drill-down exploration**.  
- Demonstrate strong skills in **data cleaning**, **modeling**, **DAX**, and **visual design** in Power BI.

---

## 📊 Dataset Information
- **Source:** IMDB Movie Dataset (`IMDB-Movie-Data.csv`)  
- **Records:** 1,000 movies approximately  
- **Key Fields:** Title, Genre, Director, Year, Runtime (Minutes), Rating, Votes, Revenue (Millions), Metascore  

The dataset includes both numerical and categorical features, providing a balanced scope for visual and analytical storytelling.

---

## 🧹 Data Preparation
Data was cleaned and transformed using **Power Query Editor** in Power BI.  
Major steps included:
- Handling missing and null values in `Revenue` and `Metascore`.  
- Changing data types for numeric columns (Rating, Revenue, Votes).  
- Splitting multiple genres into individual categories.  
- Creating calculated columns such as **Decade**, **Revenue Range**, and **Rating Group** for better analysis.  
- Ensuring uniform formatting across columns.

---

## 🧩 Data Modeling
A **star schema** model was designed for simplicity and efficiency:
- **Fact Table:** Movie details (main dataset).  
- **Dimension Tables:** Genre, Year, and Director created for filter and lookup operations.  
- Relationships defined between these tables enabled accurate aggregation and cross-filtering.  

This structure improved performance and allowed for robust DAX calculations.

---

## 🎛 Filters and Slicers Used
The dashboard includes several slicers for dynamic and user-driven exploration:
- **Year** — analyze movies across different release years.  
- **Genre** — explore trends and performance by genre.  
- **Director** — compare the success and influence of directors.  
- **IMDB Rating** — filter based on audience rating levels.  
- **Metascore** — analyze critic ratings.  
- **Revenue Range** — categorize movies based on revenue performance.  

Each filter is fully interactive, dynamically updating visuals across all pages.

---

## 🧮 DAX Operations Created
Several **DAX measures** were used to enhance insights and interactivity within the report:  
- **Total Revenue (Millions)** — sums up the overall revenue across selected filters.  
- **Average IMDB Rating** — calculates the mean audience rating.  
- **Average Metascore** — computes the critic average score.  
- **Total Movies** — counts the number of movies visible based on active filters.  
- **Revenue Growth by Year** — shows how total revenue changes year over year.  
- **Top Genre by Revenue** — dynamically identifies the highest earning genre.  
- **Top Director by Revenue** — identifies the most commercially successful director.  
- **Revenue per Vote / Rating Ratio** — provides deeper insights into audience engagement.  

These DAX measures help drive interactivity and bring analytical depth to the report.

---

## 📈 Visualizations and Insights
The Power BI report consists of multiple pages focused on exploration and insights:

### 🔹 Overview Page
- Key metrics: **Total Movies**, **Average Rating**, **Average Revenue**, and **Average Metascore**.  
- **Trend line chart** showing yearly revenue patterns.  
- **Bar charts** displaying top genres and directors by revenue.  
- **Scatter plot** exploring the relationship between IMDB Rating and Revenue.

### 🔹 Genre Analysis
- Genre-wise comparison of **average ratings**, **movie count**, and **total revenue**.  
- Helps identify genres that perform well both critically and commercially.  
- Includes slicers for year and rating group to observe evolving trends.

### 🔹 Rating and Revenue Insights
- Distribution charts of **IMDB Rating** and **Metascore**.  
- Comparison visuals of audience vs critic reception.  
- Identifies movies with both **critical acclaim** and **box-office success**.

### 🔹 Top Movies Dashboard
- Displays **Top 10 Movies** based on either revenue or rating.  
- Includes **drillthrough** functionality to explore director and rating details.  
- KPIs for **revenue contribution** and **rating distribution**.

---

## ⚙️ Key Features
- **Interactive Slicers** for dynamic filtering.  
- **Drillthrough Pages** to view movie-level details.  
- **Dynamic Tooltips** for quick data interpretation.  
- **Bookmarks and Navigation Buttons** for smooth navigation.  
- **Clean UI/UX Design** with consistent theme and colors.  

Every visual is interconnected, ensuring a cohesive and intuitive user experience.

---

## 💡 Insights Derived
- **Action**, **Adventure**, and **Drama** are among the most dominant genres.  
- **Drama** and **Biography** genres often maintain high IMDB ratings but lower revenue.  
- A steady upward trend in **movie revenue** post-2010.  
- **High Metascore** movies tend to achieve better ratings from audiences.  
- **Top directors** consistently maintain strong average ratings across genres.  
- Ratings and revenue do not always correlate — some well-rated films earn less, while blockbusters may have moderate ratings.

---

## 🧠 Skills Demonstrated
- Data Cleaning and Transformation (Power Query)  
- Data Modeling and Relationship Design  
- Interactive Dashboard Building with Slicers, Filters, and Bookmarks  
- DAX for Calculated Measures and KPIs  
- Visual Storytelling and Dashboard UI/UX Design  
- End-to-End Business Intelligence Workflow  

---

## 🧰 Tools Used
- **Power BI Desktop** — for data modeling and visualization  
- **CSV Dataset** — IMDB Movie Data  
- **DAX** — for calculated measures and insights  
- **Power Query Editor** — for transformation and data cleaning  

---

## 🚀 How to Use
1. Download all files from this repository.  
2. Open the `.pbix` file in **Power BI Desktop**.  
3. Ensure the CSV file path matches your directory or update under *Transform Data → Data Source Settings*.  
4. Refresh data and interact with slicers and visuals to explore insights.  

---

## 📸 Dashboard Preview
*(Add dashboard screenshots here for visual reference)*  

| Overview Dashboard | Genre Analysis |
|--------------------|----------------|
| ![Overview](screenshots/dashboard.png) | ![Genre Analysis](screenshots/genre.png) |

---

## 📂 Repository Contents
| File | Description |
|------|--------------|
| `PowerBI Project1.pbix` | Main Power BI report file |
| `IMDB-Movie-Data.csv` | Dataset used for analysis |
| `screenshots/` | Contains dashboard images |
| `README.md` | Documentation for the project |

---

## 🏁 Conclusion
This Power BI project provides a complete exploration of **movie performance trends** using IMDB data.  
It demonstrates the power of data visualization and analysis to uncover insights on how **genres, directors, ratings, and revenues** influence movie success.  

It also highlights proficiency in **data cleaning, modeling, DAX, and dashboard design**, reflecting strong **data storytelling and analytical thinking** skills.

---

## 👨‍💻 Author
**Kishore S**  
📧 [Your Email or Contact Link]  
🔗 [LinkedIn Profile]  

---

## 🏷️ Tags
`#PowerBI` `#DataAnalysis` `#IMDB` `#DataVisualization` `#BusinessIntelligence` `#Dashboard` `#DataStorytelling` `#DAX`
