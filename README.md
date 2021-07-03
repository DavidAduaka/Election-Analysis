# Election-Analysis

## Project Overview
A colorado Boad of Elections employee has given you the following tasks to complete eleciton audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get the complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidiate won.
5. Determine the winner of the election based on popular vote.

## Resources 
-  Data Source: election_results.csv
-  Software: Python 3.7.6, Visual Studio Code, 1.57

## Summary 
The analysis of the election show that:
-  There were 369,711 votes cast in the election. 
-  The candidates were:
     -  Charles Casper Stockham
     -  Diana DeGette
     -  Raymon Anthony Doane 
-  The candidate results were:
     -  Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 
     -  Diana DeGette received  73.8% of the vote and 272,892 number of votes.
     -  Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
-  The winner of the election was:
     -  Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
To complete the audit the election commision requested some additional data:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout 

## challenge Summary 
With these results, the election commission has the data necessary to improve voter turnout in specific counties. Mainly, Arapahoe. As voter turnout increases, the code has to able to handle larger datasets and run more efficiently. For this I propose modififying two things in the code the first being, using while loops instead of for loops because they take less time to run, and second defining data structures as tuples instead of lists because they are easier to iterate over. 
