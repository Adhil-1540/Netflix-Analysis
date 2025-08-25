# 🎬 Netflix Power BI Dashboard

This project is a Power BI dashboard built using the Netflix dataset.  
The goal of this project is to explore and visualize Netflix content trends such as movies vs TV shows, duration, release years, and country-wise insights.

---

## 📂 Dataset
The dataset used is **Netflix Titles** which contains:
- Show ID  
- Title  
- Director  
- Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Listed In (Genre)  

### Data Cleaning & Transformation (Power Query)
- Extracted `Duration (minutes)` for movies.  
- Created `Seasons` column for TV shows.  
- Handled null values in `Date Added`, `Country`, and `Duration`.  
- Split `Duration` column into **minutes** and **seasons** for better analysis.  
- Dropped irrelevant columns like `Description` (not used in visuals).  

---

## 📊 Dashboard Pages & Visuals

### **Page 1 – Home (Overview)**
- Donut Chart: Movies vs TV Shows distribution  
- Bar Chart: Titles by Country  
- KPI Cards: Total Titles, Movies, and TV Shows  
- Navigation Menu for other pages  

### **Page 2 – Movie Analysis**
- Average Movie Duration  
- Oldest Movie Year  
- Bar Chart: Movie count by Country  
- Line Chart: Movies released over time  

### **Page 3 – TV Shows Analysis**
- Oldest TV Show Year  
- Donut Chart: Ratings distribution for TV shows  
- Bar Chart: Titles by Seasons  

### **Page 4 – Trends**
- Line Chart: Titles added over time  
- Stacked Bar/Area Chart: Movies vs TV Shows trend over years  
- KPI Cards: Year with maximum additions, Total Movies, Total TV Shows  

---

## 🚀 Insights
- Majority of Netflix content consists of **Movies** over **TV Shows**.  
- USA and India are the top content-producing countries.  
- Content production has significantly increased post-2015.  
- TV Shows are usually short (1–2 seasons).  
- The average Netflix movie duration is around **90 minutes**.  

---

## 🛠️ Tools Used
- **Power BI** → Dashboard & Visuals  
- **Power Query** → Data Cleaning & Transformation  
- **Microsoft Excel / CSV** → Initial dataset format  

---

## 📌 How to Use
1. Clone this repository.  
2. Download the dataset (`netflix_titles.csv`).  
3. Open the Power BI file (`Netflix_Dashboard.pbix`).  
4. Explore the interactive visuals.  

---

## ✨ Author
👤 **Adhil Kappan**  
📧 adhilkappan80@gmail.com  
🔗 www.linkedin.com/in/adhil-kappan  

