# pandas-challenge

This project provides a solution using Python and pandas to analyze data from the city's school district. It aims to assist the school board and the mayor in making informed strategic decisions about future school budgets and priorities.

![1693976745162](https://github.com/user-attachments/assets/037ba803-484d-40c8-882a-4dce88a98de6)

This project used two datasets in csv format, one is $${\color{lightblue}schools\\_complete.csv}$$ file with the data elements School ID, school_name, type, size, budget and another dataset is $${\color{lightblue}students\\_complete.csv}$$ file with the data elements Student ID, student_name, gender, grade, school_name, reading_score and math_score. For this analysis, both datasets were imported, merged, and the aggregated data was displayed using Python pandas DataFrames. The project was carried out in a Jupyter Notebook to present and communicate the analysis, and the following link was created to share the report. [PyCitySchools_starter.ipynb](PyCitySchools/PyCitySchools_starter.ipynb )

## School District Data Analysis

### Trends and Insights

Based on the analysis performed on the school district data using Python and pandas, several trends and insights emerged:

1. **Average Math and Reading Scores**
   - Charter schools consistently outperformed district schools in both average math and reading scores. The average math scores for charter schools were notably higher than those of district schools, indicating a possible focus on academic excellence within these institutions.
   - Reading scores showed a similar trend, with charter schools again leading over district schools, suggesting that these schools may have stronger literacy programs or resources.

2. **Passing Rates**
   - The percentage of students passing both math and reading was significantly higher in charter schools compared to district schools. This indicates that a larger proportion of students in charter schools meet or exceed the proficiency standards.
   - District schools showed lower passing rates, which could be linked to various factors like student-teacher ratios, resource availability, or socio-economic influences.

3. **Impact of School Size**
   - Smaller schools (with fewer than 1,000 students) demonstrated better average scores and higher overall passing rates. This trend suggests that smaller class sizes or a more personalized learning environment could positively influence student performance.
   - Large schools (with 2,000 to 5,000 students) tended to have lower average scores and passing rates, highlighting challenges that larger institutions may face in maintaining high educational standards.

4. **Spending Per Student**
   - Schools with moderate spending per student (around $585 to $630) showed the highest overall passing rates. Surprisingly, schools with the highest per-student spending did not always correlate with better performance, which could indicate that simply increasing the budget is not enough to drive academic success.
   - The data suggests that there is an optimal range of spending where resources are efficiently utilized to produce the best outcomes for students.

5. **Overall School Performance by Type**
   - Charter schools consistently displayed higher overall performance compared to district schools across multiple metrics, including average scores and passing rates. This trend reinforces the idea that charter schools may provide a more effective educational environment or have access to specialized teaching methods that positively impact student outcomes.

### Summary
The analysis indicates that school size and the type of school (charter vs. district) are significant factors in determining student performance. Smaller, charter schools tend to achieve better results, suggesting that strategies to reduce class sizes and adopt charter-like practices could benefit district schools. Additionally, targeted spending rather than simply increasing budgets appears to play a crucial role in driving academic success.

These findings can serve as valuable insights for the school board and mayor to guide future budget allocations, policy decisions, and resource distribution across the school district.
