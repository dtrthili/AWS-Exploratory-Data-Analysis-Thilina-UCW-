# AWS-Exploratory-Data-Analysis-Thilina-UCW
 
**Project Description:** Exploratory Data Analysis (EDA) on Property Tax Report - City of Vancouver

**Project Title:** Emphasis on Land values on legal types: An Exploratory Data Analysis

**Objective:** The primary goal of this project is to perform an exploratory data analysis (EDA) on the Property Tax dataset to uncover patterns, trends, and insights related to land values. By analyzing various features such as legal type, previous value, and current value, we aim to understand how property valuation has changed.

**Dataset:** The Property Tax dataset consists of information such as:
•	PID: Unique identifier for each property
•	Legal-Type: Categories of legal: Land / Strata / Other
•	Street-Name: Street Name
•	Property-Postal: Postal Code
•	Previous-Land-Value: Previous Land Value
•	Current-Land-Value: Current Land Value
•	Report-Year: Year

**Methodology:**
1-	Data Collection and Preparation:
o	Download the Property Tax report from the City of Vancouver - Open Data Portal (https://opendata.vancouver.ca/explore/dataset/property-tax-report/information/?sort=-tax_assessment_year&refine.zoning_classification=Limited+Agriculture&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6InByb3BlcnR5LXRheC1yZXBvcnQiLCJvcHRpb25zIjp7InNvcnQiOiItdGF4X2Fzc2Vzc21lbnRfeWVhciIsInJlZmluZS56b25pbmdfY2xhc3NpZmljYXRpb24iOiJMaW1pdGVkIEFncmljdWx0dXJlIn19LCJjaGFydHMiOlt7ImFsaWduTW9udGgiOnRydWUsInR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJ5QXhpcyI6ImN1cnJlbnRfbGFuZF92YWx1ZSIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLWN1c3RvbSJ9LHsiYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6ImNvbHVtbiIsImZ1bmMiOiJBVkciLCJ5QXhpcyI6ImN1cnJlbnRfbGFuZF92YWx1ZSIsInNjaWVudGlmaWNEaXNwbGF5Ijp0cnVlLCJjb2xvciI6InJhbmdlLUFjY2VudCJ9XSwieEF4aXMiOiJsZWdhbF90eXBlIiwibWF4cG9pbnRzIjo1MCwic29ydCI6IiIsInNlcmllc0JyZWFrZG93biI6InJlcG9ydF95ZWFyIiwic2VyaWVzQnJlYWtkb3duVGltZXNjYWxlIjoiIiwic3RhY2tlZCI6IiJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZSwic2luZ2xlQXhpcyI6ZmFsc2V9)

![image](https://github.com/user-attachments/assets/9867fabd-275c-4e72-9ab5-2a7f2702a47c)

o	Perform initial data cleaning, which includes handling missing values, correcting data types, and renaming columns for clarity.
2-	Descriptive Statistics:
o	Generate summary statistics (mean, median, mode) for numerical features (like Age and Fare) and frequency distributions for categorical features (like Pclass and Sex).
3-	Data Visualization:
o	Create visualizations to illustrate key insights:
	Histograms and Boxplots: Analyze the distribution of continuous variables like Age and Fare.
	Bar Charts: Showcase survival rates across different categories (e.g., Sex, Pclass).
	Heatmaps: Visualize correlations between numerical variables.
4-	Survival Analysis:
o	Compare survival rates:
	By gender: Determine if there is a significant difference in survival rates between male and female passengers.
	By class: Analyze how passenger class affected survival chances.
	By age group: Create age bins to assess survival across different age demographics.
5-	Insights and Findings:
o	Summarize the findings based on data visualizations and statistical analyses, highlighting notable trends and patterns (e.g., women and children had higher survival rates, first-class passengers had a significant survival advantage).
6-	Conclusion:
o	Discuss the implications of the findings and suggest further analyses or data-driven decisions that could be explored, such as building predictive models to classify survival based on passenger features.
Tools and Technologies:
•	Python (Pandas, NumPy, Matplotlib, Seaborn)
•	Jupyter Notebook for interactive data exploration
•	Any additional data visualization tools like Tableau or Power BI (optional)
Deliverables:
•	A comprehensive Jupyter Notebook containing all steps of the analysis, including code, visualizations, and narrative explanations of findings.
•	A presentation summarizing key insights and visualizations for stakeholders or peers.
This EDA project not only demonstrates your analytical and programming skills but also highlights your ability to derive meaningful insights from data, making it a valuable addition to your data analyst portfolio.

