#  HR Analytics Dashboard

A comprehensive Power BI dashboard for analyzing employee attrition and workforce metrics to help HR teams make data-driven decisions.

##  Project Overview

This interactive Power BI dashboard provides deep insights into employee attrition patterns, helping organizations:
- Identify key factors contributing to employee turnover
- Analyze workforce demographics and distribution
- Make informed decisions about retention strategies
- Track HR metrics in real-time

##  Key Performance Indicators (KPIs)

| Metric | Value |
|--------|-------|
| **Total Employees** | 1,473 |
| **Attrition Count** | 237 |
| **Attrition Rate** | 16.1% |
| **Average Employee Age** | 37 years |
| **Average Salary** | $6.5K |
| **Average Years at Company** | 7.0 years |

##  Dashboard Features

### 1. **Attrition by Education**
- Visualizes employee turnover across different educational backgrounds
- Categories: Life Sciences (38%), Medical (27%), Marketing (15%), Technical Degree (14%), Other (5%)

### 2. **Attrition by Age Groups**
- Bar chart showing attrition distribution across age brackets
- Age groups: 26-35, 18-25, 36-45, 46-55, 55+
- Highest attrition in 26-35 age group (116 employees)

### 3. **Attrition by Salary Slab**
- Horizontal bar chart analyzing turnover by salary ranges
- Salary bands: Up to 5k, 5k-10k, 10k-15k, 15k+
- Identifies compensation-related attrition patterns

### 4. **Attrition by Years at Company**
- Area chart showing attrition trends based on tenure
- Helps identify critical retention periods
- Peak attrition visible in early years

### 5. **Attrition by Job Role**
- Detailed breakdown by specific positions
- Roles tracked: Laboratory Technician, Sales Executive, Research Scientist, Sales Representative, Human Resources

### 6. **Gender Distribution**
- Pie chart showing male vs female attrition
- Male: 140 employees
- Female: 79 employees

##  Tools & Technologies Used

- **Microsoft Power BI Desktop** - Dashboard creation and visualization
- **Excel/CSV** - Data source
- **DAX** - Data Analysis Expressions for calculations
- **Power Query** - Data transformation and cleaning

##  Project Structure
```
HR-Analytics-Dashboard/
│
├── HR analytics.pbix          # Main Power BI file
├── data/                      # Data folder (if applicable)
│   └── HR_data.csv
├── screenshots/               # Dashboard images
│   └── dashboard_preview.png
└── README.md                  # Project documentation
```

##  Data Source

The dashboard uses HR data containing the following fields:
- Employee ID
- Age
- Department
- Education
- Job Role
- Salary
- Years at Company
- Attrition Status
- Gender
- And more...

*(Note: Sample/anonymized data used for demonstration purposes)*

##  Key Insights

Based on the dashboard analysis:

1. **High Attrition in Entry-Level Roles**: Laboratory Technicians and Sales Executives show highest turnover
2. **Early Career Attrition**: Significant attrition in employees with 0-5 years at company
3. **Salary Impact**: Majority of attrition occurs in lower salary brackets (Up to 5k)
4. **Age Factor**: Younger employees (26-35) are more likely to leave
5. **Education Correlation**: Life Sciences graduates have highest attrition rate (38%)

##  Dashboard Design Features

- **Interactive Filters**: Filter by Human Resources, Research & Development, and Sales departments
- **Gender-based Analysis**: Separate views for male and female attrition
- **Clean Visual Design**: Professional dark theme with color-coded visualizations
- **Responsive Layout**: Optimized for different screen sizes

##  Future Enhancements

- [ ] Add predictive analytics for attrition risk
- [ ] Include employee satisfaction scores
- [ ] Integrate real-time data refresh
- [ ] Add drill-through pages for detailed employee profiles
- [ ] Export functionality for reports
- [ ] Mobile-optimized view



