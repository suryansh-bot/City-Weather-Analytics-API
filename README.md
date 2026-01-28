# Day 5 Capstone – City Weather Analytics Service

## Project Overview
This project is a data processing and analytics service that combines static city data with real-time weather information and exposes insights through REST APIs.  
The pipeline fetches weather data from the OpenWeather API, cleans and transforms city-level data, and serves the processed results using FastAPI.

---

## Tech Stack
- Python
- Pandas
- FastAPI
- Requests
- Pytest
- OpenWeather API

---

## Project Structure
day5-capstone/
├── data/
│ ├── raw/
│ │ └── worldcities.csv
│ └── processed/
│ └── merged_data.csv
│
├── src/
│ ├── api_client.py
│ ├── data_loader.py
│ ├── data_cleaner.py
│ ├── transformer.py
│ ├── pipeline.py
│ └── app.py
│
├── tests/
│ ├── test_cleaner.py
│ └── test_transformer.py
│
├── requirements.txt
├── .env
└── README.md

