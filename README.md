# 🧾 Hypothesis Testing on Taxi Fare vs. Payment Method

## 📘 Project Overview
This project analyzes whether **the mode of payment (Cash or Card)** has a **significant impact on taxi fare prices**.  
Using real or simulated taxi trip data, hypothesis testing was performed to determine if the difference in fare amounts between payment types is **statistically significant** or simply due to random chance.

---

## 🎯 Objective
To test whether **payment method influences taxi fare amount** using statistical methods such as:
- Exploratory Data Analysis (EDA)
- Visualization
- Hypothesis Testing (t-test or ANOVA)

---

## 🧩 Hypotheses

**Null Hypothesis (H₀):**  
> There is **no significant difference** in the mean taxi fare between cash and card payments.

**Alternative Hypothesis (H₁):**  
> There **is a significant difference** in the mean taxi fare between cash and card payments.

---

## 📊 Dataset Description
The dataset contains records of taxi trips with key attributes such as:

| Column Name | Description |
|--------------|-------------|
| `fare_amount` | Total fare charged for the trip |
| `trip_distance` | Distance of the trip (in miles/km) |
| `payment_type` | Type of payment used (e.g., Cash, Card) |
| `passenger_count` | Number of passengers |
| `store_and_fwd_flag` | Whether the trip data was stored and forwarded later |
| `pickup_datetime` | Trip start time |
| `dropoff_datetime` | Trip end time |

---

## 🔍 Analysis Performed

1. **Data Cleaning**
   - Removed missing or invalid values.
   - Filtered unrealistic fares or distances.

2. **Exploratory Data Analysis (EDA)**
   - Checked distributions of `fare_amount` by `payment_type`.
   - Visualized data using histograms and pie charts.
   - Analyzed correlation between
