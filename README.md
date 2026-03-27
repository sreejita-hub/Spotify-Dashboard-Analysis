# Spotify-Dashboard-Analysis
Spotify data analysis dashboard using Google Sheets
# Spotify User Analytics Dashboard

## Project Overview

This dataset contains user activity and listening behavior data from Spotify. It is designed to analyze user engagement, subscription patterns, and music preferences. The dashboard helps in understanding trends in user activity, listening hours, and genre popularity.

---
![Dashboard](dashboard.png)
<img width="721" height="463" alt="Screenshot 2026-03-27 101238" src="https://github.com/user-attachments/assets/d1cd257e-6202-4ede-b01c-38f465d9686c" />

---

## File Details

* **Filename**: spotify_user_data.xlsx
* **Total Records**: Up to 5000 rows
* **Primary Keys**: User_ID

---

## Data Dictionary

| Column Name         | Description                     | Data Type   |
| ------------------- | ------------------------------- | ----------- |
| user_id             | Unique identifier for each user | Integer     |
| age                 | Age of the user                 | Integer     |
| subscription_type   | Free / Premium                  | Categorical |
| subscription_status | Active / Inactive               | Categorical |
| signup_date         | Date user joined                | Date        |
| avg_listening_hours | Average listening time per day  | Float       |
| favorite_genre      | User’s preferred music genre    | Categorical |

---

## Key Insights & Statistics

* Premium users spend more time listening
* Active users are higher than inactive users
* Popular genres include Pop, Bollywood, and Latin
* Listening hours vary significantly across age groups

---

## Analysis Suggestions

* **User Engagement**: Compare listening hours between Free and Premium users
* **Trend Analysis**: Use signup_date to track user growth
* **Behavior Analysis**: Study how age affects listening habits
* **Genre Popularity**: Identify most preferred genres

---

## Data Cleaning Notes

* Removed missing or null values
* Limited dataset to 5000 rows
* Formatted date column properly
* Created pivot tables for analysis

---

## Dashboard Features

* KPI Metrics (Total Users, Active Users, Avg Listening Hours)
* Subscription Analysis
* Genre Distribution
* Listening Hours Distribution
* Interactive Filters (Slicers)

---

## 🚀 Generated for Spotify Dashboard Analysis

