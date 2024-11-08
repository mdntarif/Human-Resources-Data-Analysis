# HR Data Analysis and Insights

This project focuses on analyzing and visualizing key workforce metrics from the **Human Resources Data Set**. It leverages advanced Excel techniques such as Power Query, Pivot Tables, statistical analysis, and various lookup functions to extract, clean, and model HR data. The ultimate goal is to gain insights into workforce diversity, employee performance, and organizational trends to guide HR decision-making and strategic workforce planning.

## Project Overview

This analysis uses a dataset with multiple tables containing employee information, performance scores, and HR-related data. The project solves business problems related to employee demographics, performance evaluations, workforce diversity, engagement, and organizational structure. Key techniques include Power Query, statistical analysis (mean, median, mode, variance, etc.), and data visualization through Pivot Tables and charts.

### Key Business Problems & Solutions

1. **Workforce Diversity and Engagement**:
   - Analyze the gender and race distribution across departments.
   - Categorize employees by age groups within departments.
   - Calculate average employee engagement scores by department.
   - Use functions like `COUNTIF` and `AVERAGEIF` to calculate gender, race, age group distribution, and engagement.
   - Visualize with pie, bar, and clustered column charts for better comparative analysis.

2. **Employee Profile & Communication**:
   - Extract and clean employee data (e.g., convert names to uppercase, calculate ages).
   - Generate personalized email addresses for each employee.
   - Standardize email format using first initial, last name, age, and domain.

3. **Performance Evaluation**:
   - Use `VLOOKUP`, `XLOOKUP`, and `INDEX-MATCH` functions to retrieve employee names and performance scores based on EmpID.
   - Build a dynamic and automated performance evaluation report for HR managers.

4. **Employee Distribution Analysis**:
   - Use Pivot Tables to compare employee values (salary, performance rating) across categories.
   - Segment the distribution by marital status and visualize with charts.

5. **Department-Wise Employee Comparison**:
   - Analyze employee distribution across departments segmented by marital status and gender.
   - Use Pivot Tables with filters to segment by gender and marital status.
   - Provide insights into workforce demographics and diversity.

6. **Engagement and Satisfaction Analysis**:
   - Calculate average engagement survey scores and satisfaction scores by department.
   - Use Pivot Tables to compare these metrics, filtered by gender.
   - Visualize with Clustered Column Charts to identify trends and areas for improvement.

7. **Position and Compensation Analysis**:
   - Create a comparison report on employee positions across departments.
   - Analyze key performance metrics such as average engagement score and pay rate.
   - Filter the data by marital status, citizenship status, and gender.
   - Enhance the report with conditional formatting and a professional design.

8. **Statistical Insights for Talent Management**:
   - Apply statistical concepts such as mean, median, mode, variance, standard deviation, and correlation.
   - Extract insights like average age, level, most common department, age variance, and the correlation between department and manager.
   - Use these insights to guide strategic HR decisions on hiring, promotions, and workforce planning.

## Tools & Techniques Used

- **Excel Power Query**: For importing, cleaning, and transforming data.
- **Excel Formulas**: Including `SUM`, `AVERAGE`, `MIN`, `MAX`, `COUNT`, `IF`, `SUMIFS`, `COUNTIFS`, `VLOOKUP`, `XLOOKUP`, `INDEX-MATCH`.
- **Pivot Tables & Pivot Charts**: For summarizing and visualizing data.
- **Conditional Formatting**: For highlighting key data trends and making reports visually appealing.
- **Statistical Concepts**: Mean, Median, Mode, Variance, Standard Deviation, Correlation.

## Dataset Overview

The dataset used includes the following tables:

- **tbl_action.csv**: Contains employee actions (e.g., promotions, terminations).
- **tbl_employee.csv**: Employee personal and job-related data (e.g., employee ID, name, gender, department).
- **tbl_hr_data.txt**: Detailed HR data including performance scores, employment status, and department information.
- **tbl_perf.csv**: Employee performance data including performance ratings and review dates.

## How to Use

1. **Data Import**: Import the provided dataset using Power Query.
2. **Data Cleaning**: Apply necessary transformations to clean text columns and standardize date formats.
3. **Data Modeling**: Use Power Pivot to join the four tables on `EmpID` and create relationships between them.
4. **Statistical Analysis**: Apply statistical measures to generate insights on employee demographics, performance, and organizational trends.
5. **Pivot Tables & Visualization**: Build Pivot Tables for each analysis task and visualize with appropriate charts.
6. **Reporting**: Create concise and visually appealing reports using conditional formatting and charts.

## Business Applications

- **Diversity & Inclusion**: Gain insights into gender, race, and age distribution to inform diversity initiatives.
- **Performance Management**: Evaluate employee performance and identify areas for improvement.
- **Workforce Planning**: Understand employee demographics, engagement, and satisfaction to guide HR strategy.
- **Compensation Analysis**: Assess employee compensation and performance metrics to ensure fair and competitive salaries.
- **Strategic HR Decision-Making**: Use data-driven insights to optimize talent management, promotions, and resource allocation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For more information or questions regarding the project, please contact me via GitHub.

---

This `README.md` offers a clear and concise description of your project, including the business problems, tools, and methodologies used. It’s structured for easy understanding, especially for potential collaborators or employers reviewing the project on GitHub.
