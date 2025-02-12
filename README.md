# airline_data_simulated
This repository contains a comprehensive project that simulates a dataset related to airline operations and passenger data. The dataset was simulated using ChatGPT and subsequently analyzed through various stages of data cleaning, manipulation, and feature engineering. The next step in the analysis will involve applying Unsupervised Learning algorithms to uncover hidden patterns within the data.
## Overview
The dataset includes detailed flight-related information such as flight numbers, passenger counts, wait times, feedback, and other features relevant to the airport industry. This project serves as a practical exercise to clean and prepare data for machine learning models, with a focus on handling real-world dirty data problems.
## Key Features:
Flight Information: Flight number, day, date, and flight status (e.g., "On Time", "Delayed")
Passenger Details: Passenger class (Economy, Business, First Class), total passengers
Wait Times: Time spent waiting at the gate, including missing and inconsistent data
Monetary Data: Currency values with different currencies (USD, EUR, GBP, etc.)
Temperature Data: Inconsistent temperature units (Celsius and Fahrenheit)
Customer Feedback: Unstructured text data on passenger experiences
I’ve performed a series of data cleaning steps to prepare the dataset for analysis. Key steps include:

1. Data Cleaning:
Inconsistent Formats: Standardized inconsistent date formats, currency symbols, and temperature units (°C and °F).
Missing Data: Identified and handled missing values using various techniques like imputation and deletion.
Cross-Field Validation: Addressed inconsistencies between related fields (e.g., total_passengers vs. the sum of economy_class, business_class, and first_class).
Whitespace & Capitalization Issues: Cleaned category labels to ensure uniformity (e.g., Flight status and airline columns).
Outliers: Detected and removed outliers that may negatively affect analysis or predictions.
## Next steps
The next phase of this project will involve feature engineering and  Unsupervised Learning to identify patterns, clusters, and anomalies within the dataset
##key learning
understanding data needs and real world scenarios is important, this will help you improve your prompts to chatgpt inorder to have a representative dataset
