# Patient Pathway Analysis (KNIME Workflow)

## Objective
This project analyzes patient diagnostic test data to uncover insights in healthcare pathways, including:
- Trends in testing volume and costs over time.
- City-wise distribution of diagnostic tests.

It demonstrates how **KNIME workflows** can be applied to healthcare datasets to support data-driven decision-making in patient diagnostics and treatment pathways.

---

## Workflow

### Workflow Screenshot
![Workflow Screenshot](images/Diagnosis.png)

### Monthly Trend of Test Counts and Costs
![Monthly Trend](images/Monthly_Trend.png)

### Total Sum Distribution by City
![City Distribution](images/City_Distribution.png)

---

## Steps

1. **Load Data**: Import patient and test datasets (CSV Readers).
2. **Join Data**: Combine patient and test data.
3. **Date Processing**: Convert date fields and extract `Year–Month`.
4. **Aggregation**: Group data to compute monthly summaries.
5. **Visualization**:
   - **Line Plot** → Monthly test counts and costs.
   - **Bar Chart** → City-wise test costs.
   - **Pie Chart** → Distribution of tests across cities.

---

## Outputs

- **Line Plot**: Monthly trends of test counts and costs.  
- **Bar Chart**: City-wise cost comparison.  
- **Pie Chart**: Distribution of test counts across different cities.  

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/maheshnilewar/Patient_Pathway_Analysis_KNIME.git

2. Tools & Technologies

KNIME Analytics Platform – for data preparation, joining, grouping, and visualization.
CSV datasets – sample patient and test data.
GitHub – project hosting and collaboration.

3. Future Work

This project can be extended in the following ways:
Patient-Level Pathway Analysis: Expand the workflow to analyze diagnostic journeys of individual patients across multiple tests.
Predictive Modeling: Integrate machine learning models (e.g., in KNIME or Python) to forecast test volumes, costs, or patient outcomes.
Data Enrichment: Incorporate additional clinical or demographic data to provide deeper insights into healthcare trends.
Automation: Wrap the workflow into reusable KNIME components for rapid deployment across similar datasets.
Dashboard Integration: Connect outputs to visualization tools (Tableau/Power BI) or KNIME WebPortal for interactive reporting.

Author
Mahesh Nilewar
