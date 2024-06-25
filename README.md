# pandas-challenge


## PyCity School
This folder contains that jupyter notebook file that contains the script used to run the district analysis. 

### Main Script
This jupyter notebook file contains the mainscript used to analyze the data: [District-wide Standardized Test Analysis](https://github.com/EdGonz44/pandas-challenge/blob/main/PyCitySchool/PyCitySchools_mainscript.ipynb)

In this script we broke down the data into distinct dataframes that summarized the data in novel ways. The first distinct dataframe was a district summary that included total students, total budget, and a breakdown of student math/reading scores with pass rates. The subsequent dataframes consisted of: a breakdown of the district summary stats but by individual schools with the inclusion of that schools total budget, per student budget, and school type; a breakdown of the stats of the top 5 schools; a breakdown of the stats of the bottom 5 schools; math scores by grade; reading scores by grade; scores by school spending; scores by school size; and, scores by school type. These dataframes allowed me to create an analysis on the district's district-wide standardized test results. The jupyter notebook contains the written analysis; but, for ease of access, this README also contains the written analysis.


## Resources
This folder contains the csv files we referenced in the PyCity school jupyter notebook file.

## Analysis:
The overall district is comprised of 15 different schools, containing nearly 40,000 students (39,170) and a total budget of $24,649,428.00. The students as a district have an approximate pass rate of 75% in math, 86% in reading, an overall pass rate (passing both math and reading) of 65%.  This would suggest that the district is experiencing some shortcomings in their education of the students due to their less than stellar overall pass rate. However, if you were to compare the schools by their overall pass rate, then it becomes noticeable that the top 5 schools are all charter type schools, while the bottom 5 schools are all district type schools.  This would suggest that charter schools typically have better success than district schools.

 If we were to compare the average overall pass rate of each school by their school type we would see that the overall pass rate for charter type schools averages around 90%, while district type schools average around 54%. This comparison would confirm our assumption that charter schools have better success than district schools. 
 
As to the reason why this is, we can possibly extrapolate a reason by looking at the breakdown of the student’s scores by school spending per student and school size. It should be noted that charter schools typically had a smaller budget than district schools and so they typically had smaller spending ranges (<585, %585-630), whereas the district schools typically had a larger budget and  had higher spending ranges (%630-645, %645-680).  One would assume that a higher budget, accompanied by a larger spending range. would lead to a higher overall pass rate, due to their being more resources allocated. However, the opposite was found where the lower spending range schools experienced more success. This would imply that the less money is spent per student,  the more likely they will perform better; but, this notion would be incorrect when given context with the school sizing. 

When split into school size groups of  small(<1000), medium(1000-2000), and large(2000-5000) the schools that fell into the small and medium groups had approximate pass rates of 89-90%. This would mean that the smaller a school is, the more likely  the school would produce better results in their overall pass rate. What is interesting to note, is that the large group is made up entirely of district schools, whereas the small and medium groups consist of only charter schools. Given this context, we can conclude that while charter schools may spend less per student, their success is more dependent on having a small student body in comparison to district schools. The reason they spend less per student is more due to the fact that their budget is  generally smaller than district type schools. This would mean that funding does not necessarily have a large effect on students overall success, but rather the size of their school’s student body. 
