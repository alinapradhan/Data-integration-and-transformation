# Data-integration-and-transformation
# Data Integration and Data Transformation for Data Mining

This project demonstrates core techniques in **data preprocessing**, focusing on integration and transformation tasks often required before data mining or machine learning.

## Project Overview

The notebook covers:

-  **Data Integration**
  - Tight Coupling (inner join on common keys)
  - Loose Coupling (concatenation)
  
-  **Data Transformation**
  - Smoothing using rolling averages
  - Aggregation by groups (e.g., sum of salaries by gender)
  - Discretization (binning continuous data into categories)
  - Attribute Construction (deriving new features)
  - Normalization:
    - Min-Max Normalization
    - Z-score Normalization
    - Decimal Scaling

##  Sample Datasets

Two small synthetic datasets are used:

1. **Personal Info** (ID, Name, Age)
2. **Employment Info** (ID, Gender, Salary)

These are integrated and transformed using `pandas` and `numpy`.

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/data-integration-transformation.git
   cd data-integration-transformation
