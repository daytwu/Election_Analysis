# Election_Analysis

## Project Overview

### Overview of Election Audit

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

Purpose of this eleciton audit analysis is to find out who the candidates are within this election and how many votes did each candidate get, as well as finding out which county participated the most in the election voting process.

### Election-Audit results

<img width="248" alt="Election_audit screenshot" src="https://user-images.githubusercontent.com/68725398/92498929-3cdc1c00-f1c9-11ea-8052-ed5ad67cbe07.png">

- How many votes were cast in this congressional election?

  + There are a total of 369,711 votes cast in this congressional election.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  + Of the total 369,711 votes, 10.5% (38,855) of the votes are from Jefferson County, 82.8% (306,055) votes are from Denver County and 6.7% (24,801) votes are from Arapahoe County.

- Which county had the largest number of votes?
  + Denver County had by far, the largest amounts of votes cast in this election. At 306,055 votes, it is nearly 8 times more than Jefferson, the second largest county.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  
  There are 3 candidates for this election. 
  + Candidate 1, Charles Casper Stockham, received 23.0% of the total votes cast (85,213). 
  + Candidate 2, Diana DeGette, received 73.8% of the votes casted (282,892). 
  + Candidate 3, Raymon Anthony Doane, received 3.1% of the votes casted (11,606).

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  + Candidate 2, Diana DeGette is the winner of the election, with an overwhelming 73.8% (282,892) of the total votes casted, an absolute landslide victory.

### Election-Audit Summary

|file_to_load = os.path.join("Resources", "election_results.csv")|

This script can be modified for any election as long as the .csv file path and name is known and the file data is understood correctly in terms of which columns contained what data. For the file path, this could be done within the same folder instead of declaring it within any other subfolders. The columns for the candidate names and the counties are currently set to columns 1 and 2 within the file, which means the script just needs to have the referenced columns updated to match any new files to be loaded into. Alternatively, this can be manually entered as an input box too.




## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.38.1
  
  ## Challenge Overview
  
  ## Challenge Summary
  
  
