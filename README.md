Overview

Project Samarth is an intelligent Q&A prototype built for the Bharat Digital Fellowship Challenge.
The goal is to make data from data.gov.in — especially agricultural and climate datasets — accessible through a natural language chat interface.
Users can ask complex questions, and the system fetches and combines real data to provide clear, cited insights.

🌾 Problem Statement

Government portals like data.gov.in host thousands of valuable datasets from multiple ministries.
However, the data exists in different formats, structures, and code values, making it hard for policymakers and researchers to find cross-domain insights.
Project Samarth solves this by connecting agricultural data (like crop production, yield) with climate data (like rainfall, temperature).

💡 Features

Natural Language Query Understanding

Intelligent Dataset Selection (agriculture + climate)

Dynamic Data Cleaning & Integration

Result Explanation with Source Citations

Lightweight Web Interface (Streamlit-based prototype)

⚙️ System Design (Prototype Architecture)

Frontend: Streamlit UI for asking natural language questions.

Backend Logic:

Uses Python with Pandas for data handling.

NLP pipeline (using spaCy or transformers) to interpret the question.

Logic layer identifies relevant datasets from data.gov.in.

Data Sources:

Ministry of Agriculture & Farmers Welfare datasets (crop production, yield).

India Meteorological Department (IMD) datasets (rainfall, temperature).

Output:

Answer generated in simple text format with dataset citations.

🧩 Example Questions

Compare rainfall in Maharashtra and Gujarat for the last 5 years and list top crops.

Identify the district with highest rice production in Tamil Nadu.

Correlate sugarcane yield with rainfall trend in Uttar Pradesh.

🔗 Demo & Repository

Prototype under development.
This repository will soon include the working Streamlit demo and dataset integration code.


Created by

Nagesh Awachar
MCA Student | Data Science Enthusiast 
