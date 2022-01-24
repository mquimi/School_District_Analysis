# School_District_Analysis

### Overview of the School District Analysis:

The overall purpose of this analysis is for the school board to understand the different perfromance metrics, based on math and reading scores for various schools and school districts. While conducting the analysis, we ran into an issue of academic dishonesty for ninth graders at Thomas High School.

in order to prevent skewness to the analyasis, we have been advised to by Maria to convert all ninth grade Thomas High School's students to NaN (null value.)

Below are the two files that were used for this analysis:


- [Schools Files](Resources/schools_complete.csv)
- [Student Files](Resources/students_complete.csv)



### Results:

- How is the district summary affected?

Original analysis
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/original%20analysis.png)

Updated analysis
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/updated%20analysis.png)

- As you can see from the images above, the reading and math scores were not drastically imapcted. The changes from the original image to the updated image show a chage of less than .5%. It is also helpful to remember that there are only 461 9th graders at Thomas High school and a total of 39,170 students. If you do the math, 9th graders only make up 1.17% of the population, meaning grades arent impacted as much.


- How is the school summary affected?

School summary original
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/School%20summary%20original.png)

School summary with NaN
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/School%20summary%20with%20changes.png)


Based on the two images, you can see that there some 9th graders who had higher math scores than the rest of the school population. Reading scores on the other hand show that there were 9th graders who scorred lowerd than other students at Thomas High School.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


Math and reading scores by grade
Math Original
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/Math%20Original.png)

Math Updated
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/Math%20Updated.png)

Reading Original
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/Reading%20Origial.png)

Reading Updated
![alt text](https://github.com/mquimi/School_District_Analysis/blob/main/Image/Reading%20Updated.png)

- the only scores that were impacted by the 9th grade change are the 9th graders at Thomas High School. If wanted to calculate the average scores, then we will some changes because we will be calculating two completely different values.

Scores by school spending
- the school budget did not change when replacing 9th grade scores with NaN

Scores by school size
-  the school size did not change when replacing 9th grade scores with NaN

Scores by school type
- the school type did not change when replacing 9th grade scores with NaN

###Summary:

Changes that occured in the school district analysis after the ninth grade scores's at Thomas High School were replaced with NaNs were:

1. Average math score, passing math %, passing reading % and overall passing % all decreased at Thomas High School
2. The overall passing % for the entire district decreased due to Thomas High School overall passing % decrease
3. Charter school scores resulted in a reduction with the 9th grade changes happening
4. Schools like Wright High School moved into the top 5 high school districts when changes happened
