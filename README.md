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




