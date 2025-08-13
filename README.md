# 📊 Data Analysis Projects

This repository contains my personal data analysis projects, covering data cleaning, exploratory data analysis (EDA), visualization, and insights generation using **Python** and **Excel**.  
Each project focuses on a different dataset and explores unique patterns, trends, and insights.

---

## 📂 Projects
## 📜 Table of Contents
1. [Netflix Data Visualization](Netflix/) – [Details](#-Netflix-Data-Visualization)


### 1️⃣ Netflix Data Visualization
Analyzes and visualizes Netflix's dataset of movies and TV shows to uncover trends such as release years, monthly additions, genre popularity, and more.

**Dataset:** [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows) from Kaggle  
Contains details like:
- **Title**
- **Director**
- **Cast**
- **Country**
- **Date Added**
- **Release Year**
- **Rating**
- **Duration**
- **Listed In** (Genre)
- **Description**

**Key Analysis Steps:**
- Data loading & cleaning (handling missing values, date formatting)
- Filtering by Movies / TV Shows
- Extracting and visualizing:
  - Monthly content additions
  - Release year distribution
  - Top genres
  - Country-wise content count
- Visualizations using **Matplotlib** and **Seaborn**

**Insights:**
- Movies dominate Netflix’s catalog compared to TV Shows.
- United States produces the highest amount of Netflix content, followed by India.
- Most frequent ratings are `TV-MA` (mature audience) and `TV-14`.
- Peak release years: **2017–2020**
- Monthly TV Show additions peak in **October** and **December**.
- Some directors (e.g., Rajiv Chilaka) have disproportionately high content counts.

![Netflix Visualization Screenshot](https://github.com/user-attachments/assets/b2241dec-8e81-41ad-b7b7-5da1415f4167)

---

## 🛠 Tech Stack
- **Python** – Pandas, NumPy, Matplotlib, Seaborn
- **Excel** – Pivot Tables, Charts, Dashboards
- **Jupyter Notebook** – Interactive data exploration

---

## 🚀 How to Run a Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/data_analysis.git
2. Install Dependencies
    ```bash
    pip install pandas matplotlib seaborn numpy
3. Navigate to the specific project folder.
4. Download the dataset (if not included) and place it in the folder.
5. Run the notebook:
    ```bash
    jupyter notebook

---

## 📌 Future Plans
- Add more datasets and analyses.
- Include interactive dashboards (Plotly / Power BI / Tableau).
- Perform predictive modeling on selected datasets.
