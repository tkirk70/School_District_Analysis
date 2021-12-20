# School_District_Analysis
OSU Module 4 - Jupyter and Pandas


## Overview of the school district analysis: Explain the purpose of this analysis.

Analysis was done twice on the school district dataset.  Once for the raw testing numbers reported and a second time after removing questionable results from one grade of one school.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
  All averages are lower after adding Nan values for Thomas High School 9th graders math and reading scores.
- How is the school summary affected?
  Thomas High School scores were affected dramatically with overall passing %'s going from ~90% all the way down to 65.1%.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  After averaging 10th-12th graders and adding that average back to the per_school_summary, Thomas High School once again finished second in overall passing %.


## How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
  Nans greatly affect this dataframe.
- Scores by school spending
  Negative corrolation continues for this data frame: spending v performance.
- Scores by school size
  Larger schools continue to struggle.
- Scores by school type
  Charter schools continue to outperform District Schools.

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

There is a large difference whether we count all students or all students whose tests were validated.  The original numbers reported for Thomas High School 9th graders were in line with the average of 10th-12th graders.
