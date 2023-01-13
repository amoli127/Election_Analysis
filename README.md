# Election_Analysis

## Project overview
Assisted a Colorado board of elections in an election audit of the tabulated results for a U.S. congressional precinct in Colorado. Tom, a Colorado election board member, needs assistance with an audit of the election results. Tom's manager wants to know how the vote auditing process can be automated using Python.

To determine the winner of the elections, votes will be counted from the three primary methods, punch cards, direct recording electronic (DRE), and mail-in ballots. The following tasks will be performed to complete the audit of the election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.

## Resources
-Data Source: election_results.csv

-Software: Python 3.9.13, Visual Studio Code, 1.74.3

## Summary

The analysis of the election show that:
There were "x" votes cast in the election. 
The candidates were: 
  - Charles Casper Stockham 
  - Diana DeGette 
  - Raymon Anthony Doane 
  
The winner of the election was: 
  - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.


## Election-Audit Results

When analyzing the data of the election results, we verified the following results.

* There were a total of **369,711** votes in the congressional election.

* The following are the results breakdown per county:

    * Jefferson county received 10.5% of the votes, with a total of 38,855 votes.
    * Denver county received 82.8%, with a total of 306,055 votes.
    * Arapahoe county received 6.7%, with a total of 24,801 votes.

* The county with the largest number of votes was **Denver** county with 306,055 total votes.
* The following are the results breakdown per candidate:


  * Charles Casper Stockham received 23% of the vote and 85,213 number of votes. 
  * Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
  * Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

* The winner of the election was: 
  - Candidate *Diana DeGette*, who received **73.8%** of the vote and **272,892** number of votes.
 
 ## Election-Audit Summary:
 
Analyzing the results of the elections, we performed a count of the total votes, and we made a breakdown between candidates and counties of the State of Colorado. Although this type of process can be done manually or using different software, Python is a tool that allows the automation of this process. Thanks to the algorithm we created to count the votes in these elections, the results of this U.S. Congressional race can be certified. Below we can see an example of the code that we used to count the votes each candidate received.

 
 ![image](https://user-images.githubusercontent.com/117063056/212238100-47819306-29c6-41fd-859a-b0409c2e3018.png)
 
This same code can be modified and applied to other processes.

* One of those examples could be to implement the code for the presidential elections and help in the breakdown by state.

* Another example would be to implement it in a business, such as a car dealership, and do a sales count to determine each salesperson's percentage and evaluate their efficiency.
 
 
