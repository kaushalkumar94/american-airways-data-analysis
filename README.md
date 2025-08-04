# American Airways Customer Review Analysis

## Project Overview

This repository presents an end-to-end data analysis pipeline associated with American Airways. It consists of two primary workflows: analyzing structured booking data to uncover factors linked to flight booking completion, and performing customer review analysis using data scraped from review platforms. This enables actionable insights into both customer purchase behavior and post-travel feedback.

## Problem Statement

**American Airways Customer Review Analysis**

> The aim of this project is to analyze public customer reviews about American Airways to identify top drivers of satisfaction or dissatisfaction, and perform exploratory analysis on booking data to understand factors influencing flight booking completion. This will assist in improving both customer experience and booking conversion rates.

---

## File Descriptions

### 1. `customer_review_scraping_and_cleaning.ipynb`

- **Role:**  
  Automates the extraction (scraping) of customer reviews from an airline review website (e.g., airlinequality.com), then performs cleaning and preparation of the review text.
- **Main Steps:**
  - Collect customer review texts from the web.
  - Store reviews in a pandas DataFrame.
  - Clean the review text (remove unwanted tokens, standardize case, etc.).
- **Outcome:**  
  A cleaned dataset of customer reviews, ready for sentiment analysis, word frequency analysis, or further natural language processing (NLP).

---

### 2. `booking_data_eda_and_preprocessing.ipynb`

- **Role:**  
  Performs exploratory data analysis (EDA), cleaning, and feature preprocessing on structured airline booking data from American Airways.
- **Main Steps:**
  - Load and preview booking data with customer details and booking outcomes.
  - Summarize features (statistics, distribution, and missing values).
  - Prepare data (feature selection/encoding) for predictive modeling.
- **Outcome:**  
  A structured and well-understood dataset, ready for predictive modeling to determine which bookings are likely to complete.

---

## How To Use

- Open each notebook in Jupyter or your favorite compatible environment.
- For review analysis, run `customer_review_scraping_and_cleaning.ipynb` to obtain and clean customer reviews.
- For booking data, run `booking_data_eda_and_preprocessing.ipynb` to perform data exploration and necessary preprocessing.
- Use the processed data for deeper analytics such as sentiment analysis, predictive modeling, or dashboarding.

---

## Repository Structure

├── customer_review_scraping_and_cleaning.ipynb  

├── booking_data_eda_and_preprocessing.ipynb  

├── README.md


---

## Author

[Kaushal Kumar]

---


