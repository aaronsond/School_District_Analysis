# School District Analysis

## Overview
We filtered through test data from a school district, in order to understand the school variables that correlated with student performance, as measured by student reading scores, math scores, and overall passing rates. Many Correlations were found, although the mechanism for causality is not in the scope of this project. As part of this analysis, we removed certain data that appeared to be academic dishonesty. This created variance from the data pre-removal.

## Results
![No filter THS](Resources/THS_no_filter.PNG)
![Filtered THS](Resources/THS_filter.PNG)

* District level affect of removing potentially dishonest scores: Thomas High School moves on average, from Math scores of 83.42, to 83.35. and reading scores move from 83.85 to 83.9. This removal decreases, albeit slightly, district level scores
* The school summary ends with a non applicable value for the 9th grade class, given the doubts of academic honesty raised by the school board. 
* When the 9th grade scores from THS are removed, we see a percent passing rate that is slightly lower. Without removing this data, THS students passed math at a rate of 93.27%, and reading at 97.31%. With this filter, the passing rates are 97% for reading, and 93.19% for math.
* The effect of these score changes is minimal across the data set. 
*   By grade, Thomas High School has no results for 9th grade, but the rest of it's scores are unaffected. 
*   Spending by school is unaffected when averaging out across schools. Any affect in by school size is similarly lost in averages and rounding, and similar with overall results by school type

## Summary
Once the results have been modified to control for potential academic dishonesty, we lost any data for the 9th grade at Thomas High School. The average scores for the district were not strongly shifted, but it decreases district level scores slightly. It shifts entirely future models and expectations for the 9th grade class, since these scores are not to be trusted. The potential academic dishonesty reduces confidence in the administration and future scoring of Thomas High School. 
