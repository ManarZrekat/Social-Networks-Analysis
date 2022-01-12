# Social-Networks-Analysis

# Dataset
The data represents the multi-layer temporal network which connects a population of more than 700 university students over a period of four weeks. The dataset was collected via smartphones as part of the Copenhagen Networks Study. The network includes the following:

- physical proximity between the students estimated via Bluetooth signal strength.
- phone calls between the students.
- text messages between the students.
- Facebook friendships between the students.
- The data also includes the gender of each student
  
 https://figshare.com/articles/dataset/The_Copenhagen_Networks_Study_interaction_data/7267433
 
 
 # Data preprocessing
 - the proximity dataset includes the rssi of each interaction, the analyzing work I'm doing is on social and personal interactions, I consider a social interaction to be between    0-4m in distance so I filtered the data to include only social interactions by selecting rows with rssi value bigger than -68.
 -deleted all rows that have the value -1 or -2 since they are irreverent for my research question 
 
 
 # Research Question
 The dynamics of communication for the two genders - How the two genders interact differently between each others, in 
Heterophily and Homophily interactions 

-It's important to remember that the male population in the study is 3.5 times bigger than the female population, which will result in biased conclusions and results.
-Keeping that in mind the results I will show can only be representative of the students in the study.






 

  

