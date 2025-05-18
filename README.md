🌞 Solar Challenge - Week 1
This project is part of the MoonLight Energy Solutions challenge. It sets up a Python environment and Continuous Integration workflow to prepare for data analysis and engineering work.

🛠 How to Reproduce the Environment
Follow these steps to set up the project locally:

1. Clone the repository
git clone https://github.com/Tewodros7/solar-challenge-week1.git
cd solar-challenge-week1

2. Create and activate a virtual environment

# Create virtual environment
python -m venv .venv

# Activate it (on Windows)
.venv\Scripts\activate

# Activate it (on macOS/Linux)
source .venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

What's in This Repo
solar-challenge-week1/
│
├── .github/
│   └── workflows/
│       └── ci.yml             # GitHub Actions CI file
│
├── .gitignore                 # Ignores data, .venv, etc.
├── requirements.txt           # Python dependencies
├── README.md                  # This file!
├── notebooks/                 # For Jupyter Notebooks
├── src/                       # Source code will go here
├── tests/                     # For unit tests
└── scripts/                   # Utility scripts

✅ Features
Git & GitHub project setup

Python virtual environment with requirements.txt

GitHub Actions for Continuous Integration (CI)

Clean folder structure 
