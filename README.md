# Bike Share Data Analysis Case Study

## Project Overview

This project analyzes Divvy Bike Share trip data to identify behavioral differences between annual members and casual riders.

The analysis was conducted as part of the Google Data Analytics Professional Certificate Capstone Project. The goal is to generate actionable insights that can help the marketing team develop strategies to convert casual riders into annual members.

---

## Business Task

Cyclistic's marketing team aims to increase the number of annual memberships by converting casual riders into members.

To support this objective, this analysis addresses the following business question:

**How do annual members and casual riders use bike-share services differently?**

---

## Dataset

The dataset used in this project is publicly available from Divvy Bike Share and contains trip-level records from November 2020 to November 2021.

### Data Source

https://divvy-tripdata.s3.amazonaws.com/index.html

### Dataset Features

The dataset includes information such as:

* Ride ID
* Rideable Bike Type
* Start and End Date/Time
* Start and End Stations
* Rider Type (Member or Casual)

---

## Tools and Technologies

* R
* RStudio
* tidyverse
* dplyr
* ggplot2
* lubridate

---

## Data Preparation

The following data-cleaning and preprocessing steps were performed:

* Imported and combined monthly trip datasets
* Inspected data structure and variable types
* Checked for missing values
* Removed invalid and incomplete records
* Converted date and time variables into appropriate formats
* Calculated ride duration
* Extracted day-of-week information
* Extracted monthly information for trend analysis

---

## Feature Engineering

Several new variables were created to support analysis and visualization.

### Ride Duration

Calculated the duration of each trip to compare riding behavior between rider groups.

### Day of Week

Extracted weekday information to analyze riding patterns throughout the week.

### Month

Extracted monthly information to investigate seasonal usage trends.

---

## Exploratory Data Analysis

The analysis focused on the following areas:

### Ride Frequency by Day of the Week

Examined how riding activity varies throughout the week for members and casual riders.

### Distribution of Rideable Bike Types

Compared bike type preferences between rider groups.

### Monthly Ride Trends

Analyzed seasonal fluctuations in bike-share usage.

### Distribution of Ride Duration

Compared trip duration patterns between annual members and casual riders.

### Member vs Casual Riders

Evaluated the overall distribution of rider types within the dataset.

---

## Key Findings

### Casual Riders Take Longer Trips

Casual riders generally have longer ride durations compared to annual members.

### Members Ride More Consistently

Annual members demonstrate more consistent riding behavior throughout the week.

### Casual Riders Prefer Weekend Usage

Casual riders show higher riding activity during weekends, suggesting greater recreational usage.

### Seasonal Trends Influence Usage

Bike-share usage increases during warmer months and decreases during colder periods.

### Differences Exist in Bike Type Preferences

The analysis indicates variations in bike type selection between rider groups.

---

## Recommendations

Based on the findings, the following recommendations are proposed:

1. Develop targeted membership promotions for frequent casual riders.
2. Launch weekend-focused membership campaigns.
3. Offer incentives encouraging casual riders to transition to annual memberships.
4. Create personalized marketing strategies based on rider behavior and usage patterns.

---

## Repository Structure

bike-share-analysis/

├── data/

├── scripts/

├── visualizations/

└── README.md

---

## Visualizations

The repository includes the following visualizations:

* Ride Frequency by Day of the Week
* Distribution of Rideable Bike Types
* Monthly Ride Trends
* Distribution of Ride Duration
* Member vs Casual Riders

---

## Author

**Sneha Pirahalathan**

Applied Statistics Graduate

Aspiring Data Analyst

