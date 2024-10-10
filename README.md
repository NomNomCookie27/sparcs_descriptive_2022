## Project Overview

In this project, I analyzed de-identified data from the 2022 SPARCS (Statewide Planning and Research Cooperative System) dataset. The main goal was to explore healthcare trends, patient demographics, and hospital performance metrics by performing descriptive statistics and creating visualizations for key fields such as Length of Stay, Total Charges, and Total Costs.

## Dataset

The dataset used includes key fields from the SPARCS 2022 data, such as:
- Age Group
- Gender
- Length of Stay
- Type of Admission
- Total Charges
- Total Costs
- Ethnicity
- Race
- Discharge Year

### Data Source

The dataset can be found [here](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/5dtw-tffi/about_data).

## Analysis Breakdown

Here’s a quick breakdown of what’s included in the analysis:

1. **Data Loading**:
   - I loaded the dataset into a Pandas DataFrame and selected key columns for analysis.

2. **Descriptive Statistics**:
   - I calculated basic statistics (mean, median, standard deviation, etc.) for `Length of Stay`, `Total Charges`, and `Total Costs`.
   - I also explored categorical variables like `Age Group`, `Gender`, and `Type of Admission` by counting their distributions.

3. **Visualizations**:
   - A histogram for the distribution of Length of Stay.
   - A boxplot for Total Charges to help identify any outliers.
   - A bar plot to visualize trends in admissions based on Type of Admission.

4. **Handling Missing Data**:
   - I checked for any missing values in the dataset and either dropped rows or filled them with median values where necessary.

5. **Summary of Findings**:
   - I provided a summary of the main insights, including the average length of stay, how total costs vary by age group and type of admission, and any noticeable trends in admissions or charges.
   
### Requirements:
You’ll need the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn

## Conclusion

This project gave me a chance to explore some key healthcare trends and patterns in the SPARCS 2022 dataset. The analysis highlights the impact of factors such as age and type of admission on hospital stays and costs. I hope this provides a good starting point for further exploration of healthcare data!



