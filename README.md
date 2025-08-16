# Uber-Data-Analytics
ETL pipeline and analytics dashboard for Uber data using GCP &amp; Mage.
🚖 Uber Data Analytics | Modern Data Engineering on GCP
📌 Introduction

This project demonstrates how to build an end-to-end data engineering pipeline for Uber trip data using modern tools and Google Cloud Platform (GCP). The workflow covers data ingestion, transformation, warehouse modeling, and dashboard visualization to generate insights from real-world NYC TLC Trip Record Data.

🏗️ Architecture
<img src="architecture.jpg" alt="Architecture" width="600">
🛠️ Technology Stack
Programming

Python – ETL scripting, data processing

Google Cloud Platform

Google Cloud Storage – raw data storage

Compute Engine – virtual machine for running Mage pipelines

BigQuery – data warehouse & SQL analytics

Looker Studio – interactive dashboards and visualizations

Modern Data Pipeline Tool

Mage – open-source orchestration tool for building, running, and managing pipelines

Contribute here: mage-ai/mage-ai

📂 Dataset

The project uses NYC TLC Trip Record Data (Yellow and Green Taxi Trips), which includes:

Pick-up and drop-off dates/times

Pick-up and drop-off locations

Trip distances

Itemized fares

Rate types & payment methods

Passenger counts

🔗 Sample dataset used in this project:
uber_data.csv

📖 More info:

TLC Trip Record Data Website

Data Dictionary (Yellow Taxi)

🗄️ Data Model
<img src="data_model.jpeg" alt="Data Model" width="600">
🎯 Project Workflow

Data Ingestion – Load raw TLC data into Google Cloud Storage

Data Transformation – Clean and preprocess data with Mage pipelines

Data Warehousing – Store transformed data in BigQuery

Analytics & Visualization – Create interactive dashboards in Looker Studio

📊 Dashboard Example

(Insert screenshot of Looker Studio dashboard here for better presentation)

▶️ Complete Tutorial

🎥 Watch the Full Video Walkthrough

🤝 Contributing

Contributions are welcome! If you’d like to enhance the project, feel free to:

Open an issue

Submit a pull request

Explore and contribute to Mage, the core pipeline tool used here

📜 License

This project is licensed under the MIT License – feel free to use, modify, and share.
