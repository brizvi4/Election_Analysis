# County Election Analysis

## Overview of Project

Tom and Seth asked for my help to submit the election audit results to the election commission. They gave me a csv file containing ballot ID's, county names and candidade names. For this task, I was asked to use Python to extract meaningful information from the available data. I had to extract the following information:

- Find out the total votes casted in this election
- The number of votes casted in each county along with their percentages
- The largest county turnover
- Number of votes each candidate won and their percentages
- Winner of the election

## Election Results

By using my coding knowledge, I printed out the results on the terminal. After this, I printed out the results to a text file called election_analysis_txt. The following information was displayed in the text file:

- A total of 369,711 votes were casted in the election

![image](https://user-images.githubusercontent.com/95254809/150715809-b58bed40-a0d7-4191-a13d-2db1b16f7f9d.png)

- Denver county had the most votes (306,055). It comprised 82.8% of the total votes. Jefferson had 10.5% of the votes which amounts to a total of 38,855 votes. And Araphoe got a total of 24,901 votes which is the remaining 6.7%.

![image](https://user-images.githubusercontent.com/95254809/150716337-8c4f64d9-5ec3-4355-b915-d1ba23cdec81.png)

- Denver county had the most number of votes

![image](https://user-images.githubusercontent.com/95254809/150716402-d6ce4897-9976-42e7-a61d-e69dbcd6df2e.png)

- Diana DeGette had the most number of votes (272,892). It comprised 73.8% of the total county votes. In second place stood Charles Casper Stockham with 85,213 votes. This was 23% of the total tunrnout. Raymon Anthony Doane stood last in the election with 11,606 and these votes were 3.1% of the total votes. 

![image](https://user-images.githubusercontent.com/95254809/150717731-2cbca8a8-25ff-47f4-8282-e8e473ca5e55.png)

- Diana DeGette won the election with a huge margin. She had a total number of 272,892 votes. And these votes were 73.8% of the total votes. 

![image](https://user-images.githubusercontent.com/95254809/150718109-2a5e5455-75a5-458a-82a7-1d367ff77a14.png)

## Election Audit Summary

A good advantage of this Python code is that it can be used for other elections as well. For instance, all the variables we created for the candidates and counties can also be used for other candidates and counties. After using the csv.reader function and applying the file path, one can use the same for if statements for other elections. I am talking about the for and if statements shown in the below photos:

![image](https://user-images.githubusercontent.com/95254809/150721042-9322b2bf-40fa-4cb4-8b37-82b5d0f3b4a0.png)

![image](https://user-images.githubusercontent.com/95254809/150721068-63ea675f-6910-42bd-a98f-39b5cf0ed11b.png)

In order to print the results to a text file, one can first open the file using the write function and specifying the path where the want to the text file to be present in. And then the same print statements can be used to print out the counrt election results. Please see the below photos for reference. 

![image](https://user-images.githubusercontent.com/95254809/150721268-f9255f82-f593-47c0-9ab9-18797b252b59.png)

![image](https://user-images.githubusercontent.com/95254809/150721354-b60fbc90-cbf7-457e-9bce-2b7f9d646ae5.png)

In the second photo, I have marked the print statements with a red line becasue there is a lot of other code as well. 





