# Overview of Project #
The purpose of this Project is to analyze and audit the Election Outcome for a recent local congressional election, to determine the winning candidate and the largest voter turnout based on county. The analysis required the following data to be presented:
1. The total number of votes cast.
2. The list of candidates in the election.
3. The total number of votes received by each candidate.
4. The total number of voter turnout for each county.
5. The percentage of votes for each candidate.
6. The winner of the election based on popular vote. 
7. The county with the highest turnout.

# Resources #
Data Source: election_results.csv <br>
Software: Python 3.10, Visual Studio Code, Excel

# Election Audit Results #
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The county results were:
  - Jefferson County received a total of 38,855 votes, which accounts for 10.5% of the total votes. 
  - Denver county received a total of 306,055 votes, which accounts for 82.8% of the total votes. 
  - Arapahoe county received a total of 24,801 votes, which accounts for 6.7% of the total votes.

- The county with the largest voter turnout was: Denver 

- The candidates results were:
  - Charles Casper Stockham received a total of 85,213 votes, which accunts for 23% of the total votes.
  - Diana DeGette received a total of 272,892 votes, which accounts for 73.8% of the total votes.
  - Raymon Anthony Doane received a total of 11,606 votes, which accounts for 3.1% of the total votes.

- The winner of the election was:
  - Diana DeGette, who received a total of 272,892 votes, which is 73.8% of the total votes.

# Election Audit Summary #
## Script Usage ##
The script uses the data from the file "election_results.csv". The script can be reused for any other elections, provided the following is changed:
1. The Data File: The "file_to_load" variable stores the path and filename of the data file. This must be changed in order to reuse the script.
2. The Output File: The "file_to_save" variable stores the path and filename of the output/result file. This can be changed to store the output elsewhere. 

![PythonCode](/Screenshot/PythonCode.png)

