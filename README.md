## HR-Data-analytics

#Overview
This project involves the development of a Power BI dashboard to track employee data for the HR team. The dashboard provides insights into various aspects including working hours, attendance, performance, and leaves. By streamlining HR processes, the dashboard significantly increases efficiency and facilitates informed decision-making.

#Goal
The primary goals of the dashboard are:

    -To check the working preferences of employees.
    -To monitor sick leave percentages.

#Implementation Details
  -Data Import and Transformation

    The project started with importing data from an Excel file containing different sheets with varying column names.
    To ensure consistency, the sheets were merged, and data was processed using Power Query.
    Initial transformations included fixing headers and un-pivoting columns except for name and employee ID.
    Text values in non-date columns were identified and converted to date format, with error values caused by text data removed.
    Parameters were set to automate the transformation process.

  -Data Modeling and Analysis

    A function was created based on the transformation steps in Power Query.
    This function was applied to all tables to ensure consistency.
    Unnecessary columns were deleted to streamline the dataset.
    DAX was used to create measures for KPIs (Key Performance Indicators) and other metrics

  -Visualization

    The data was visualized using charts, slicers, and tables to provide actionable insights.
    Visualization elements were carefully chosen to effectively communicate key HR metrics.

  -Repository Structure

    Dashboard: Contains the Power BI file (.pbix) for the HR dashboard.
    Data: Includes the original Excel file and any intermediary data files used during the transformation process.
    Documentation: Houses additional documentation such as this README file.
  

