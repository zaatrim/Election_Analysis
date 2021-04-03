# **Election results Audit & Analaysis**

## *Project Overview*
 Our objective is to help Steve and Seth audit & certify the election results for Colorado state. Analysis based on actual ballots cast in elections.  Election certification will be defined based on analyzing the total votes, total Votes per Candidate, % of votes each candidate got out of total Votes, votes per county, and county votes % out of total votes. Need to identify the county with the highest votes & the winning candidate.
 we were asked to automate the analysis & audit process to be scalable to other states. for this purpose, I will write code in Python to ready the data and perform the elections audit in push button.       
   
                  
## *Analysis & Results*
### Analysis
Election Data was collected and consolidated into CSV text File, Named "election_results.csv". I will write code in Python to automate the data analysis based on the CSV file. 
   a. We will initiate the analysis process by importing the raw Txt file into Python. And define a file to save the data to i.  Once we read the file, we will store the Data in the "election_data" file name, Define the Variables, Lists, and Diceritonariers we need to run the analysis.
       
![code_Initiation_variables_definition](https://user-images.githubusercontent.com/80013773/113467625-0da52a80-93f9-11eb-8b44-853181b5d467.png)
            
   b. we will start loop through all rows in the file to :
      i. Calculate the total number of votes. 
      ii. identify the list of Candidates and List Counties, store their unique value into the defined lists "candidate_options" &"county_list" accordingly.
      iii. count number of votes per candidate and number of votes per count. Store these values in the defined Dectionieries "candidate_votes" & "county_votes"  accordingly. 

   ![1st_loop_votes_county_candidate](https://user-images.githubusercontent.com/80013773/113467691-873d1880-93f9-11eb-8f0e-07e7eb3eef04.png)
   
   C. then, we will initiate an additional Loop to calculate the county % of total Votes and the Largest county. And print the results to the terminal, and save the results to the "election_analysis.txt" file.

   ![2nd_Loop](https://user-images.githubusercontent.com/80013773/113467714-b2276c80-93f9-11eb-8b61-bcf7c0a98344.PNG)
   
   ![print_1st_loop_votes_county_candidate](https://user-images.githubusercontent.com/80013773/113467742-da16d000-93f9-11eb-9663-533ddbc426b4.png)

   D. Next will initiate an additional Loop to calculate the Candidate votes % out of total Votes and then identify the winning candidate. Then print the results to the terminal and save the results to the "election_analysis.txt" file.

   ![loop_print_winners](https://user-images.githubusercontent.com/80013773/113467757-fadf2580-93f9-11eb-9be9-9b9a335fa793.PNG)
          
### Results

Election results analysis is leading to the following results and conclusions:
   a) Total Votes in the state of Colorado was 369711.
   b) Dever is the largest county, with 82.8% of total Votes.
   c) The Candidate election winner is Diana DeGette with272,892 Votes. Won with 73.8% out of total votes   

   ![Terminal_print](https://user-images.githubusercontent.com/80013773/113467770-1813f400-93fa-11eb-8326-74823c143557.PNG)

    
## *Summary*
### Advantages
- Writing the code in Python is a significant advantage for automating the election results Audit and analysis. We could use this code in any state or federal election. All we need to have is a CSV file to contain the Elections results. Need to include the Ballot ID, County, and Candidate. Then in click, we can get the analysis and results of the elections. 
