# Netflix Data Visualization

This project analyzes and visualizes Netflix's dataset of movies and TV shows to uncover trends such as release years, monthly additions, genre popularity, and more.

## 📂 Dataset
The dataset used is [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows) from Kaggle.  
It contains details like:
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

## 📊 Features of the Analysis
- Dataset loading and exploration
- Data cleaning (handling missing values, date formatting)
- Filtering by Movies / TV Shows
- Extracting and visualizing:
  - Monthly content additions
  - Distribution of release years
  - Top genres/categories
  - Country-wise content count
- Visualizations using **Matplotlib** and **Seaborn**

## 🛠 Tech Stack
- **Python**
- **Pandas** (Data manipulation)
- **Matplotlib** & **Seaborn** (Data visualization)
- **NumPy**

## 📈 Insights
From the analysis, we observed:
- Movies dominate Netflix’s catalog compared to TV Shows.
- United States produces the highest amount of Netflix content, followed by India.
- Most frequent ratings are `TV-MA` (mature audience) and `TV-14`.
- Peak release years in the dataset are between 2017 and 2020.
- Monthly additions of TV Shows peak in October and December.
- Some directors, such as Rajiv Chilaka, contribute heavily to the content count.
<img width="903" height="546" alt="Screenshot 2025-08-14 015626" src="https://github.com/user-attachments/assets/b2241dec-8e81-41ad-b7b7-5da1415f4167" />



## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-visualization.git
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn numpy
3. Download the dataset from Kaggle and place it in the project folder.
4. Open and run the Jupyter Notebook
   ```bash
   jupyter notebook netflix-visualization.ipynb
