# TikTok Engagement Dashboard 

## Project Overview
This project simulates and analyzes engagement metrics for 50 TikTok videos. The goal is to demonstrate **product thinking, data analysis, and actionable insights** for TikTok content strategies. It is designed as a **quick, high-impact project** suitable for demonstrating skills to recruiters or for resume enhancement.

---

## Key Features
- **Simulated Dataset**: 50 TikTok videos with metrics like Likes, Comments, Shares, Views, Content Category, and Video Length.
- **Engagement Metric**:  
  The engagement rate is calculated as:  

  **Engagement Rate = (Likes + Comments + Shares) / Views**
  
- **Data Analysis**: 
  - Average engagement rate per content category.
  - Relationship between video length and engagement rate.
- **Visualizations**: 
  - Bar chart for engagement rate by content category.
  - Scatter plot for video length vs engagement rate.
- **Insights & Recommendations**:
  - Comedy videos show the highest engagement.
  - Short videos (20–40 seconds) perform better.
  - Suggest focusing on short, high-engagement content.

---

## Dataset
The Excel dataset `TikTok_Engagement_50videos.xlsx` contains the following columns:

| Column Name        | Description                              |
|-------------------|------------------------------------------|
| Video_ID           | Unique ID for each video                  |
| Content_Category   | Video category (Comedy, Dance, DIY, Food, Education) |
| Video_Length_sec   | Video length in seconds                   |
| Likes              | Number of likes                           |
| Comments           | Number of comments                        |
| Shares             | Number of shares                          |
| Views              | Number of views                           |

> **Location:** Save the file in `Desktop/Spreadsheet` folder for code execution.

---

## Tools & Technologies
- Python 3
- Pandas (for data manipulation)
- Matplotlib (for visualization)
- Excel (data storage and optional analysis)

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
```
2. Ensure the dataset `TikTok_Engagement_50videos.xlsx` is saved in:
```bash
`Desktop/Spreadsheet/TikTok_Engagement_50videos.xlsx`
```

3. Run the Python script:  
```bash
python TikTok_Engagement_Dashboard.py
```
4. View the printed insights in the console and visualizations in pop-up windows.

---

## Sample Insights

- Comedy videos have the highest average engagement.
- Shorter videos (20–40 seconds) tend to get higher engagement.
- **Recommendation:** Encourage short, comedic content to maximize user interaction.
---
