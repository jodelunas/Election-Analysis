# Election-Audit

## Overview of Election Audit
The purpose of this audit was to add the following additional data to complete the audit.

1. The voter turnout for each county.
2. The precentage of votes from each county.
3. The county with the largest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The audit of the election show that:
- There were 369,711 votes cast in the election.
- The county results were:
  - Jefferson County had 10.5% of the vote and 38,855 number of votes.
  - Denver County had 82.8% of the vote and 306,055 number of votes. 
  - Arapahoe County had 6.7% of the vote and 24,804 number of votes.
-The county with the largest voter turnout was:
  -Denver County with 82.8% of the vote and 306,055 number of votes.
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diane Degette who recieved 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
The script as written, can be used as written for other districts or states within the parameter used here. Since most elections have more than one seat being elected, some simple modifications can be made to accomidate this. For every seat I would need to create a list and dictionary to hold their names and votes. I would need to extract name from the corisponding row in the data and track their votes. Use if statements to retrieve the candidates and calculate the winner. I would need  a for loop to determine the percentage of votes for the candidate. Then just print the results.
