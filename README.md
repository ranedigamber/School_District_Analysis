# School_District_Analysis
# Overview of the analysis

The goal of this project was to assist Maria who is a chief data scientist for a school district analyze school funding and standardized test score. We had previously help Maria generate a concise summary of these analysis to be presented to the school district board and superintendents. Based on this analysis the school board later informed Maria that they discovered evidence of academic dishonesty. It appears that the ninth grade reading and math scores for Thomas High School have been tampered. We and Maria have been asssigned to null void all the ninth grade math and reading score from the affected school, while keeping the scores from others intact. As before we are to provide a summary as to how these changes affect the overall analysis

  Based on our primary task the election commission had further requested additional data for;
  1. Voter turnout in each county.
  2. Percentage of votes from each county out of the total count. 
  3. The county with the highest turnout.
The output of this analysis will be included in a text file that should be easy to read for audience of any background.

## Summary Results:
### How was the district summary affected
  * The inital analysis was performed on the total number of students inclusive of the 9th grader's from the Thomas High School. The figure below depicts the summary result of this analysis. 
  
  ![district_summary_before](https://user-images.githubusercontent.com/107159218/177902185-3897d557-8bed-4bb2-a659-b0c8aa62aa42.JPG)
  
  * The removal of the 9th graders from the analysis yielded a new summary that has very minor changes in the "average math" and the "% math, %reading and % overall passing" scores. The figure below depicts the new district summary.
  
  ![district_summary_after](https://user-images.githubusercontent.com/107159218/177902944-51f8a307-20f5-47f7-950b-3d9460cc7d01.JPG)

### **How was the school summary affected?**
  * The biggest change the occurs by removing the 9th graders of Thomas High School from the analysis affects Thomas High School. As we can see from the figure below, prior removal of the 9th graders, Thomas High School had an overall passing % of 90.95 and was ranked 2nd in all district schools. 
  ![School_summary_before](https://user-images.githubusercontent.com/107159218/177907336-a0402d29-d166-45eb-b98c-b39e9c1b1155.JPG)

 * After the exclusion of the 9th graders from the analysis this school the overall passing % drops to 65.08 (net ~26% drop). As a result the overall standing for this school also drops and the school is listed in the bottom 5 for the district. The figure below provides a summary of the school performance after removal of the 9th graders. 
 ![School_summary_after](https://user-images.githubusercontent.com/107159218/177907352-587eaa89-a9f4-42e4-8453-6181a5e8ebf8.JPG)

### **How does replacing the ninth grader's math and reading score affect Thomas High School's performance relative to the other schools?**
  * As pointed out the the section above replacing the 9th grader's math and reading school results in Thomas High School dropping from 2nd position to the 8th from the bottom in the school district ranking.


### How does replacing the 9th grade score affect the following:
1 Math and Reading Score by Grade
  * Due to the tampering of the 9th grade results from this Thomas High School the student grades were replaced with "nan". The math and reading score for these 9th graders were previously 83.6 and 83.7 respectively. The figures below are from the corrected analysis.
  * Avg Math Score
  
  ![Avg_math Score](https://user-images.githubusercontent.com/107159218/177909650-94adca49-2d88-4649-864f-963e180fcb04.JPG)

  * Avg Reading Score
  
  ![Avg_reading score](https://user-images.githubusercontent.com/107159218/177909669-2eb249b0-e27a-4c98-b89e-cf073faf744b.JPG)

2 Scores by school spending
  * 
### Election outcome
  
 
### Various features of the code
  
 
 
 
### Election Audit Summary
  
