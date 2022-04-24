# School_District_Analysis
An analysis of standardized tests

## Overview of the school district analysis: Explain the purpose of this analysis.

After performing an analysis on the local school districts high school standardized testing scores, evidence of academic dishonesty was brought to light by the school board. According to what they know, the reading and math grades for ninth graders at Thomas High School are compromised. Since the inclusion of this bad data has probably given us an inaccurate district summary, this analysis aims to remove the compromised data from the dataset and redo the previous analysis with results that exclude the bad data. After the analysis is done, we can compare the results and see how the district summary was affected and perhaps confirm that the data had been tampered with if it falls to far from district averages.



## Results: 

s

* How is the district summary affected?

    The school district as whole was **not significantly affected** by the bad scores. As we can see below, the old scores (upper) have nearly the same values as the scores adjusted for the removed data (lower). The makes sense; with 39,170 total students in the district the 9th graders at Thomas High school only make up roughly 1% of the total student base.

    #### **Original** 
    ![district_summary_old](Resources/district_summary_old.png)

    #### **After Reanalysis**
    ![district_summary_new](Resources/district_summary_new.png)

    While the difference itself is quite small, it should be noted that the district comes out looking a little worse overall after reanalysis, meaning that the scores that were removed were most likely above average. It will be much easier to see the impact by looking at the change in the Thomas High School scores alone.

* How is the school summary affected?

    The school itself felt a slightly greater impact but 

    #### **Original** 
    ![ths_summary_old](Resources/ths_summary_old.png)

    #### **After Reanalysis**
    ![ths_summary_new](Resources/ths_summary_new.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
* Scores by school spending
* Scores by school size
* Scores by school type

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
