# world-cup-predictions-2022
Predictions for the  2022 World Cup in Qatar using Python.
This was a personal project I completed independently as I wanted to improve my fluency with Python and the associated libraries for data analysis and data science.
I am an avid soccer fan from Canada and have always been interested in sports betting. The project looks to guide betting decision making by predicting outrights.
I also wanted to improve my skills in statistical analysis and model development.
The model I developed calculates a team's probability of scoring with respect to their Attack Strength (AS) and the Defence Strength (DS) of their opponent.
The expected probability of scoring in the league is also factored in. 
These variables are calculated with respect to the averages for a team's expected goals (xG), expected goals against (xGA), and the average number of games played.
Using the associated probabilities for AS, DS, and the probability of scoring in the league, I use a poisson distribution to simulate different score lines. 
All matches are simulated and advancement to the Round of 16 from the Group Stage follows the standard points convention with the top two teams advancing.
All related csv and xlsx files can be found in the "data" folder, whereas non-output figures can be found in "images". 
The "Predictions Workbook" file shows all code and work conducted for analysis. 
The "Predictions Report Notebook" and "Predictions Report PDF" files analyze the findings from the workbook and comment on the results.
Best of luck to all the teams in the tournament, and go Canada!
