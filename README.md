# Football Player Analysis: Emotion, Sentiment, and Performance Prediction

## Problem Context
Professional footballers often face intense criticisms that can negatively impact their performance and mental health. To address this challenge, our project focuses on analyzing online sentiments, predicting player performance, and identifying excessive criticism. This initiative aligns with FIFPro’s mission to enhance player welfare.

## Overview
This repository implements an end-to-end data science pipeline that combines machine learning, natural language processing, and sentiment analysis to evaluate both **player performance** and **public perception**. We draw data from:
- **Reddit Posts** (scraped with PRAW)
- **PDF Text** (extracted and cleaned)
- **Audio Files** (converted from MP3 to WAV)
- **FIFA Player Stats** (for condition classification)

**Key Components:**
- **Emotion Recognition:** Process facial expressions from PDF images.
- **Player Performance Prediction:** Predict ratings and market values using Linear Regression, Random Forest, and SVR.
- **Player Condition Classification:** Categorize players into conditions (super, good, normal, bad, awful) with an SVM model.
- **Sentiment Analysis:** Analyze text sentiment with VADER, focusing on Reddit discussions about players.
- **Data Acquisition & Preprocessing:** Automate web scraping, audio conversion, and text cleaning/tokenization.
![images](https://github.com/user-attachments/assets/bd739590-2513-44ab-b772-0a3971444d1c)
![web scraping pipeline](https://github.com/user-attachments/assets/a2396cc9-c882-4e21-838a-26381224ec73)
![1A_FIFPRO_PrimaryLogo_Portrait-320x267](https://github.com/user-attachments/assets/a2e77a0a-b56b-4a7d-bb6b-4ae282574a6b)
![machine learning pipeline](https://github.com/user-attachments/assets/8de344c0-c3be-4226-8374-f62cf351f357)
