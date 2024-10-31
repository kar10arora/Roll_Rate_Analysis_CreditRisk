This project performs essential checks on the credit portfolio data to ensure accuracy and completeness. 
It utilizes both the Snapshot Method and the Month on Books (MOB) Method to analyze account transitions across delinquency stages. 
The Snapshot Method captures the state of accounts at specific intervals, while the MOB Method segments accounts based on their age since origination.

Using the transition matrix generated from these methods, the project visualizes the roll rate analysis to provide insights into the 
movement of accounts between delinquency categories over time. 
This comprehensive approach aids in understanding credit risk dynamics and identifying trends for proactive risk management.
--> Features
Roll rate calculation for tracking delinquency transitions.
MOB analysis for evaluating delinquency patterns over account age.
Data preprocessing and feature engineering scripts.
Visualizations for roll rates, delinquency distributions, and MOB trends.
-->  Data Requirements
For effective analysis, the dataset should contain the following fields:
account_id: Unique identifier for each account.
date: Observation date.
origination_date: The date when the account was opened.
delinquency_status: Status of the account in terms of delinquency stages (e.g., Current, 30 Days, 60 Days, etc.).
balance: (Optional) Account balance, if available, for deeper analysis.
