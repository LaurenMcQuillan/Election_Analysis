# Election Analysis

## Overview of Election Audit

A board of elections employee has requested an audit of election results for a U.S. congressional precinct in Colorado. The request is that the analysis be done in Python, so that if the audit is successful, the Python code can be used to audit other congressional districts as well. Votes were collected by three voting methods: mail-in ballots, punch cards, and direct recording electronic counting machines. The voting data has already been gathered, so it was requested that I report the following based on voting data:

1.	The total number of votes cast
2.	The total number of votes for each candidate
3.	The percentage of votes for each candidate
4.	The winner of the election based on the popular vote
5.	The voter turnout for each county
6.	The percentage of votes from each county out of the total vote count
7.	The county with the highest turnaround

The three candidates in this election were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. Votes were collected from Jefferon, Denver, and Arapahoe counties.

## Election Audit Results

*	There were 369,711 total votes cast in this congressional election
*	Total number of votes and percentage of total vote by county:
    * Jefferson County voters submitted 38,855 votes, making up 10.5% of the total votes
    * Denver County voters submitted 306,055 votes, making up 82.8% of the total votes
    * Arapahoe County voters submitted 24,801 votes, making up 6.7% of the total votes
* Denver County had the highest number of votes submitted
* Total number of votes and percentage of total vote by candidate:
    * Charles Casper Stockham received 85,213 votes, making up 23.0% of the total votes
    * Diana DeGette received 272,892 votes, making up 73.8% of the total votes
    * Raymon Anthony Doane received 11,606 votes, making up 3.1% of the total votes
* Diana DeGette won the election with a total of 272,892 votes, making up 73.8% of the total votes

![election_results_txtfile](https://user-images.githubusercontent.com/115508658/200401596-3ba9ff2e-db52-4ff1-b4f4-c924d0b42ef2.png)

## Election Audit Summary

Since the script was able to successfully calculate total vote and percentage of total vote by county and by candidate as well as the winning candidate and the county with the highest voter turnout, the script could be used without modification for other congressional district elections if the dataset is in the same format as the original dataset. The script could also be modified and reused for other election types. Two examples of possible modifications are:

1.	This script could be modified to be used for presidential elections to calculate the popular vote.  It could also be interesting to add in the voter’s state if it were collected in the original dataset. This could be done by following the same steps that were followed to add in county voter information, with the additions being state specific. I could initialize a state list and dictionary, initialize variables for highest state voter turnout and the number of votes by state, find the state name by row and find the unique state names, find the voter turnout by state, calculate the state’s voter turnout as a percentage of the total votes, and then add in print statements to print the additional information to the terminal and election_results text file.

2.	Another way that this script could be modified is if additional voter demographic data were collected, we could look at the specific demographics to determine which demographic group had the highest voter turnout, just like we used the script to find the same information by county.



