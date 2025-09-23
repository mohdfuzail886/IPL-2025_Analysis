# 🏏 IPL 2025 Data Analysis (Python)

## 📌 Project Overview
This project performs an in-depth analysis of the **Indian Premier League (IPL) 2025** dataset using Python.  
It explores matches, ball-by-ball data, players, venues, and performance trends to extract insights, visualize trends, and build baseline predictive models (e.g., match outcome prediction).

---

## 📂 Project Structure
ipl-2025-analysis/
├── data/ # Raw IPL 2025 datasets (matches.csv, ball_by_ball.csv, players.csv)
├── notebooks/
│ ├── 01-data-cleaning.ipynb
│ ├── 02-eda.ipynb
│ └── 03-modeling.ipynb
├── src/ # Utility scripts (data loaders, functions)
├── reports/
│ └── figures/ # Saved visualizations
├── requirements.txt
└── README.md

> ⚠️ **Note:** Raw data files are large and may not be included. Download from the sources below and place them inside the `data/` folder.

---

## 📊 Data Sources
- IPL 2025 Records – [Kaggle](https://www.kaggle.com/)  
- IPL Dataset 2008–2025 – [Kaggle](https://www.kaggle.com/)  
- GitHub IPL Dataset  
- ESPNcricinfo (for validation)

---

## ⚙️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/ipl-2025-analysis.git
cd ipl-2025-analysis

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Lab
jupyter lab

##📈 Analysis Highlights

✅ Season-wise Summary: Matches, winners, average runs/wickets

✅ Top Players: Batsmen (runs, strike rates), Bowlers (wickets, economy rates)

✅ Venue Analysis: Average scores, win percentages

✅ Toss Impact: Toss vs Match Outcome analysis

✅ Overs Breakdown: Powerplay, middle overs, death overs

✅ Predictive Modeling: Baseline match outcome prediction using ML

✅ Visualizations: Matplotlib, Seaborn, and Plotly

##🚀 Future Improvements

Build a live win probability model using ball-by-ball data

Deploy interactive dashboards with Streamlit or Power BI

Extend analysis across multiple IPL seasons (2008–2025)

##🏆 Credits

Data Sources: Kaggle, GitHub IPL Datasets, ESPNcricinfo

Purpose: Data Analysis portfolio project using Python
