# Employee-Performance-Review
### Leveraging Tableau for Strategic Insights: Analyzing XYZ Company’s Employee Performance
As XYZ Company plans for expansion, understanding its historical employee performance is critical. With Tableau's powerful visualization tools, the company can uncover meaningful insights into workforce trends, hiring patterns, and key performance metrics. This article outlines the step-by-step process for creating impactful visualizations that guide strategic decision-making.
Key Insights for Employee Performance (2023)
XYZ Company seeks to focus on the following visualizations:

#### 1. Number Cards for Workforce Metrics

Summarize critical workforce statistics such as total employees, average age, employees with tenure ≥3 years, those hired in the last six months, and employees who left during the same period.
Steps to Create:
Average Age: Drag the Age field to the Text card, select "Measures," and choose "Average."
Hired in the Last 6 Months:
Drag the DOJ (Date of Joining) field to Filters.
Select "Relative Date" > "Last 6 Months."
Add Emp ID to Text cards.
Left in the Last 6 Months:
Use the Left Date field in Filters with similar settings.
Add Emp ID to Text cards.

#### 2. Gender Representation by Department

A table showcasing department-wise gender counts provides clarity on workforce diversity.
Steps to Create:
Drag Gender to Columns and Dept to Rows.
Add Emp ID to Text cards, then use "Count" as the aggregation method.

#### 3. Employee Count by Salary Range (Bar Graph)

Visualize the distribution of employees across salary ranges.
Steps to Create:
Drag Emp ID to Columns.
Drag Range (salary range) to Rows for a clear distribution.

#### 4. Hiring Trends Over Time (Line Graph)

Track the number of employees hired year by year to understand recruitment trends.
Steps to Create:
Drag the DOJ field to Columns and Emp ID to Rows.

#### 5. Employee Ratings (Column Chart)

A column chart consolidates employee performance ratings across key areas like communication, efficiency, and problem-solving.
Steps to Create:
Add Dept to Filters for department-specific insights.
Drag fields like Communication, Efficiency, Knowledge, Problem-Solving, and Punctuality to the Label (Marks card).
Final Dashboard
Integrate all visualizations into a single dashboard, offering a comprehensive view of employee performance and enabling management to identify strengths and areas for improvement. This holistic approach allows XYZ Company to make data-driven decisions to support its expansion plans.

### Conclusion
By utilizing Tableau to analyze workforce data, XYZ Company gains actionable insights into its employee performance trends. This visualization framework not only enhances decision-making but also aligns with the organization’s goal of fostering growth through informed strategies.
