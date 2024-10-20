# Employee Satisfaction Survey Analysis

## Overview

The Seattle Department of Public Works conducted a survey of approximately 1,500 employees to measure job satisfaction and identify opportunities for improved engagement and motivation. The objective of this analysis is to summarize the survey responses and provide insights for HR leadership to inform strategies for enhancing employee satisfaction.

## Data Description

The survey data includes the following fields:

| Field         | Description                                                     |
|---------------|-----------------------------------------------------------------|
| **Response ID** | Unique, sequential ID representing a response to a survey question. |
| **Status**     | Identifies whether a response was complete or incomplete.      |
| **Department** | Survey respondent's job department (Human Resources, Public Works, etc.). |
| **Director**   | Binary (0/1) field indicating if the respondent is in a Director role. |
| **Manager**    | Binary (0/1) field indicating if the respondent is in a Manager role. |
| **Supervisor** | Binary (0/1) field indicating if the respondent is in a Supervisor role. |
| **Staff**      | Binary (0/1) field indicating if the respondent is in a Staff role. |
| **Question**   | Full survey question text.                                      |
| **Response**   | Survey response value (0, 1, 2, 3, 4).                          |
| **Response Text** | Survey response text (Not Applicable, Strongly Disagree, Disagree, Agree, Strongly Agree). |


## Data Cleaning Process - Excel

1. **Calculate Stats**: Used Excel to find min, max, count, and blanks for each numerical field.
2. **Remove Blanks**: Deleted rows with any blank responses.
3. **Remove Duplicates**: Removed rows with duplicate values.
4. **Frequency Count**: Counted values in Department and Question fields, and standardized names.

## Conclusions

- **Overall Satisfaction**: Decent, but can be improved (avg 3.02).
- **Recognition**: Needs work; employees feel underappreciated (avg 2.80).
- **Work Environment**: Generally positive (avg 3.14).
- **Growth Opportunities**: Needs improvement (avg 3.04).
- **Leadership**: Needs better accountability (avg 2.95).
- **Team Building**: Low score for having a best friend at work (avg 2.60).

Focusing on recognition, growth opportunities, leadership, and team-building activities could improve overall satisfaction.



