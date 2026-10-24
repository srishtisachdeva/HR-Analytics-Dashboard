# HR-Analytics-Dashboard

HR Analytics Dashboard
An interactive HR Analytics Dashboard built with Microsoft Power BI
to explore employee demographics, attrition patterns, salary
distribution, job satisfaction, and work experience. The report brings
key HR indicators into one view to support data-driven workforce
decisions.
Dashboard Overview
The report contains a single dashboard page with KPI cards, charts, a
job-role matrix, and slicers.
Key Metrics
- Employee count --- employee records included in the analysis.
- Attrition count --- attrition records represented in the report.
- Attrition rate (%) --- attrition rate measure from the data
  model.
- Average age --- average employee age.
- Average years at company --- average employee tenure.
Visualizations
- Attrition by department --- compares attrition across
  departments.
- Attrition by salary slab --- compares attrition across salary
  bands.
- Job role and job satisfaction matrix --- lets users examine
  attrition counts by role and satisfaction level.
- Employee count by age group --- compares the employee population
  across age bands.
- Attrition by gender --- breaks down attrition by gender.
- Attrition by total experience --- explores attrition counts
  across total-experience values.
- Department funnel --- presents employee counts by department.
Filters
The dashboard includes slicers for Department and Age Group. Use
them to narrow the report and explore segments of the workforce.
Selections may affect multiple visuals on the page.
Note: the figures shown depend on the report's data model and active
filters. This README does not state fixed totals because those values
can change with filtering.

Tools and Technologies
- Microsoft Power BI Desktop --- report authoring and interactive
  visualization
- Power Query / data model --- data preparation and model layer,
  where configured in the PBIX
- DAX measures --- includes an Attrition Rate % measure referenced
  by the report
How to Open
1. Download or clone this project repository.
2. Open HR analytics dashboard.pbix in Microsoft Power BI
   Desktop.
3. If Power BI prompts for data-source credentials or a refresh, follow
   the prompts for the source configured in the report.
4. Use the Department and Age Group slicers to explore different
   workforce segments.
5. Hover over charts for tooltips and select chart elements to
   cross-filter other visuals where interactions are enabled.
Suggested Analysis Questions
- Which departments have comparatively higher attrition?
- How does attrition vary across salary bands and gender?
- Which job roles show different job-satisfaction patterns?
- How is employee count distributed across age groups?
- Is attrition associated with different levels of total work
  experience?
- How do the results change when a specific department or age group is
  selected?
Repository Contents
- HR analytics dashboard.pbix --- Power BI report file
- README.md --- project overview and usage guide
Limitations
- The PBIX file is the report artifact; the source dataset and refresh
  configuration may be external or embedded in the Power BI model.
- Interpret patterns as descriptive analysis, not proof that a
  particular factor causes attrition.
- Confirm data definitions (especially attrition count and attrition
  rate) in the model before using results for operational decisions.
Future Enhancements
- Add a date or hiring-cohort view if suitable fields are available.
- Include drill-through pages for employee segments and
  department-level analysis.
- Add trend comparisons and targets for attrition rate.
- Document data sources, refresh cadence, and measure definitions.
