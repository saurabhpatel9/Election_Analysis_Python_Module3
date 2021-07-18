# Election_Analysis

## Overview of Election Audit:

    The Election Commission had requested some additional piece of data to complete the election audit of an election which will be accompolished by the use of tools like  VSCode, Python and Git.
    The purpose of this analysis is to complete the election commission audit by using Python.

Requested information which would help in completion of the election audit include the following:
<ul>
<li>Retrieve and calculate the total number of votes cast.</li>
<li>Provide a complete list of candidates with received votes.</li>
<li>Calculate the total number of votes each candidate received.</li>
<li>Calculate the percentage of votes each candidate received.</li>
<li>Determine the winner of the election based on the highest vote count.</li>
</ul>

## Election Audit Results:
    The analytical based answers to the questions from the election commission can be found below:
<ul>
  <li><b>How many votes were cast in this congressional election?</b></li>
  Total Votes: 369,711</br></br>
<li><b>Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.</b></li>
  County Votes:</br>
	<b>Jefferson:</b> 10.5% (38,855)</br>
	<b>Denver:</b> 82.8% (306,055)</br>
	<b>Arapahoe:</b> 6.7% (24,801)</br></br>
<li><b>Which county had the largest number of votes?</b></li>
	<b>Denver</b> had won with the largest number of votes.</br></br>
<li><b>Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.</b></li>
	<b>Charles Casper Stockham:</b> 23.0% (85,213)</br>
	<b>Diana DeGette:</b> 73.8% (272,892)</br>
	<b>Raymon Anthony Doane:</b> 3.1% (11,606)</br></br>
<li><b>Which candidate won the election, what was their vote count, and what was their percentage of the total votes?</b></li>
	Winner: <b>Diana DeGette</b></br>
	Winning Vote Count: <b>272,892</b></br>
	Winning Percentage: <b>73.8%</b></br>
</ul>

### Code Snippet Screenshots (to demonstrate the logic used):
![candidate logic](https://user-images.githubusercontent.com/86158802/126084504-ebd43915-e937-4335-8d6e-0b277e740145.PNG)
![county logic](https://user-images.githubusercontent.com/86158802/126084506-876e236b-6290-4378-af60-584b2342c291.PNG)


## Concluded Analysis:
The analysis concludes that 3 Counties count up to 369,711 votes. The Denver county remarked with the largest percentage of votes with 82.8% of total votes. Diana DeGette won with 73.8% of the votes among all the candidates, amounting to 272,892 of the 369,711 total votes.

## Analysis Result:
![election_results](https://user-images.githubusercontent.com/86158802/126084518-6c19a037-85e6-4e92-abcf-242ccfe1b238.PNG)

## Election Audit Summary:
This Analysis can be performed for every election keeping in mind, the following two factors involved:
<ul>
  <li>The script can be modified by changing the csv file path to the targetted file for the required election analysis.</li>
  <li>The looping logic works the same way, keeping in mind the fields targetted for the analysis, the input and output file can be modified as per need.</li>
</ul>

