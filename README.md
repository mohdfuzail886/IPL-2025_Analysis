🏏 IPL 2025 Data Analysis (Python)
📌 Project Overview

This project explores and analyzes the Indian Premier League (IPL) 2025 dataset using Python.
The analysis covers matches, ball-by-ball data, players, venues, and performance trends.
The goal is to extract insights, visualize trends, and build baseline predictive models (e.g., match outcome prediction).

📂 Project Structure
ipl-2025-analysis/
├── data/                  # Raw IPL 2025 datasets (matches.csv, ball_by_ball.csv, players.csv)
├── notebooks/
│   ├── 01-data-cleaning.ipynb
│   ├── 02-eda.ipynb
│   └── 03-modeling.ipynb
├── src/                   # Utility scripts (data loaders, functions)
├── reports/
│   └── figures/           # Saved visualizations
├── requirements.txt
└── README.md

📊 Data Sources

IPL 2025 Records (Kaggle)

IPL Dataset 2008–2025 (Kaggle)

GitHub IPL Dataset

ESPNcricinfo
 for validation

⚠️ Note: Raw data files are large and may not be included in this repo. Please download from the sources above and place inside the data/ folder.

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/yourusername/ipl-2025-analysis.git
cd ipl-2025-analysis

2. Create a virtual environment and install dependencies
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
pip install -r requirements.txt

3. Launch Jupyter Lab
jupyter lab

📈 Analysis Highlights

✅ Season-wise summary (matches, winners, average runs/wickets)

✅ Top batsmen & bowlers (runs, strike rates, wickets, economy rates)

✅ Venue performance analysis (average scores, win percentages)

✅ Toss vs Match Outcome analysis

✅ Powerplay, middle overs, and death overs breakdown

✅ Predictive modeling (baseline match outcome prediction using ML)

✅ Visualizations with Matplotlib, Seaborn, and Plotly

🚀 Future Improvements

🔹 Build a live win probability model from ball-by-ball data

🔹 Deploy dashboards with Streamlit / Power BI

🔹 Extend analysis across multiple seasons (2008–2025)

🏆 Credits

Data: Kaggle, GitHub IPL Datasets, ESPNcricinfo

Developed as part of a Data Analysis portfolio project using Python
