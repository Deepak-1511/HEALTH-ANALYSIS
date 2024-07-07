# HEALTH-ANALYSIS

### Project Summary:
This project involves analyzing an insurance dataset using Python. The analysis includes data cleaning, exploration, and visualization to understand the relationships between different variables in the dataset.

### Key Steps and Descriptions:

1. **Library Imports**:
   - Imported essential libraries for data analysis and visualization: `numpy`, `pandas`, `matplotlib`, and `seaborn`.

2. **Data Loading**:
   - Loaded the insurance dataset from a CSV file using `pandas`.

3. **Initial Data Exploration**:
   - Displayed the first few rows of the dataset to understand its structure.
   - Checked the shape (number of rows and columns) of the dataset.
   - Reviewed the column names.
   - Obtained summary information about the dataset including data types and non-null counts.
   - Checked for missing values and duplicated rows.

4. **Data Cleaning**:
   - Removed duplicated rows from the dataset.
   - Rechecked the shape and summary information of the cleaned dataset.
   - Examined the unique values in specific columns (`age`, `sex`, `region`, `children`, `charges`, `smoker`).

5. **Data Export**:
   - Saved the cleaned dataset to a new CSV file.

6. **Data Visualization**:
   - Created various plots to visualize the data:
     - Bar plots showing the relationship between age and region.
     - Count plots and bar plots for other variables.
     - Box plots for charges.
     - Line and scatter plots to explore relationships between charges, region, and age.
   - Noted some errors in the plotting code, indicating potential issues with plot configurations or data format.
