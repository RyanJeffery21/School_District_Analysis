# School District Analysis

# Purpose
A school district asked for an analysis of reading and math scores across the district broken down to include scoring as it relates to school type, budget per student, and enrollment size.  After reviewing the data, the school board was made aware of potential cheating in the 9th grade class of Thomas High School.  The data from this class was removed and the data was analyzed again for comparison.

# Results

## District Scoring

Original Analysis
![Original District](https://github.com/RyanJeffery21/School_District_Analysis/blob/6d0ebd7b1f49b27121533ad062d452b20652b08f/Resources/Original%20District.png)

Adjusted Analysis

![Adjusted District](https://github.com/RyanJeffery21/School_District_Analysis/blob/6d0ebd7b1f49b27121533ad062d452b20652b08f/Resources/Adjusted%20District.png)

As we can see, changing the 9th grade class' scores to NaN had a very small impact on the overall district scoring.  The student counts were left the same for this graphic, only the scores were removed.  In the following graphics, the students and their scores have both been removed to provide a more accurate percent.

## How is Thomas High Affected?

Original Scores:

![Thomas High Original](https://github.com/RyanJeffery21/School_District_Analysis/blob/6d0ebd7b1f49b27121533ad062d452b20652b08f/Resources/Thomas%20High%20Original.png)

Adjusted Scores:

![Thomas 1012 Adjusted](https://github.com/RyanJeffery21/School_District_Analysis/blob/0c0058d0af90d148d5972de24b1e67ceb7340c63/Resources/Thomas%20High%2010_12%20Adjusted.png)

After removing the ninth graders completely and just running the analysis on Thomas High 10th, 11th, and 12th graders, we can see that the schools overall performance did not suffer.  All passing percentages differed by less than a half a percent after removing the 9th graders from the results.

## School Rankings

Original Ranking:

![Top Schools Original](https://github.com/RyanJeffery21/School_District_Analysis/blob/0c0058d0af90d148d5972de24b1e67ceb7340c63/Resources/Top%20Schools%20Original.png)

Adjusted Ranking:

![Top Schools Adjusted](https://github.com/RyanJeffery21/School_District_Analysis/blob/0c0058d0af90d148d5972de24b1e67ceb7340c63/Resources/Top%20Schools%20Adjusted.png)

As we can see, Thomas High remained in the number two spot after the 9th graders were purged from the data.  With Thomas High's scores remaining virtually the same after removing the 9th grade, none of the other metrics were greatly affected.  The scores by school spending, scores by school size, and scores by school type analysis all remained virtually unchanged from the original analysis that had the cheating data included.


# Summary
Removing the 9th graders did not have a significant impact in any category as the school's scores remained consistent throughout all grades.  Had we left the students in but just left the scores as NaN, it would have greatly affected the schools percentages but doing so would not have been the correct way to analyze the school as a whole.




