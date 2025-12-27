# Product Recommendation System using ALS

## Project Overview
This project implements a scalable product recommendation system using the
Alternating Least Squares (ALS) algorithm on the Instacart Market Basket
Analysis dataset. Apache Spark is used to process large-scale data and
generate personalized recommendations.

## Dataset
Instacart Market Basket Analysis Dataset (Kaggle)

## Tools & Technologies
- Apache Spark
- Spark MLlib (ALS)
- Databricks Community Edition
- Python (PySpark)

## Methodology
1. Data ingestion and preprocessing
2. Construction of user-product interaction matrix
3. ALS model training using implicit feedback
4. Model evaluation using RMSE
5. Recommendation logic using prediction ranking

## Results
The ALS model achieved an RMSE of approximately 4.2, indicating good
prediction performance for implicit feedback data.

## Notes
Due to Unity Catalog restrictions in Databricks Community Edition,
top-N recommendation APIs could not be directly displayed. Recommendations
were derived by ranking predicted interaction scores.

## Author
Moosa Raza
