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


### How was the school summary affected
    * The biggest change the occurs by removing the 9th graders of Thomas High School from the analysis affects Thomas High School. As we can see from the figure below, prior removal of the 9th graders, Thomas High School had an overall passing % of 90.95 and was ranked 2nd in all district schools. 
    ![School_summary_before](https://user-images.githubusercontent.com/107159218/177905913-fc9efb99-7c42-4e3e-b5b4-3f85cae7b618.JPG)

    * After the exclusion of the 9th graders from the analysis this school the overall passing % drops to 65.08 (net ~26% drop). As a result the overall standing for this school also drops and the school is listed in the bottom 5 for the district. The figure below provides a summary of the school performance after removal of the 9th graders. 
    ![School_summary_after](https://user-images.githubusercontent.com/107159218/177906259-0c9dad97-45cc-4aa5-a99b-0f8f4fe3fdcd.JPG)


### County with largest number of votes
  * **Denver county** had the largest voter turnout

### Summary of number of votes and the percentage of total votes for each candidates overall
  * The following is the tabulated result for total votes and percentage of the total for the three candidates:
    * **Diana DeGette: 73.8% (272,892)**
    * Charles Casper Stockham: 23.0% (85,213)
    * Raymon Anthony Doane: 3.1% (11,606) 

### Election outcome
  * The winner for this election was:
    * ***Diana DeGette*** who received **272,892** votes which was **73.8%** of the total votes casted.
 
### Various features of the code
  * How to get candidate vote count
 
 ![Code Candidate vote count](https://user-images.githubusercontent.com/107159218/176787617-18729b4d-f7fc-45b2-b9c1-f8c46c1c9dea.JPG)

  * How to get county vote count
 
 ![Code_countyvote count](https://user-images.githubusercontent.com/107159218/176787653-9dc5d13d-2cc9-4b7e-ad4d-94774a4a4e1e.JPG)

  * How to get candidate votes percentage
 
 ![Code_Candidate votes and their percentage](https://user-images.githubusercontent.com/107159218/176787717-54dc6077-5213-42a3-b38d-d2ef5ffb072c.JPG)

  * How to get county vote percentage
 
![Code_percentage of county votes](https://user-images.githubusercontent.com/107159218/176787780-d7fbdc41-35c7-4745-b9b6-1f68e7e2f016.JPG)

  * How to get total votes casted
  
 ![Code_total vote count](https://user-images.githubusercontent.com/107159218/176787828-ebb1f835-095e-4e80-9e57-3bc9e8898b37.JPG)

 
### Election Audit Summary
  * The script could be modifed for a national level elections, for example in this audit we declared a dictionary with *key=county* and *value=votes*. In a similar fashion we could use a dictionary of list with *key=states* and *values=[list of counties]*
  * We could also use modify the script to iterate over results from past years or they type of ballots cast (mail in, hand counted or computer counted) which could provide more statistical information and reveal any underlying trends or preferences 
