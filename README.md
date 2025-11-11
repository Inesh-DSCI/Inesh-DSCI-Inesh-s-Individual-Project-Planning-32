# Inesh-DSCI-Inesh-s-Individual-Project-Planning-32
Individual Project Planning Assignment for DSCI 100
Project creation date: November 11, 2025
Author: Inesh Saroya

Data Description: 
Two data sets have been provided. The first being,  "players" which includes data regarding players identities which includes their name, age, gender, experience in the game, subscription status, email id(hashed), and hours played. The second, "sessions" includes the players (identified via hashed email)  start and end time for their sessions, with dates included. Descriptive summary of both data sets: 

players:
-Number of Observations:196
-Number of Variables:7
-Name, Variable Type and Description of each Variable:
-experience,<chr>, variable describing the experience of each player from beginner to veteran
-subscribe,<lgl>, variable describing whether or not the player is subscribed to the service
-hashed email<chr>, variable indicating a hashed version of the players email
-played_hours,<dbl>, variable describing the ammount of hours of Minecraft played 
-name,<chr>, variable indicating the name of the player
-gender,<chr>, variable indicating the gender of the player
-Age,<dbl>, variable indicating the age of the player

Mean values for quantitative variables:
average_hours_played	average_age
       <dbl>	           <dbl>
        5.85	           21.14


sessions:
-Number of Observations:1535
-Number of Variables:5
-Name, Variable Type and Description of each Variable:
-hashed email<chr>, variable indicating a hashed version of the players email
-start_time,<chr>, variable indicating the date and time the player began playing Minecraft
-end_time,<chr>, variable indicating the date and time the player stopped playing Minecraft
-original_start_time,<dbl>, variable indicating the start time recorded in UNIX time 
-original_end_time,<dbl>, variable indicating the end time recorded in UNIX time 

issues: 
1. For the sessions.csv file, both start_time and end_time include the date and time in the same cell, proper analysis can not continue for this data set until it is tidied and each cell contains only one value.
2. N/A found in either dataset will have to be accounted for in code in order to properly manipulate data. 