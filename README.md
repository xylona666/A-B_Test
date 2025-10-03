# A-B_Test


As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention and game rounds.


# tools 

 pandas DataFrames 
 pandas plot


 # data

 The data is from 90,189 players that installed the game while the AB-test was running.

 AB Testing Process¶
Understanding business problem & data
Detect and resolve problems in the data (Missing Value, Outliers, Unexpected Value)
Look summary stats and plots
Apply hypothesis testing and check assumptions
Check Normality & Homogeneity
Apply tests (Shapiro, Levene Test, T-Test, Welch Test, Mann Whitney U Test)
Evaluate the results
Make inferences
Recommend business decision to your customer/director/ceo etc.



The variables are:

userid - a unique number that identifies each player.
version - whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).
sum_gamerounds - the number of game rounds played by the player during the first week after installation
retention_1 - did the player come back and play 1 day after installing?
retention_7 - did the player come back and play 7 days after installing?
When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.
