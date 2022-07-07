# School_District_Analysis
# Overview of Election Audit

The goal of this project was to assist Maria who is a chief data scientist for a school district analyze school funding and standardized test score. We had previously help Maria generate a concise summary of these analysis to be presented to the school district board and superintendents. Based on this analysis the school board later informed Maria that they discovered evidence of academic dishonesty. It appears that the ninth grade reading and math scores for Thomas High School have been tampered. We and Maria have been asssigned to null void all the ninth grade math and reading score from the affected school, while keeping the scores from others intact. As before we are to provide a summary as to how these changes affect the overall analysis

  Based on our primary task the election commission had further requested additional data for;
  1. Voter turnout in each county.
  2. Percentage of votes from each county out of the total count. 
  3. The county with the highest turnout.
The output of this analysis will be included in a text file that should be easy to read for audience of any background.

## Election-Audit Results:
### Total number of votes casted in the congressional election
  * This election saw a good voter turnout and a total of **369,711** votes were casted across three counties. 

### Summary of number of votes and the percentage of total votes for each county in the precinct
  * The result of the number of votes cast and percentage of total votes are as follows:
    * Denver county: 82.8% (306,055)
    * Jefferson county: 10.5% (38,855)
    * Arapahoe county: 6.7% (24,801)

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
