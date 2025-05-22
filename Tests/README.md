# 🌞 Solar Data Discovery - Week 0 Challenge
This repository contains my submission for the Week 0 Challenge of the  10 Academy Artificial Intelligence Mastery (AIM) program. The project explores solar farm data from Benin, Sierra Leone, and Togo to identify high-potential regions for solar energy investment.

# 🎯 Project Objective
The goal is to analyze environmental measurements and deliver data-driven insights to MoonLight Energy Solutions, helping the company identify optimal locations for solar energy deployment while aligning with sustainability and impact goals.

# ✅ Tasks Completed
   # Task 1: Git & Environment Setup
Initialized GitHub repository with a clean folder structure.

Created a Python virtual environment and documented dependencies.

Configured GitHub Actions for basic CI.

Added detailed environment setup instructions in the README.

   # Task 2: Data Profiling, Cleaning & EDA
Conducted Exploratory Data Analysis (EDA) per country:

Summary statistics, missing data analysis, outlier detection.

Time-series exploration and the impact of data cleaning on sensor outputs.

Visualizations including correlation matrices, scatter plots, wind roses, and bubble charts.

Exported cleaned datasets as data/<country>_clean.csv.

   # Task 3: Cross-Country Comparison
Compared solar irradiance metrics (GHI, DNI, DHI) across the three countries:

Boxplots, descriptive summaries, and ANOVA test results.

Highlighted insights and differences in solar energy potential.

   # Task 4: Interactive Dashboard
Built an interactive dashboard using Streamlit for real-time exploration:

Detailed country-specific analytics and trends.

Cross-country comparison tools.

Dynamic plots for GHI, DNI, DHI with time-series and correlation analysis.

🔗 Live Dashboard Access → Solar Challenge Dashboard
(Insert actual link if available)

# 📸 Dashboard Snapshots
   # 📍 Country Analysis
In-depth metrics and trends for each country.

# 🌍 Cross-Country Comparison
Visual comparison of solar energy potential across Benin, Sierra Leone, and Togo.

# 📊 Interactive Visualizations
Correlation tools and time-series plots for solar irradiance components.

# 🛠️ Getting Started
Follow these steps to set up the project locally:

# 1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/DagmMesfin/solar-challenge-week1.git
cd solar-challenge-week1
# 2. Set Up a Virtual Environment
🔁 Linux/macOS:
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
🔁 Windows:
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate
# 3. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
# 📂 Project Structure Highlights
notebooks/: Jupyter notebooks for data analysis and visualization.

data/: Raw and cleaned datasets.

dashboard/: Streamlit app source files.

.github/workflows/: CI configuration with GitHub Actions.

requirements.txt: Python dependencies list.
