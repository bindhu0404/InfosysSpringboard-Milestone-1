# Milestone 1  
### Customer Feedback Data Collection & Text Preprocessing

## Project Overview
ReviewSense is a customer feedback analysis project aimed at extracting meaningful insights from raw customer reviews.  
This repository contains **Milestone 1**, which focuses on **data ingestion and text preprocessing**.

The goal of this milestone is to clean noisy real-world customer feedback and prepare it for further analysis such as:
- Sentiment Analysis
- Topic Modeling
- Trend Detection
- Data Visualization

---

## Milestone 1 Objective
- Load customer feedback data from CSV or Excel files  
- Clean and preprocess textual feedback  
- Remove noise such as URLs, numbers, punctuation, and stopwords  
- Generate a clean, analysis-ready CSV file  

---

## Technologies Used
- **Python**
- **Pandas** – for data handling
- **Regular Expressions (re)** – for text cleaning
- **String module** – for punctuation removal

---

## Text Cleaning Steps
The preprocessing pipeline performs the following operations:
1. Converts text to lowercase  
2. Removes URLs  
3. Removes numbers  
4. Removes punctuation  
5. Removes extra whitespaces  
6. Removes common stopwords  
7. Produces clean and meaningful text 
