# TB-ACCELERATION-PLAN-Dashboard!

## Overview
This repository contains a Power BI dashboard on Tuberculosis data for monitoring and evaluation.  Data is extracted from APPR database via connector and loaded into Power BI, where Power Query is used for data cleaning, manipulation, and restructuring.  The dashboard provides a range of analyses, including an indicator summary report, trend analysis, concurrence analysis between indicators, an accountability matrix, and target achievement monitoring, among other features.

Beyond the project's striking visuals, its most compelling feature was the automation of recurring processes.  Specifically, it addressed the dynamic recalculations required by period changes (e.g., quarterly shifts) and implemented functions that adapt their behavior based on specific conditions.
## DAX formulas used 
  - Logical functions such as IF(), AND(), OR(), SWITCH()
  - Text Functions such as CONCATENATE(), LEFT(), RIGHT()
  - Calculations functions such as CALCULATE(), DIVIDE()
  - Aggregation functions such as SUM(), COUNT()
  - Information functions such as ISBLANK(), ISNUMBER()
## Data Cleaning/Restructuring done in PowerQuery
  - Text Manipulation such as Text.Replace, Text.BeforeDelimiter, Text.AfterDelimiter, Text.StartsWith, Text.EndsWith, Text.Contains, Text.Split, Text.Combine, 
    Text.PadStart, Text.PadEnd
  - Date and Time Manipulations such as Date.AddDays, Date.AddMonths, Date.AddYears, Date.FromText, DateTime.FromText, Date.Year, Date.Month, Date.Day
  - Data Type conversion such as Table.TransformColumnTypes
  - Table Manipulations such as Table.NestedJoin, Table.Merge, Table.DuplicateColumn, Table.AddColumn, Table.RenameColumns, Table.RemoveColumns, Table.Sort,     
    Table.SelectRows, Table.ReorderColumns, Table.SplitColumn, Table.ReplaceValue, Table.Pivot, Table.Unpivot
  - Creating reuseable functions

You can download the Power BI dashboard here: [TB Acceleration Plan Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmM0NTU3YTctZmRkNS00NjA0LWE2MjgtN2Y0ZWUwZjhmYzgzIiwidCI6Ijc4MDNkYTk1LWZkMDQtNDg2ZC04ZTllLTI5NGExODdjMWQyNCJhttps://drive.google.com/file/d/1hp1V0urqu9lIqO5EFUV79UGhogNHkJDN/view?usp=drive_link)

Feel free to explore and provide feedback!😊
