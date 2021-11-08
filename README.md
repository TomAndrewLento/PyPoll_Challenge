# PyPoll with Python

## Overview of Election Audit
	Provide the election commision with an analysis of the voter turnout for each county, the percentage from each county of the total count, and the county with the highest turnout

## Election-Audit Results
-------------------------
Total Votes: 369,711
-------------------------

County Votes:
Arapahoe
Votes: 24,801
Percentage of Total: 6.7%

Denver
Votes: 306,055
Percentage of Total: 82.8%

Jefferson
Votes: 38,855
Percentage of Total: 10.5%

-------------------------
Largest County Turnout: Denver
-------------------------

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------


## Election-Audit Summary
	As this script currently exists, it can parse any .csv with Ballot ID, County, and Candidate, producing an analysis like the one seen in Election-Audit Results.  
	If all Voter IDs for each county were provided in the data set, ie including those who did not vote.  A 'voter turnout' percentage could be provided in the analysis.
	If the data set provided the time, date, and facility in which the Ballots were cast, the script could determine how crowded each facility was at what time, thereby providing us with the analytics with which to improve voter accessibility.
