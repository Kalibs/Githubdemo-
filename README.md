---
editor_options: 
  markdown: 
    wrap: 72
---

The project is an analysis for a students survey for MPH, it contains
the self reported survey data.

The data set contains data collected from ADVANCED DATA ANALYSIS
students in class of 2024. It was collected using self reported surveys
and Data analysis was done using R programming langauge.

Description of the code;

1.  The data set `Class 1 Survey Fall 2024_di.csv` was imported from the
    provided GitHub link and assigned `C1survey`.

2.  The total number of observations (students) and variables were
    computed using the `dim()` function, resulting in **29
    observations** and **27 variables**.

3.  Variables were renamed to concise and descriptive names using the
    `names()` function. This step was to improve readability and
    interpretation of data.

4.  Using `sapply()` and `table()`, the data set was analyzed to
    identify the types of variables: **23 character variables** and **4
    integer variables**.

5.  **Handling Unusual Values (bday and bmonth),**

    The `bday` and `bmonth` variables were checked for unusual values,
    which were then recorded and converted to numeric format. The median
    values for both `bday` and `bmonth` were computed after cleaning the
    data.

6.  A new variable `bseason` was created to categorize the birth months
    into Northern Hemisphere seasons. The coding was checked using
    `table()`, and the number of students born in each season was
    computed.
