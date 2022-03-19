# School_District_Analysis


## Project Overview 
This project involves analyzing data from a school district to tell a story of performance based on a variety of metrics. The outputs of the analysis are: 
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
	- Top 5 and bottom 5 performing schools, based on the overall passing rate
	- The average math score received by students in each grade level at each school
	- The average reading score received by students in each grade level at each school
	- School performance based on the budget per student
	- School performance based on the school size 
	- School performance based on the type of school

In addition, some of the data showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. These altered items were stripped out and the district analysis was re-run to show how this data affected the original dataset, and provide a new/clean analysis.

The results below reflect this new analysis.


## Results
- How is the district summary affected?
	- The original analysis showed a 75.0% passing math score, a  85.0% passing reading score, and a 65.1% overall passing score.
	- The new analysis showed a 74.8% passing math score, a 85.7% passing reading score, and a 64.9% overall passing score.
	- These numbers do not differ much, but it is important to ensure the results are based on data with a high level of integrity  
- How is the school summary affected?
	- The school summary table is unchanged, except for the average math and reading scores, along with the passing percentages for math, reading, and overall.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	- Stripping out this data affected the passing percentages of Thomas High School's scores, but not by any significant amount.  The details are as follows:
		- % Passing Math went from 93.3% to 93.2%
		- % Passing Reading went from 97.3% to 97.0%
		- % Passing Overall went from 90.9% to 90.6%
- How does replacing the ninth-grade scores affect the following:
	- Math and reading scores by grade
		- The 9th graders initially had 83.6% passing for math and 83.7% passing for reading, but these values were replaced by "Nan" as these were the suspect values and removed.
		- The others grades were unchanged with the updated analysis because only 9th grade data was removed.
	- Scores by school spending
		- The impact by removing the 9th graders from Thomas High School was so small that the spending per student and their respective test scores remained unchanged before and after the updated analysis. 
	- Scores by school size
		- The impact by removing the 9th graders from Thomas High School was so small that the school size and their respective test scores remained unchanged before and after the updated analysis.
	- Scores by school type
		- The impact by removing the 9th graders from Thomas High School was so small that the school type and their respective test scores remained unchanged before and after the updated analysis.

## Summary
Overall the updated analysis did not provide greatly different results compared to the original analysis, however, it is still important to conduct this analysis to ensure that the integrity of the data is the main priority.  Decisions being made on this data need to be conducted with 100% confidence that the data being used is accurate, so it is critical to ensure this is the case.  The four cases are referenced above in the "Results" section.






