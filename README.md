# Shipping a Data Product: From Raw Telegram Data to an Analytical API

## An end-to-end data pipeline for Telegram, leveraging dbt for transformation, Dagster for orchestration, and YOLOv8 for data enrichment.

# Project Structure

Telegram2API/
├── .github/workflows/ci.yml   # For CI/CD
├── data/                       # add this folder to .gitignore
│   ├── raw/                   # Raw data goes here 
│   └── processed/             # Processed data for training
├── notebooks/
│   └── README.md         
├── src/
│   └── __init__.py  
├── tests/
|   ├── __init__.py
│   └── test_sample.py         # Unit tests
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md

# Getting Started

Clone the repository

git clone http://github.com/tegbiye/Telegram2API.git

cd Telegram2API

Create environment using venv

python -m venv .telenv

Activate the environment

.telenv\Scripts\activate (Windows)

source .telenv\bin\activate (Linux / Mac)

Install Dependencies

pip install -r requirements.txt

📜 License This project is licensed un