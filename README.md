# ✈️ Flight Delay Analysis and Prediction 

This project explores the **nycflights13** dataset to understand the causes of flight delays and build predictive models using statistical and machine learning techniques.

---

## 📘 Course Info

**Course**: STAT 232 – Statistics for Business Analytics  
**Instructor**: Prof. Wenxiu Ma  
**University**: University of California, Riverside
---

## 📂 Repository Contents

| File Name                        | Description |
|----------------------------------|-------------|
| `Project_Report.pdf`            | Final project report detailing EDA, modeling, and results |
| `PPT_Project_Progress_Report.pdf` | Progress presentation with intermediate findings |
| `Project_Proposal_with_R_Code.pdf` | Initial project proposal with exploratory R code |
| `R_Code.Rmd`                    | R Markdown script used for data analysis and modeling |
| `README.md`                     | You're reading it! |

---

## 🧠 Project Objective

To identify key contributors to flight delays and build predictive models to forecast delay durations using flight schedule, airport, and carrier information.

---

## 🔍 Research Questions

1. How do departure times impact delays?
2. Which airports and airlines experience the highest delays?
3. What role does weather or seasonality play?
4. Can we accurately predict flight delays using machine learning?

---

## 🧪 Methodology

- **Exploratory Data Analysis (EDA)**  
  Delay trends by airport, airline, time of day, etc.

- **Statistical Modeling**  
  Quadratic Regression to model non-linear relationships

- **Machine Learning Models**  
  - Random Forest Regression  
  - Gradient Boosting (GBM)  
  - Neural Networks (planned extension)

- **Model Evaluation Metrics**  
  - MAE (Mean Absolute Error)  
  - RMSE (Root Mean Squared Error)  
  - R² (R-squared)

---

## 📌 Key Insights

- Departure time and airport play a significant role in delays but explain only ~5–9% of variation.
- Newark (EWR) and Chicago O'Hare (ORD) had the longest average delays.
- Airlines differ significantly in their delay performance (e.g., Alaska Airlines had the fewest delays).
- Current models perform modestly (R² ≈ 0.09) — weather and traffic data may improve predictions.

---

## 🧰 Tools & Technologies

- **Language**: R  
- **Libraries**: `nycflights13`, `ggplot2`, `randomForest`, `dplyr`, `caret`  
- **Data**: All 2013 flights departing from NYC

---

## 🚀 Future Work

- Incorporate weather and aircraft data to boost prediction accuracy
- Classify high-risk flights using classification models
- Visualize delay trends on interactive dashboards

---

## 📄 License

This repository is for educational use only.
