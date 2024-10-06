# 🧑‍💼 HR Analytics Dashboard

## 📊 Overview

This repository contains resources for an **HR Analytics Dashboard** designed to visualize and analyze employee attrition data. The dashboard provides comprehensive insights into:

- Attrition rate
- Employee demographics
- Job satisfaction
- Salary levels
- Departmental attrition trends

This tool enables data-driven decision-making to improve employee retention and satisfaction.

## 🔍 Description

The **HR Analytics Dashboard** offers the following insights:

- **Count of Employees**: Displays the total number of employees analyzed.
- **Attrition Rate**: Shows the percentage of employees who left the company.
- **Average Age and Salary**: Provides insights into average employee age and salary.
- **Attrition by Demographics**: Visualizes attrition by education, age, gender, salary slab, years at the company, and job role.
- **Job Satisfaction**: Summarizes job satisfaction levels across various roles.

## 📂 Project Structure

### 1. Data Preparation

- **Imported the CSV File**:  
  The dataset `HR_Analytics.csv` was imported into Power BI Desktop, containing employee demographics, job roles, job satisfaction, and attrition status.

- **Data Cleaning**:  
  - Reviewed and cleaned the data to remove inconsistencies and null values.
  - Applied transformations and added calculated columns (e.g., attrition rate, average age, average salary).

### 2. Building the Dashboard

- **Visualizations**:  
  Various Power BI visuals were used to represent the data:

  - **Bar Charts**: Attrition by job role, age, salary slab, and years at the company.
  - **Pie Chart**: Attrition by education level.
  - **Line Chart**: Attrition trends across years of employment.
  - **Card Visuals**: Key metrics such as total employees, attrition count, attrition rate, average age, and average salary.

- **Filters and Slicers**:  
  - Slicers for departments (HR, Research & Development, Sales) to filter data by department.
  - Gender-based filters for analyzing male vs. female employee attrition.

### 3. Formatting and Design

- **User-Friendly Layout**:  
  The layout is designed for ease of use, with key metrics at the top followed by detailed breakdowns.

- **Themes and Colors**:  
  A consistent color theme was applied to clearly differentiate data points. For example, distinct colors represent different age groups and job roles.

- **Titles and Labels**:  
  Each visual includes clear titles and labels, making the dashboard easy to understand at a glance.

### 4. Final Review

- **Interactivity Testing**:  
  The dashboard was tested for functionality to ensure filters, slicers, and visuals work as intended.
  
- **Cross-Verification**:  
  The data and calculated measures were cross-verified for accuracy.

## 🔍 Insights Gained

- **High Attrition in Specific Demographics**:  
  Employees aged 26-35, particularly in the Life Sciences and Medical fields, had the highest attrition. This suggests a need for targeted retention strategies in these groups.

- **Impact of Salary on Attrition**:  
  A significant portion of employees earning up to 5k had the highest attrition rates, underscoring the importance of competitive compensation.

- **Job Satisfaction vs. Attrition**:  
  Despite high job satisfaction, roles such as Laboratory Technicians and Research Scientists exhibited substantial attrition, suggesting external factors like career growth opportunities may influence turnover.

- **Attrition by Tenure**:  
  The analysis shows that most employees leave within the first 0-3 years, highlighting the need for strong onboarding and early engagement programs.

- **Gender-Based Attrition**:  
  The dashboard revealed higher attrition among male employees, indicating a potential area for gender-specific retention strategies.

- **Departmental Attrition Trends**:  
  Research & Development faced higher attrition compared to other departments, suggesting a need for targeted improvements in that area.

## 📈 Importance of the Dashboard

- **Data-Driven Decision Making**:  
  By visualizing key HR metrics, decision-makers can identify trends, diagnose issues, and implement strategies to reduce attrition and improve satisfaction.

- **Proactive Retention Strategies**:  
  Insights from the dashboard allow companies to design and implement retention programs, such as revising compensation packages or offering career development opportunities.

- **Enhanced Resource Allocation**:  
  Understanding attrition patterns enables better resource allocation, such as investing in employee engagement programs for departments with high turnover.

- **Improving Employee Experience**:  
  The dashboard helps identify areas where the employee experience can be improved, such as dissatisfaction in specific roles or the impact of tenure on retention.

- **Strategic Workforce Planning**:  
  By providing a holistic view of the workforce, the dashboard enables better long-term planning, especially in succession planning and talent development.

- **Continuous Improvement**:  
  This dashboard can serve as a benchmark to track the effectiveness of HR initiatives over time, helping the company achieve better retention outcomes.

## 🚀 How to Use the Dashboard

1. **Connect Data**:  
   Import the `HR_Analytics.csv` file into Power BI.

2. **Customize Visualizations**:  
   Use the provided visualizations and filters to explore key HR metrics.

3. **Analyze Data**:  
   Leverage the dashboard’s interactivity to analyze attrition trends by demographic, job role, salary, and more.

4. **Generate Reports**:  
   Share insights with stakeholders by exporting the dashboard as a PDF or PowerPoint file for easy sharing.

## 📌 Conclusion

The **HR Analytics Dashboard** is a powerful tool that provides valuable insights into employee attrition and demographics. By using this dashboard, HR professionals and managers can identify trends, make data-driven decisions, and implement strategies to improve employee retention and overall satisfaction.

---

### 📂 Files

- **HR_Analytics_Dashboard.pbix**: The Power BI file containing the dashboard.
- **HR_Analytics_Dashboard.pdf**: A PDF version of the dashboard for easy sharing.

---

### 🔗 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
