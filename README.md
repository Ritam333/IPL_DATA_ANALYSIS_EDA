# 🏏 IPL Exploratory Data Analysis (EDA) Project

Welcome to the **IPL EDA Project**, where cricket meets data! This project dives deep into IPL (Indian Premier League) statistics, uncovering trends, insights, and performance metrics that cricket fans and data enthusiasts will love. 🎉

---

## 📂 **Project Structure**

### Data Collection
All the data used in this project is collected from **Kaggle**. Please note that the data might have some discrepancies or errors, but overall, the major data points are accurate and match real-life events.

### Data Cleaning
The data was cleaned and processed using the following steps:
- **Handling missing values**: Missing data was filled with appropriate values or removed based on the context.
- **Correcting team names**: 
  - "Delhi Daredevils" was changed to "Delhi Capitals".
  - "Royal Challenger Bangalore" was corrected to "Royal Challengers Bangalore".
  - "M Chinnaswamy Stadium, Bengaluru" TO "M Chinnaswamy Stadium"
  - ETC...

### Visualizations
The data was visualized using **Plotly Express** and **Plotly Graph Objects** to create interactive and insightful charts and graphs. These visualizations help in understanding the data trends and key metrics.

---

## 📚 **Project Overview**

In this analysis, we've explored IPL data (2008-2024) to answer the following 24 questions:

1. 🏟️ **Which stadium hosted the most matches (2008-2024)?**
2. 📈 **What is the total runs scored across seasons?**
3. 🤵 **Who is the umpire with the most number of umpiring appearances?**
4. 🎲 **Which team has won the most tosses in IPL seasons?**
5. 🎯 **Which decision was made after winning the toss?**
6. 📍 **What is the venue-wise toss-win match-win percentage?**
7. 🏆 **Which teams have won the most tournaments?**
8. ⚔️ **What is the total number of matches played and won by each team?**
9. 🍀 **What is the lucky venue for each team?**
10. 🤝 **How do teams perform head-to-head against each other?**
11. 🏅 **Who are the top 5 players with the highest runs?**
12. **Individual player performance analysis** for Virat Kohli:
    - **Kohli's Run Analysis**.
    - **Kohli's Dismissal Analysis**.
    - **Who takes Kohli's wicket most of the time?**
    - **Kohli's first and second innings comparison**.
    - **Kohli's runs against each team**.
    - **Kohli's favorite venue**.
    - **Kohli's runs by each season**.
13. 🎯 **Who is the highest wicket-taker?**
14. **Individual bowler performance analysis** for Yuzvendra Chahal:
    - **Dismissal type**.
    - **Favorite venue**.
    - **When is Chahal most effective?**
    - **Chahal’s wickets per season**.
    - **Total runs vs. total wickets per season**.
    - **Favorite batsman**.
15. 🏏 **Innings-wise run analysis by team:**
    - **First innings**.
    - **Second innings**.
16. 📊 **Which team has scored the most 200+ runs as a batting team and bowling team?**
17. 🥇 **Which team has won a match with the maximum result margin?**
18. 💯 **Which teams have won or lost with more than 100+ result margins?**
19. 🏏 **Which batsman has played the most number of balls?**
20. 🌟 **Who hit the most number of sixes?**
21. 🏅 **Who hit the most number of fours?**
22. 👕 **Which wicketkeeper has the most number of stumpings?**
23. ⚡ **Who has the highest strike rate during death overs?**
24. 🏆 **Who has won the most 'Man of the Match' awards?**

This project covers a wide range of insights, from match performance to individual player stats, helping us understand trends and patterns in IPL history. 🚀

---

## 🛠️ **Key Features**

### Stadium Insights
- **Top Stadium:** Wankhede Stadium hosted the highest matches (118).  
- **Venue Performance:** Venue-wise toss-win and match-win analysis included.

### Player Performance
- **Run Machine:** Virat Kohli leads with record-breaking 973 runs in 2016! 🧢  
- **Boundary King:** Chris Gayle rules with 359 sixes.  
- **Bowler's Delight:** Yuzvendra Chahal tops the charts with 205 wickets.

### Team Stats
- **Most Titles:** Chennai Super Kings and Mumbai Indians lead with 5 titles each.  
- **200+ Scores:** Chennai Super Kings have achieved 200+ scores 32 times.

### Special Highlights
- **Biggest Victory:** Mumbai Indians vs. Delhi Capitals, 146 runs in 2017.  
- **Stumping Master:** MS Dhoni leads with 42 stumpings.

---

## 📊 **Visualizations**

We used **Plotly Express** and **Plotly Graph Objects** to present the data interactively and effectively:

1. **Line Charts:**  
   - To visualize trends over time (e.g., total runs per season).  
   - **Library Used:** Plotly Express.

2. **Bar Graphs:**  
   - For comparisons like top players by runs or wickets.  
   - **Library Used:** Plotly Express.

3. **Pie Charts:**  
   - To show proportions (e.g., dismissal types, boundary contributions).  
   - **Library Used:** Plotly Express.

4. **Heatmaps:**  
   - To analyze venue performance and other correlations.  
   - **Library Used:** Plotly Graph Objects.

5. **Interactive Dashboards:**  
   - For deeper exploration of data trends.  
   - **Library Used:** Plotly Express & Plotly Graph Objects.

---

## 🔧 **How to Use the Project**

### Prerequisites
- Python 3.x
- Libraries:  
  `pandas`, `plotly`.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/IPL-EDA.git
