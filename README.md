# Project-Meteorite-Landings-on-Earth-
Cosmic Landing Analytics
Cosmic Landing Analytics is a data-driven project that explores meteorite landing events using a comprehensive dataset from Data.gov (NASA). The project combines Python for data cleaning, exploratory data analysis (EDA), and predictive modeling with Power BI for interactive visualizations and KPI dashboards.

Overview
Dataset: Over 45,000 meteorite landing records, including details like mass, year, geographic coordinates, and classification.
Analysis Techniques:
EDA: Data cleaning, distribution analysis, temporal trends, and geospatial visualization.
Predictive Modeling: Regression models (Random Forest, Gradient Boosting, XGBoost, LightGBM) for predicting meteorite mass, and classification for determining if a meteorite was "Fell" or "Found".
Model Evaluation: Comparison using MAE, R² (for regression), and accuracy, precision, recall, and F1-score (for classification).
Key Insights
Mass Distribution:

Median Mass: ~32.6 grams
Average Mass: ~13,278 grams
Max Mass: 60,000,000 grams
These metrics reveal that while most meteorites are small, a few extreme outliers skew the average significantly.
Temporal Trends:

Increasing numbers of meteorite landings in recent years, likely due to improved detection and reporting.
Correlation Analysis:

Very weak correlation between meteorite mass and variables such as year, latitude, or longitude, indicating that mass is primarily driven by intrinsic factors.
Predictive Modeling:

XGBoost emerged as the best-performing regression model (MAE ~25,776 grams, R² ~ -0.0318), though overall performance is challenged by data variance.
High classification accuracy (~97.78%) for the dominant "Found" category, with room for improvement on the "Fell" class.
