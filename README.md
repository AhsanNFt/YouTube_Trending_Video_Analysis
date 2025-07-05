
# 📺 YouTube Trending Video Analysis

## 📌 Project Overview & Task Objective

The `Youtube_Trending_Analysis_Main.ipynb` notebook focuses on analyzing trending YouTube videos to understand patterns behind what makes content popular. The objective is to perform data cleaning, feature engineering, and exploratory analysis to uncover insights related to video trends, engagement, and content characteristics.

---

## 📂 Dataset Information

The dataset contains trending video data from YouTube including:
- Video metadata: title, tags, description, channel, category
- Engagement metrics: views, likes, dislikes, comments
- Dates: published and trending dates

**Key Cleaning Tasks:**
- Handled missing values (`description`)
- Removed duplicates
- Cleaned and transformed date/time fields
- Processed text fields (tags, description)

---

## ✨ Features

- Cleaned text, dates, and numerical fields
- Created new features:
  - Time-based: `publish_hour`, `publish_day_of_week`, `days_to_trend`, etc.
  - Engagement: likes/dislikes/comments per view
  - Textual: `tag_count`, `title_length`, `description_length`
- Explored content trends, engagement patterns, and timing insights

---

## 🛠️ Installation

Install required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🚀 Approach

- **Library Import**: Used pandas, numpy, matplotlib, seaborn
- **Data Cleaning**:
  - Removed nulls and duplicates
  - Converted date columns and removed timezones
  - Cleaned text (tags and descriptions)
- **Feature Engineering**:
  - Time-based: publish hour, weekday, month, year
  - Engagement metrics: per-view ratios and scores
  - Text stats: tag count, title and description length
- **Analysis Ready**: Dataset is fully preprocessed and feature-rich for visualization or modeling

---

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📊 Visualizations

> _Visualization examples can be added here if available (bar plots, trend lines, heatmaps, etc.)._

---

## 📉 Results and Insights

### Key Insights:
- Videos often trend **within 0–1 days** of publishing
- Higher engagement scores correlate with quicker trending
- **Upload timing** (hour/day) may influence trending behavior
- **Text length and tag count** can help assess content richness

---

## 🧪 Usage

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Youtube-Trending-Analysis.git

# 2. Navigate to the project directory
cd Youtube-Trending-Analysis

# 3. Launch the notebook
jupyter notebook Youtube_Trending_Analysis_Main.ipynb
```

---

## 🤝 Contributing

Feel free to contribute improvements, feature ideas, or visualizations. Open an issue or pull request.

---

## 📬 Contact

- GitHub: `YourGitHubUsername`  
- Email: `your-email@example.com`  
