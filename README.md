# Election_Audit_Analysis

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes eah candidate received
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code

## Election Audit Results
The analysis of the election shows the followings:

![](analysis/election_analysis.txt)

## Election-Audit Summary:

The dataset we've been given is somewhat limited with regards to who the voters really were. To be more precise, if the data has information about the political parties of each candidate, then we could have had an anaylsis on which political party each county is more aligned with and as a result we could also have a better idea on where the voters stand politically. With such information included in the dataset, we could simply add another `for` loop and `if statement` in the script and create an output that shows which county is democratic, republican, or etc.

Also, if each ballot ID was associated with voters' race and/or gender, I think this analysis could have demonstrated a lot more specific results. Just like with the political party, we could have had a section in the output that shows which race and/or gender tends to cast ballots for each candiate.
