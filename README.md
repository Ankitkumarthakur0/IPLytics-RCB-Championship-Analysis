#  IPLytics – RCB Championship Analysis

## Introduction

IPLytics is an end-to-end Data Science and Sports Analytics project designed to analyze Royal Challengers Bengaluru's historic IPL 2025 championship-winning campaign and their subsequent qualification to the IPL 2026 Final.

This project was created to answer a fundamental sports analytics question:

**"What were the key factors behind RCB's transformation from a historically inconsistent team into a championship-winning and title-contending side?"**

Unlike traditional analytics projects that rely on publicly available datasets, IPLytics follows a real-world analytics workflow where match-level datasets were manually collected, structured, cleaned, and analyzed before applying statistical and machine learning techniques.

The project combines sports analytics, exploratory data analysis, data visualization, and machine learning to uncover meaningful insights into team performance, consistency, venue impact, opponent matchups, and winning patterns.

---

# Problem Statement

Sports teams generate massive amounts of performance data, but raw match statistics alone do not explain why a team succeeds or fails.

The primary objective of IPLytics is to:

* Understand the factors that contributed to RCB's IPL 2025 championship victory.
* Compare RCB's performance across IPL 2025 and IPL 2026.
* Identify performance trends across different venues and opponents.
* Measure consistency and match-winning efficiency.
* Develop predictive models capable of classifying match outcomes based on historical data.
* Build a foundation for future advanced sports intelligence systems.

---

# Project Workflow

The project follows a complete Data Science lifecycle:

```text
Business Problem
       ↓
Data Collection
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
Exploratory Data Analysis
       ↓
Visualization
       ↓
Machine Learning
       ↓
Performance Evaluation
       ↓
Sports Intelligence
```

---

# Dataset Development

One of the unique aspects of this project is that the dataset was not downloaded from Kaggle or any pre-built repository.

### Data Collection Process

* Manually collected IPL 2025 match data.
* Manually collected IPL 2026 match data.
* Structured match records into CSV datasets.
* Standardized team, venue, score, and result information.
* Combined multiple seasons into a unified analytics dataset.

### Dataset Features

| Feature        | Description             |
| -------------- | ----------------------- |
| Date           | Match Date              |
| Opponent       | Opposing Team           |
| Venue          | Match Venue             |
| RCB Score      | Runs scored by RCB      |
| Opponent Score | Runs scored by opponent |
| Result         | Win / Loss              |
| Season         | IPL Season              |

---

# Exploratory Data Analysis (EDA)

Several exploratory analyses were performed to understand performance patterns.

### Match Outcome Analysis

* Total Matches Played
* Total Wins
* Total Losses
* Win Percentage

### Venue Analysis

* Best Performing Venues
* Worst Performing Venues
* Average Runs by Venue
* Venue Win Percentage

### Opponent Analysis

* Strongest Opponents
* Weakest Opponents
* Head-to-Head Performance

### Consistency Analysis

* Match-to-Match Performance Stability
* High-Scoring Match Trends
* Winning Momentum Analysis

---

# Data Visualization

Visualization played a critical role in understanding trends and communicating insights.

Implemented visualizations include:

* Win/Loss Distribution
* Season Comparison Charts
* Venue Performance Analysis
* Opponent Comparison Analysis
* Score Distribution Charts
* Team Consistency Trends

Libraries Used:

* Matplotlib
* Seaborn

---

# Machine Learning Approach

The project incorporates supervised machine learning techniques to classify match outcomes.

### Objective

Predict whether RCB wins or loses based on historical match information.

### Machine Learning Workflow

1. Data Preparation
2. Feature Selection
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Prediction
7. Model Evaluation

### Algorithms Used

* Logistic Regression

### Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Performance Analysis
* Feature Importance Evaluation

### Results

* Successfully trained a match outcome classification model.
* Achieved approximately **83% prediction accuracy** on the available dataset.
* Identified influential features affecting match outcomes.

---

# Key Insights Generated

The analysis revealed several important observations:

### Performance Trends

* RCB displayed significantly improved consistency during IPL 2025.
* Performance stability contributed to deeper tournament progression.
* Certain venues demonstrated stronger win rates than others.

### Opponent Intelligence

* RCB performed better against specific opponents.
* Certain teams consistently posed greater challenges.

### Strategic Observations

* Match-winning performances were associated with stronger batting outputs.
* Consistent scoring patterns were correlated with higher win percentages.

---

# Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

### Development Tools

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

# Project Structure

```text
IPLytics-RCB-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│       ├── rcb_2025_matches.csv
│       ├── rcb_2026_matches.csv
│       └── combined_rcb_dataset.csv
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_data_analysis.ipynb
│   └── 04_machine_learning_model.ipynb
│
├── visualizations/
│
├── models/
│   └── rcb_match_prediction_model.pkl
│
└── README.md
```

---

# Future Enhancements

The current project establishes a strong analytics foundation. Future improvements include:

### Advanced Analytics

* Powerplay Intelligence
* Death Overs Analysis
* Batting Partnership Analysis
* Momentum Analysis

### Dashboard Development

* Interactive Streamlit Dashboard
* Real-Time Filtering
* Dynamic Visualizations

### Machine Learning Enhancements

* Random Forest Classifier
* XGBoost Models
* Match Probability Prediction
* Tournament Simulation Models

### Data Engineering

* Automated Data Collection Pipeline
* SQL Database Integration
* API-Based Data Ingestion

---

# Author

**Ankit Kumar**

Aspiring Data Scientist | Machine Learning Enthusiast 

This project represents a practical implementation of Data Science concepts, including data collection, preprocessing, exploratory analysis, visualization, machine learning, and performance intelligence within the sports analytics domain.

If you found this project useful, consider giving it a star.
