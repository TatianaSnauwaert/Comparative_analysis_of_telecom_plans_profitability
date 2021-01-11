# Comparative_analysis_of_telecom_plans_profitability
## Statistical Data Analysis Project from Practicum by Yandex

### Goal
Prepare a report for the telecom operator Megaline to analyze clients' behavior, determine which of the two prepaid plans is more profitable and test two statistical hypotheses.

### This project's repo includes the following files:

- The project's final jupyter notebook (Statistical Data Analysis Project_final.ipynb);
- A pdf format of the notebook (Statistical Data Analysis Project_final.pdf)
- Input data (5 csv files)
- Project description from Practicum (SDA_Project_description.pdf)

### This project includes the following steps:

1. Descriptive statistics;
2. Artifacts and duplicates check;
3. Missing values replacement and data type change;
4. Calculations;
5. EDA: distribution analysis and outliers removal;
6. Statistical hypotheses testing.

### Based on the analysis we have come to the following conclusions:

1. We found that the "Surf" plan is mostly profitable throughout the year with a tendency of being more and more profit-making towards the end of the year. In contract, the "Ultimate" plan is mostly not profitable during the year, with the opposite tendency of being even more costly by the end of the year.

2. As for the plans' conditions, the "Surf" plan brings some profit because users often exceed the limits. In contract, the "Ultimate" plan's limits should be reconsidered as users quite rarely (in 0% for calls and messages and 2% for web traffic cases) reach the limits and usually are far away from them.

3. We tested two statistical hypotheses:

- The average profit from users of Ultimate and Surf plans differs;
- The average profit from users in NY-NJ area is different from that of the users from other regions.
For both cases we have tested a bilateral and 2 unilateral hypotheses:

  - bilateral: in both cases we have rejected the null - each pair of populations does not bring the same average profit to the company;
unilateral:
- 'greater': in both cases we have rejected the nulls in favor of the alternative hypotheses:
    - The "Surf" plan brings more profit than "Ultimate", on average;
    - Users from NY-NJ area bring more profit than users from other regions, on average.
- 'less': in both cases we have retained the nulls over the alternative hypotheses:
    - The "Surf" plan does not bring less profit than "Ultimate", on average;
    - Users from NY-NJ area does not bring less profit than users from other regions, on average.

### The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/1SrGdReexaSEomJGS6yR6cRwJtHA_XqpprnLaE7B6Ayg/edit#gid=1515049661) (Introduction to SDA tab).
Total time spent on the project: 14.8 hours with a daily average	of 2.67 hours working for 8 days.
