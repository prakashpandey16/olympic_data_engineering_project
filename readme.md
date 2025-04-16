# Olympic Data Analytics Project

## Overview
The **Olympic Data Analytics Project** focuses on performing comprehensive data analysis using Olympic data, structured around the **Medallion Architecture** (Bronze, Silver, and Gold layers). This architecture enables efficient data processing, cleaning, transformation, and aggregation using **Databricks** and **PySpark**. The goal of the project is to visualize key insights and build a scalable, efficient data pipeline for Olympic datasets.

## Project Structure

### Directory Structure
```bash
Olympic-Data-Analytics-Project/
│
├── data/
│   ├── athletes.csv                  # Raw data on athletes
│   ├── coaches.csv                   # Raw data on coaches
│   ├── entries_gender.csv            # Raw data on gender-based entries
│   ├── medals.csv                    # Raw data on medals won
│   ├── teams.csv                     # Raw data on Olympic teams
│   └── ...                           # Additional raw datasets for analysis
│
├── scripts/
│   ├── bronze_layer/
│   │   ├── ingest_data.py            # Script to ingest raw datasets into the system
│   │   ├── bronze_layer.ipynb        # Jupyter Notebook for initial data ingestion and exploration
│   │   └── ...                       # Additional scripts for data ingestion and initial processing
│   ├── silver_layer                 # Script to clean and transform data
│   │   ├── silver_layer.ipynb        # Jupyter Notebook for data transformation and cleaning
│   │   └── ...                       # Additional scripts for data cleaning and transformation
│   ├── gold_layer/       # Script to aggregate data and generate insights
│   │   ├── gold_layer.ipynb          # Jupyter Notebook for final data analysis and reporting
│   │   └── ...                       # Additional scripts for data analysis and final reports
│
└── README.md                         # Project documentation and overview


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

I'm Prakash Pandey, a BCA student who is passionate about Data Engineering, building real-world data solutions, and solving business problems with technology.

- 🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/prakash-pandey-884590263/)
