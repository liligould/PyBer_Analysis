# PyBer_Analysis

## Purpose
With the help of graphic applications through Pandas  and matplotlib, visualizations of rideshare data via city type were created in order to help improve access to PyBer’s ride-sharing services by determining whether average fare and total rides per city type are correlated. By creating multiple DataFrames ride sharing data such as total rides, total drivers, total fares, average fare per rider and driver and total fare by city type will also help determine affordable prices for underserved neighborhoods.

## Findings

The first steps that were taken was to determine total rides, total drivers, total fares, average fare per rider and driver and total fare per city type (Rural, Suburban, Urban). Based on the information gathered urban locations have the advantage for accessibility, and affordability due to having higher populations in general. A higher population means more riders, more drivers, and lower costs due to high demand. Urban areas have 13 times more riders than rural locations and 30 times more drivers. Although drivers do make 3 times more per fare when driving in rural areas, overall total fares is 9 times higher in urban locations. While drivers make a lot for individual rides in rural locations riders have to pay more than urban riders.
  
![Total Vote=0](https://user-images.githubusercontent.com/80358062/114328957-c9561080-9b03-11eb-99a2-0a8b584fef95.png)



### - **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
  * To collect the total vote count and to collect individual information for each candidate a breakdown of number of votes per county and percentage of votes per county were necessary for further analysis. To do this a dictionary first had to be initialized.
  
  ![Create dictionary](https://user-images.githubusercontent.com/80358062/114329072-19cd6e00-9b04-11eb-9e3c-8712f094e41b.png)
  
  * This dictionary allowed us to more easily track votes in each county 
  
  ![Tracking votes ](https://user-images.githubusercontent.com/80358062/114329211-5f8a3680-9b04-11eb-81c6-0a5798e411e8.png)
  
  * By creating a for loop we were able to find the percentage of votes in each county as well as total votes per county
  
  ![for loop](https://user-images.githubusercontent.com/80358062/114329596-61082e80-9b05-11eb-8d2d-6b26f0bfb278.png)
  
  * The previous lines of code lead to the following results
  
  ![county votes](https://user-images.githubusercontent.com/80358062/114330608-b34a4f00-9b07-11eb-8c90-d315ac710fff.png)

### - **Which county had the largest number of votes?**
  * After creating the county results a conditional statement was then created to determine the largest county turnout based on total number of votes and total voter percentage which was Denver with 82.8% of total votes or 306,055 total votes out of 369,711.
  
  ![conditional](https://user-images.githubusercontent.com/80358062/114329712-b47a7c80-9b05-11eb-857c-62c0dfa8ba97.png)
  
  * The previous conditional statement lead to the follwoing results 
  
  ![largest county](https://user-images.githubusercontent.com/80358062/114330698-e096fd00-9b07-11eb-9157-098602c8c6f0.png)

### - **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**
  * With the data we were [given](https://github.com/liligould/Election_Analysis/blob/main/Resources/election_results.csv)
we were able to extract the candidate names from each row (row[2]) by first setting winning candidate to an empty set, and winning count and percentage starting at zero.
 
 ![winning variables](https://user-images.githubusercontent.com/80358062/114330017-61ed9000-9b06-11eb-94cf-fde34f54846f.png) 
 
 * Using the information we gathered from total votes we are able to determine the number of votes each candidate received as well as the percent of votes they held. 
 
 ![code for candidate votes](https://user-images.githubusercontent.com/80358062/114330298-05d73b80-9b07-11eb-9815-5cc3c9614b01.png)
 
 * The previous lines of code gave us the following results

![Output](https://user-images.githubusercontent.com/80358062/114330373-328b5300-9b07-11eb-8bd1-7e0203291a0e.png)

### - **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
  * Based on the winning variables and another conditional statement we were able to determine that Diana DeGette won the election with a winning vote count of 272,892 votes and winning percentage of 73.8%.
  
  ![winning candidate info](https://user-images.githubusercontent.com/80358062/114330860-4c796580-9b08-11eb-8718-b5bd5a183834.png)
  
  * The previous code let to the following output
  
  ![winning candidate output](https://user-images.githubusercontent.com/80358062/114330915-6a46ca80-9b08-11eb-85a0-3938d575cd00.png)

## Summary
This analysis was originally created to gather information on a specific election but could very easily be used in future elections as well. With a simple update of variables, candidate names, and county's that voted this code could be applied. 


