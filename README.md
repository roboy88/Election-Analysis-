Election_Analysis
Project Overview
A Colorado Board of Elections employee has tasked you with completing the audit of a local congressional election

Calculate the total number of votes.
Get a complete list of candidates who recieved votes.
Calculate the total number of votes each candidate recieved.
Calculate the percentage of votes each candidate won.
Determine the winner of the election based on popular vote.
Resources
Data Source: election_results.csv Software: Python 3.10, Visual Studeio Code 1.68.1

Summary
The analysis of the election shows: There were 369,711 total votes cast in the election.

The candidates were:

Charles Casper Stockham
Diana DeGette
Raymond Anthony Doane
The results were:

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
-The winner was Diana DeGette with 73.8% of the vote at 272,892 votes cast

Challenge Summary
All the counties listed in the original csv file:

Jefferson
Denver
Arapahoe
A breakdown of the votes by county shows:

Of the total 368,711 votes cast,

Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)
Denver county had the largest turnout of 82.8% of the total ballots cast and 306,055 votes cast total.

This script can be used for any election by feeding it raw data in .csv file format similar to the original file provided, as long as the ballot ID is in column A, county in column B, and candate name is in column C. The script looks for names and numbers in the spreadsheet and assigns variables based on what it reads in the file. Candidate names, county names, and votes can be replaced in the spreadsheet and the script will calculate it all over again.
