# Election_Analysis

## Project Overview

- Background information:
A Colorado Board of elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the percentage of votes each candidate won.
5. The winner of the election based on popular vote.

![image](https://user-images.githubusercontent.com/107363048/178186079-ba621f37-c348-4790-a1af-496ba94042bb.png)

- The purpose of this review was to create a Python based code that would automatically calculate the 1 - 5 listed items above.


## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results:
1. How many votes were cast in this congressional election?

 - There were 369,711 total votes total.

2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

 - Jefferson county had 10.5% of the total votes with 38,855 individual tallies.

 - Denver county had 82.8% of the total votes with 306,055 individual tallies.

 - Arapahoe country had 6.7% of the total votes with 24,801 individual tallies.

3. Which county had the largest number of votes?

 - Denver county had the largest voter amount.

4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

 - Charles Casper Stockham had 85,213 votes at 23% of the total.
 - Diana DeGette had 272,892 votes at 73.8% of the total.
 - Raymon Anthony Doane had 11,606 votes at 3.1% of the total.

5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

 - Diana DeGette won the election with 272,892 total votes which accounted for 74% of the total.


## Election-Audit Summary

The code built to calculate the total votes, counties, percentages, and candidates can be reused consistantly if new elections are run using a similar CSV format regardless of region or candidates. 

1. State Additon Example

- If additional columns are added to include states for a potentially larger election, simple if statements can be added into the code to account for the new columns added to calculate state combind totals.

2. Candidate Votes By County Addition

- A piece of useful information would be adding an additional line of code to account for each candidate vote total per county as this would give each candidate an idea of where time should be invested should another election come up.
