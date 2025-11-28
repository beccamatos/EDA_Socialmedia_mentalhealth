# EDA_Socialmedia_mentalhealth
This repository contains a complete exploratory data analysis (EDA) of how social media use, screen time, stress, sleep quality, and lifestyle habits relate to overall mental well-being.
The project includes data cleaning, visualization, statistical insights, and reproducible R code.

## Objectives
The goal of this project is to:
- Understand patterns in mental health and digital habits
- Explore correlations between screen time, stress, sleep, and lifestyle
- Create clear and reproducible visualizations
- Evaluate sample distributions and identify any data issues
- Prepare high-quality plots 

## Tools & Technologies

- R
- tidyverse
- data.table
- ggplot2
- dplyr

## Key Analyses Performed

### Age × Gender Boxplot
Shows median ages per gender
Observations:
Male median age ≈ 33

Female median age ≈ 35

Other ≈ 27 (sample too small → category removed for analysis)

## Histograms (Screen Time, Stress, Sleep)
Explanation of shape, symmetry, peaks, outliers

Interpretation

## Line Plot: Exercise × Days Offline
Mean trend line

Point-wise visualization

## Correlation Heatmap (Python → R equivalent)
Sleep ↔ Stress

Screen time ↔ Sleep

Screen time ↔ Stress

Annotated heatmap with correlation coefficients\

## Summary of Insights
- Higher screen time tends to correlate with lower sleep quality.
- Stress level increases with screen time in most cases.
- People who exercise more frequently usually take more breaks from social media.
- Gender distribution for analysis must be adjusted due to extremely small Other sample size.

# Getting Started

Follow these steps to set up and run the full Ratio pipeline.

1) Project Setup

Clone the repository and enter the project directory:

git clone https://github.com/beccamatos/EDA_Socialmedia_mentalhealth.git
cd EDA_Socialmedia_mentalhealth

Place required CSV inputs in input/:

input/Mental_Health_and_Social_Media_Balance_Dataset.csv (required)

2) Manual Execution

Run the script:

Rscript "script/EDA_socialmedia_mentalhealth.Rmd"
