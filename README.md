# Election_Analysis

## Project Overview
A Colorado Board of Elections employees need the following tasks completed to perform an election audit of a recent local congressional election. 
1. Calculated the total number of votes.
2. Get a complete list of candidates who have recieved votes.
3. Calculate the percentage of votes each candidate won
4. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6 and Visual Studio Code, 1.64.2

## Summary 
The analysis of the election showed that:

- There were 369,711 votes
- The candidates were:
  - Charles Casper Stockham
  - Diane DeGette
  - Raymond Anthony Doane

- The candidate results were:
  - Charles Casper Stockham recieved 23.0% and 85,213 votes
  - Diana DeGette recieved 73.8% and 272,892 votes
  - Raymon Anthony Doane recieved 3.1% and 11,606 votes

- The winner of the election was:
  - Diana DeGette who recieved 73.8% of the vote and 272,892 votes

## Challenge Overview

### Overview of Election Audit
The goal of this project is to determine the election results for the election commission of Colorado to complete their audit. The election results include the following data which was synthesized by taking data from a provided election_results.csv file, uploading the file in VS code, coding the results using Python programming language and saving the election results to a text file:
![Election_Results_Terminal](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election%20Results%20Terminal.png?raw=true)
![Election_Results_Text_File](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election%20Results%20txt.png?raw=true)

### Election-Audit Results
From this project the follow was assertained for the election commission:

There were a total of 369,711 votes cast. 

![Election_Results_Total_Votes](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election_Results_Total_Votes.png?raw=true)

The breakdown of the number of votes and the percentage of total votes for each count in the precinct was:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

![Election_Results_County_Breakdown](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election_Results_County_Breakdown.png?raw=true)

The county with the largest number of votes or largest turnout was Denver:

![Election_Results_Largest_Number_Votes](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election_Results_Largest_Number_Votes.png?raw=true)

The breakdown of the number of votes and the percentage of the total votes each candidate recieved was:
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

![Election_Results_Candidate_Breakdown](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election_Results_Candidate_Breakdown.png?raw=true)

The candidate that won the election was Jefferson County's Diana DeGette with a winning vote count of 272,892 and 73.8% of the total votes.

![Election_Results_Winning_Candidate](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Election_Results_Winning_Candidate.png?raw=true)

## Challenge Summary

### Election-Audit Summary: 
This script can be used for any election as long as the data file contains the same voter information - voting ballots cast, geograpical running area and candidate information. With a few modifications this script could even be used to asertain election results at the state level by subing out coding that pulls 'county' infomation with 'state' information. For example, when creating the county list and dictionary one could sub out county for state information:

![County_to_State_code](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/County_to_State_code.png?raw=true)

Additionally, if one desired they could also find the county with the lowest turnout for further investigation, i.e., voter accessability, potential gerrymandering, etc. To do this one would need to first track the smallest county turnout by adding the below step to the code: 

![Smallest_County_Code](https://github.com/adecoste2/Election_Analysis/blob/main/Resources/Smallest_County_Code.png?raw=true)

