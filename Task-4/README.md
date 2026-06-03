# Task 4 - Sentiment Analysis

## Overview
This project performs Sentiment Analysis on customer reviews using Python. The reviews are classified into Positive, Negative, or Neutral sentiments using Natural Language Processing (NLP) techniques.

## Objective
The objective of this project is to analyze customer feedback and determine the sentiment expressed in each review.

## Tools & Libraries Used
- Python
- Pandas
- TextBlob
- Matplotlib

## Project Structure

Task-4-Sentiment-Analysis/
│
├── reviews.csv
├── sentiment_analysis.py
├── results.csv
├── sentiment_chart.png
└── README.md

## Dataset
The dataset contains customer reviews stored in a CSV file.

Example:

| Review |
|----------|
| Amazing product |
| Very bad service |
| Excellent quality |
| Not worth the money |
| Average experience |

## Methodology

1. Load customer reviews from CSV.
2. Analyze sentiment using TextBlob.
3. Classify reviews as:
   - Positive
   - Negative
   - Neutral
4. Save the results into a new CSV file.
5. Create a bar chart to visualize sentiment distribution.

## Output Files

### results.csv
Contains original reviews along with sentiment labels.

Example:

| Review | Sentiment |
|----------|----------|
| Amazing product | Positive |
| Very bad service | Negative |

### sentiment_chart.png
A bar chart showing the number of Positive, Negative, and Neutral reviews.

## Results
The model successfully classified customer reviews and generated a visual representation of sentiment distribution.

## Learning Outcomes
- Data Processing with Pandas
- Natural Language Processing (NLP)
- Sentiment Analysis using TextBlob
- Data Visualization using Matplotlib
- Working with CSV datasets in Python

## Author
Alex Raj

## Internship
CodeAlpha Data Analytics Internship