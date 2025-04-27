# Transaction-Anomaly-Detection-System
Overview
A comprehensive fraud detection analytics project that leverages machine learning and statistical analysis to identify anomalous patterns in payment transactions. This system analyzes transaction metadata to flag potentially fraudulent activities in real-time.
Project Description
The Transaction Anomaly Detection System aims to enhance payment security in the rapidly growing digital economy. With the increasing volume of online transactions, identifying fraudulent patterns has become critical for businesses and financial institutions.
This project analyzes a dataset of 200,000 payment transactions to uncover fraud patterns, transaction trends, and anomaly indicators. Using Python and various data science libraries, I've developed a robust analytical framework that can detect suspicious activities based on multiple dimensions:

Transaction amount analysis
Payment method patterns
Device-based risk assessment
Geographical distribution analysis
Temporal behavior patterns

Key Findings

Fraud Rate: 1.04% of transactions flagged as fraudulent
Payment Methods: UPI dominates (54.1%), followed by Wallet (29.4%), with higher fraud vulnerability in mobile transactions
Transaction Patterns: Fraudulent transactions tend to have higher values (avg. ₹2,034.80) compared to legitimate ones
Device Analysis: Mobile platforms show higher fraud rates than web or tablet interfaces
Temporal Patterns: Transaction volumes peak on Thursdays and between 11 AM-1 PM

Technology Stack

Programming Language: Python
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Statistical Analysis: SciPy
Machine Learning: Scikit-learn

Future Development Goals

Implement real-time transaction scoring
Develop user behavior profiles for enhanced anomaly detection
Create an interactive dashboard for monitoring fraud patterns
Expand the model to incorporate more payment channels
Integrate natural language processing for transaction description analysis

Dataset
The analysis is based on a diverse dataset of 200,000 payment transactions across multiple payment methods, geographical locations, and device types, containing both legitimate and fraudulent activities.
