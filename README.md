# Election_Analysis
## Overview of Election Audit
### The purpose of this election audit is to tally votes from three counties and determine:
#### The number of votes each candidate received and the percentage of the total
#### The votes cast by county and the percentage of the total
#### The county with the largest number of votes
#### The winning candidate
## Election-Audit Results
### Total Votes Cast
#### Total Votes: 369,711
### Number of Votes and Percentage of Total for each County
#### Jefferson: 10.5% (38,855)
#### Denver: 82.8% (306,055)
#### Arapahoe: 6.7% (24,801)
### County with Largest Number of Votes
#### Denver
### Number of Votes and Percentage of Total for each Candidate
#### Charles Casper Stockham: 23.0% (85,213)
#### Diana DeGette: 73.8% (272,892)
#### Raymon Anthony Doane: 3.1% (11,606)
### Candidate with Largest Number of Votes and Percentage of Total
#### Winner: Diana DeGette
#### Winning Vote Count: 272,892
#### Winning Percentage: 73.8%
## Election-Audit Summary
#### This script can be used to determine the same election results as above for future elections given that the data are in the same format. The data will need to be in a csv file and contain 3 columns in this order: Ballot ID, County, and Candidate.
### Modifying the Script
#### The script can be altered in line 9 to reference the new the input data: 

~~~~~~~~~~~~~~~~~~~~~
<file_to_load=os.path.join("Resources","election_results.csv")>'
~~~~~~~~~~~~~~~~~~~~~

#### The script can similarly be changed in line 11 to print the results to a new text file:

~~~~~~~~~~~~~~~~~~~~~
'<file_to_save = os.path.join("analysis", "election_results.txt")>'
~~~~~~~~~~~~~~~~~~~~~
