# part-1-neural-network-analysis

# Dataset Source Link:
https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing

C:\Users\brswe\Downloads\may_2026_assignment\ai_project_synthetic_datasets\part_1_neural_network_analysis\customer_churn_nn.csv

# Part 1 Dataset: Customer Churn Neural Network Dataset

## File
`customer_churn_nn.csv`

## Goal
Build a neural network model to predict whether a customer is likely to churn.

## Target Column
- `churn`: 1 = customer churned, 0 = customer retained

## Feature Notes
- Categorical columns: `region`, `plan_type`, `contract_type`, `payment_method`
- Numerical columns: tenure, charges, login days, tickets, delays, data usage, satisfaction, complaint recency, discounts, referrals
- `customer_id` is an identifier and should not be used as a predictive feature.