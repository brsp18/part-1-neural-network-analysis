# part-1-neural-network-analysis

# Dataset Source Link:
https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing


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

### Task 1: Dataset Understanding

Number of rows and columns           - print(df.shape)
Type of input features               - print(df.dtypes)
Target variable description          - print(df['churn'].decribe())
Missing value check                  - df.isnull().sum()  
Basic statistical summary            -
Distribution of the target variable  - (df['churn'].value_counts()) :  counts the churn column data
                                       (df['churn'].value_counts(normalize = True)*100) : provides the percentage of churned and unchurned data.churned(1),notchurned(0)


### Task 2: Data Preprocessing
Prepare the data for neural network training.

Handling missing values, if any 
Encoding categorical columns, if present
Scaling or normalizing numerical features
Splitting the dataset into training and testing sets

