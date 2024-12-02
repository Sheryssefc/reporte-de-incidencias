# reporte-de-incidencias

### Dashboard Preview : https://github.com/Sheryssefc/reporte-de-incidencias/blob/main/reporte_de_incidencias.png

# Jira Incident Report - FinanSmart (2024)
This incident report covers data from 2024 up to November, collected from Jira for the fictional fintech company **FinanSmart**. The report aims to provide a clear and detailed view of the reported incidents, indentifying problem areas, and make informed decisions to improve service and keep users satisfied.

## Tools Used
- **Power BI**: For creating interactive visualizations and dashboards.
- **Jira**: As the data source for managing incidents.
- **Excel/CSV**: For organizing and cleaning data before loading it into Power BI.

## Data Loading Process in Power BI
The following steps were taken to load, organize, and clean the data from Jira into Power BI:

### 1. **Data Collection**
   - **Data Export**: The data was exported from Jira in CSV format.
### 2. **Data Organization**
   - **Categorizing Data**: Grouped incidents by status, problem type, and responsible person to make the data easier to analyze and interpret.
   - **Sorting and Structuring**: Data was sorted and structured in a way that facilitates easy navigation and understanding, with clear definitions for each metric and dimension.
### 3. **Data Cleaning**
   - **Grammar Corrections**: Corrected any grammatical errors in textual data to ensure clarity and consistency across the dataset.
   - **Removing Redundant Words**: Eliminated repetitive words or phrases to improve the quality of the data and ensure better analysis.
   - **Removing Incomplete Records**: Rows with missing or incorrect data were removed to ensure accurate analysis.
   - **Data Type Conversion**: Correct data types (e.g., dates, numbers, text).
### 4. **Creating Visualizations**
   - **Importing into Power BI**: The CSV files or data retrieved from Jira were imported into Power BI.
   - **Field Transformation**: Some fields were transformed to a more suitable format and creating new columns to facilitate analysis, like  `MesNumerico`.
   - **Interactive Dashboard**: Visualizations such as bar charts, line charts, and KPI cards were created to analyze total incidents, resolved incidents, pending, and canceled issues.
   - **Area-Based Analysis**: Charts also display incidents segmented by company area, allowing identification of areas with more problems.
### 5. **Adding Filters**
   - **Interactive Filters**: Filters were added so users can view data by month, responsible person, or problem type, making the report more interactive.
   - **KPI Measures**: Custom measures were created to calculate total incidents by status, average resolution time, and other key metrics.

## Report Impact
This report has provided FinanSmart with a clearer view of incidents throughout the year, delivering the following benefits:
- **Improved Incident Response**: The analysis helps the support team respond faster to recurring problems.
- **Prioritizing Critical Areas**: Areas with more incidents are identified and prioritized for resolution to improve user satisfaction.
- **Data-Driven Decisions**: Management can make informed decisions based on the data, implementing improvements in areas with a high volume of incidents.

## How to Use the Report
   1. **Open the .pbix file**: Download the Power BI file and open it in 
   Power BI Desktop.

   2. **Explore the Visualizations**: Interact with the filters to  
   analyze incidents by different criteria.
## Conclusion
The Jira incident analysis via Power BI provides a powerful tool for improving incident management, ensuring user satisfaction, and optimizing support processes. This dashboard showcases how data visualizations can transform the way problems are managed and decisions are made within an organization.
