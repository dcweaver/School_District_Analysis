# School_District_Analysis

## Overview of School District Analysis
The purpose of this analysis was to use apply the skills learned in working with the numpy and pandas packages for python in order to clean, filter, sort, and display data in dataframes for the school disctrict. By removing ninth grade reading and math scores from the data, we are able to get a clear picture of the academic abilities of the students at Thomas High School. 

## Results
* **How is the district summary affected?**

Shown below are the disctrict summaries both before and after the ninth grade scores from Thomas High School had been filtered.

![with ninth grade](/Resources/dist_summary_unfiltered.png)

![filtered ninth out](/Resources/dis_summary_filtered.png)

The image above shows the district summary with all of the data for the disctrict, even the ninth graders at Thomas High School that have been accused of academic dishonesty. As you can see in the bottom image, even after filtering the fraudulent data, the overall scores are relatively the same, meaning that there was not enough outlier scores at Thomas High School to affect the overall district by themselves. 

* **How is the school summary affected?**
As you can see in the image of the dataframe below, before filtering out the ninth grade scores for reading and math at Thomas High School, the overall passing percent of students is at about 65%, with the numbers passing for reading and math being 66 and 69%, respectively. 

![school summary unfiltered](/Resources/per_school_unfiltered.png)

After filtering the ninth grade scores, however, the passing rates for all categories at Thomas High School skyrocketed. The overall passing percentage at Thomas High School is now over 90% and both reading and math passing percentages are even higher than that at 93% and 97% respectively.

![school_summary_filtered](/Resources/per_school_filtered.png)

* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?** 

Shown below is a dataframe listing the top five performing schools in the disctrict. After filtering out the ninth grade data from the dataset, Thomas High School instantly catapulted to the top, becoming the second highest performing school in the district overall. 

![top schools](/Resources/top_schools.png)

* **How does replacing the ninth-grade scores affect the following:**

** Math and reading scores by grade

After removing ninth grade scores, the average math and reading scores for each grade at Thomas High School are all between 83% and 84%. An average grade for every grade being a B falls in line with where we see most of the other averages at schools in the district, and shows that Thomas High School is consistently performing well.  

** Scores by school spending

Thomas High School is in the middle range of spending per student, falling into the $631-$645 per student range. When compared to other schools in that spending range per student, as shown below, Thomas High School vastly outperforms their spending counterparts. 

![spending per student](/Resources/spending_ranges.png)

** Scores by school size

Thomas High Schools falls into the medium sized school range (between 1000-2000). It performs about the same as all other schools in that size range, with average scores in the mid 80's and an overall passing percentage right at 91%. 

** Scores by school type

Thomas High School, along with all other Charter schools in the district, perform much better overall than the district schools that are not charter schools in the area. The dataframe below confirms this, with Thomas High School matching all of the categories almost exactly.

## Summary

In summation, by removing the ninth grade reading and math scores from the data at Thomas High School caused major changes. Firstly, their overall passing percentage went way up, from in the 60's to in the 90's. This segue'd into raising the scores and passing percentage for all other charter schools in the disctrict, now that Thomas High wasn't bringing the scores down. Thirdly, this affected the data when grouping schools by amount spent per student, raising the percentages for all schools in the same spending range. Lastly, it positively affected the avg scores and overall passing percentage for all medium sized schools in the district. 





