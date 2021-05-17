# analysing_ny_schools_data

Investigating the relationship between demographics and performance in high schools is an interesting angle to take to discover the efficacy of standardised tests. NYC has a significant immigrant population, comparing factors such as race, income and gender with SAT performance is a good way to find whether the SAT system is a fair test. For example if a demographic group performs better than others, we would have some evidence that the SAT system is possibly not fair.

Data on New York City high schools is publicly available through [NYCOpenData](https://opendata.cityofnewyork.us/), as well as the demographics of each high school.

Several data files were sourced:

ap_2010.csv - Advanced Placement exam reults for each high school (passing an optional AP exam can earn a student college credit in that subject)

class_size.csv - Information on class size for each school

demographics.csv - Information on school demographics

graduation.csv - Percentage of students who graduated for each school

sat_results.csv - SAT scores by school

high_school_directory.csv - Directory of NY high schools

survey_ny.txt - Data on school surveys from all schools

survey_d75.txt - Data on school surveys from NY District 75

The datasets were cleaned and aggregated into a single csv. The process can be found in the cleaning and aggregation notebook, and the analysis can be found in the data analysis notebook.
