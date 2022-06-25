# Election_Analysis

## Project Overview
This is an election audit of a local congressional election which recently occurred.  The election audit is being conducted for the Colorado Election Commission.  The required tasks for the audit are listed below:

1. Tally the total number of votes cast.
2. Provide a complete list of counties that cast votes in the election.
3. Calculate the total number of votes, or voter turnout for each county.
4. Calculate the total number of votes cast in each county.
5. Calculate the total percentage of votes cast in each county.
6. Determine the county with the highest voter turnout.
7. Provide a complete list of candidates who received votes.
8. Calculate the total number of votes that each candidate received.
9. Calculate the percentage of votes each candidate won.
10. Determine the election winner  based on the popular vote.

## Resources
- Data Source: election_results.csv
-  Software: Python 3.7.6, Visual Studio Code, 1.68.1

## Election-Audit Results
The analysis of the election returned the following results:
- There were 369,711 total votes cast in the election.
- The following counties cast votes in the election:
    - Jefferson
    - Denver
    - Arapahoe
- The county results were:
    - Jefferson County turned out 10.5% of the vote with 38,855 number of votes.
    - Denver County turned out 82.8% of the vote with 306,055 number of votes.
    - Arapahoe County turned out 6.7% of the vote with 24,801 number of votes.
- The following candidates received votes:
    - Charles Casper Stockholm
    - Diana DeGette
    - Raymon Anthony Doane
- The county with the largest voter turnout was: Denver County
- The candidate results were:
    - Charles Casper Stockholm received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
This project utilized Python [repetition statements and conditional statements](https://docs.python.org/3/tutorial/controlflow.html) with [logical operators](https://docs.python.org/3/library/stdtypes.html#boolean-operations-and-or-not) to calculate, develop, and analyze the election data to produce the required results. Next, the script uses print statements to print out the election analysis sorted by county and by candidate to the command line.  

![Results_Printed_To_Terminal](https://github.com/mewers2/election-analysis/blob/main/Resources/Results_Printed_To_Terminal.png)

The election analysis is also printed to a text file for submission to the Colorado Election Commission. 

![Results_Printed_To_Text_File](https://github.com/mewers2/election-analysis/blob/main/Resources/Results_Printed_To_Text_File.png)

This script could be used for any other election. It could be modified to provide additional analysis, perhaps by political party, or by age range, or gender, based on any additional voter data.  
