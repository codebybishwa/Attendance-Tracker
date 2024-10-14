# Attendance Record Generation Task (CS384)

## Overview
This Python script automates the generation of attendance records based on QR code scanning data. It processes student attendance data and generates an Excel sheet (output_excel.xlsx) highlighting the attendance status for each student on different lecture dates. 

The status is color-coded for easy interpretation:
- <b>Red<b/>: Absent (0)
- <b>Yellow<b/>: Partial Attendance (1)
- <b>Green<b/>: Full Attendance (2)

## Features
- Reads attendance timestamps and student details from input files.
- Processes attendance for two consecutive lectures on each lecture date.
- Generates a color-coded Excel report of attendance status.
- Automatically highlights Absent, Partial, and Full attendance for each student.

## Dependencies
The script uses the following Python libraries:

- pandas: For data handling and manipulation.
- openpyxl: For Excel file generation and formatting.
- re: For regular expressions to clean up class timing data.
- datetime: For timestamp manipulation.
