## Project: School_District_Analysis
Working with Anaconda, Jupyter Notebook, Python and Pandas to analyze data for a school district.

### Overview of the school district analysis
This challenge involved working with the school district to create a program that could efficiently interpret a large dataset of high school students in one school district and display easy-to-read tables that show the student scores within certain grades and schools.  Here are list of required deliverables from the district:

    - Provide information related to the Thomas High School excluding the ninth year.
    - Provide an overview of the key metrics for each school in table format
    - Provide a snapshot of the district's key metrics presented in table format
    - List the top five and bottom five performing schools based on the overall passing rate
- Caculate the average math and reading scores by students in each grade level
- List school performance based on budget per student, school size and type of high school.

### Results

By excluding the ninth year of the Thomas High School, figures have not changed dramatically on a global basis, while the impact on the school in particular becomes more relevant.

From an overall point of view the impact of excluding then ninth year of Thomas High Scholl do not have a significant impact on a district level:

Original results:
![Original Results](/Resources/District_Summary_old.png)

New Results:
![Original Results](/Resources/District_Summary_new.PNG)

On the contrary, excluding the ninth year change dramatically the performance of the Thomas High School by 26 points in reading 27 points in math and 25.5 points in the overall. This change put THS "on track" in comparison with other "Charter" similar-size schools. In fact makes THS to rank second on the district.

It is quite obvious that there have been a problem with the information related to the 9th grade of THS and a further analysis should be performend in order to determine if there was a mistake on the information, how it was collected or if there is indeed something to correct in the school to improve results on the 9th grade. What is clear is that the information provided was not in line with the rest of the information of THS or similar schools in the district.

### Summary of data analysis

The tools used in this challenge were Anaconda, Jupyter Notebook, Python and Pandas.  It was great to utilize the functionality of all the tools combined to create a user-friendly program that effortlessly depicts such important data.  As mentioned before the reading and the interpretation of the data is flexible with this customized program.  If new data can be provided in the same format this script can easy read, merge, format and output clear statistical findings that can add to key decision making.  Refactoring this code should be just as simple with the right tools and minor manipulation.

By conducting this analysis, the school district can effectively determine their next steps in terms of funding per student capita, per school, and even per grade based on the results provided.  The data shown will allow also coduct a comparison of the student success percentages on reading versus math, the passing percentages and the overall percentages of passing students.  The performed analysis has also included grouping of student scores by the school spending, the school size and the type of school.

This code could be much more useful with a bit more of Phyton coding, a better interaction with the user could allow this code to read any comma-delimited (.CSV) dataset with the same formatted columns.  Simply change the name of the file and the analysis can be determined in the same manner.  Different types of datasets can also be read, by tweaking and refactoring the code to gain the same benefits.  As long as the source of the data can be verified, then the data will be accurately depicted.

This program was written to automate and calculate the passing percentages of a dataset for this entire school district and, for that matter, can be utilized for many school districts in a very efficient manner.  It will also help in determining the total budgetary amounts per capita, per grade, per school if those metrics are analytics are necessary data points.
 
With the analysis we can conclude that Charter schools perform better than District schools, smaller schools provide better results than large ones.

It is important to notice that as a results of the analysis, apparently the less-founded schools provide better results that those with bigger budget, but a deeper analysis will tell us that the driver to reach that figures is not the amount spend by student but the type of school. All those scholls that appears on the first bin are charter schools that as we saw before, perform better thant the district ones.