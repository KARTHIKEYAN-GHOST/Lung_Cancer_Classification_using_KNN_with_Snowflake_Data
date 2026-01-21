# Lung Cancer Classification using KNN with Snowflake Data

This project demonstrates how to integrate **Snowflake cloud data** with a **machine learning classification model** in Python.  
A K-Nearest Neighbors (KNN) classifier is trained to predict lung cancer outcomes using patient data fetched directly from a Snowflake database.

The project is intended for **learning and demonstration purposes**, focusing on database connectivity, preprocessing, and basic model training.

---

## Objective

To retrieve healthcare-related data from Snowflake and use it to predict the presence of lung cancer using a KNN classifier.

---

## Data Source

- **Platform:** Snowflake
- **Table:** `CANCER`
- **Query:**  
  ```sql
  SELECT * FROM "CANCER" LIMIT 5;
