# Patient Pathway Analysis (KNIME Workflow)

## Objective
This project analyzes patient diagnostic test data to uncover trends in testing volume and costs over time, and city-wise distributions.

## Workflow
![Workflow Screenshot](images/Diagnosis.png, Monthly Trend of Test Counts and costs.png,Total Sum Distribution by City.png
## Steps
1. Load patient and test data (CSV Readers).
2. Join patient and test datasets.
3. Convert date fields and extract Year-Month.
4. Group data to compute monthly summaries.
5. Visualize trends in:
   - Line Plot → monthly test counts and costs.
   - Bar Chart → city-wise test costs.
   - Pie Chart → distribution of tests across cities.

## Outputs
- **Line Plot**: Monthly trends of test counts and costs.
- **Bar Chart**: City-wise cost comparison.
- **Pie Chart**: Percentage distribution across cities.

