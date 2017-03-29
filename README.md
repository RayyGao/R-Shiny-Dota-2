# R-Shiny-Dota-2
This project is about R Shiny. I used Shiny to build up data visualization for 50000 ranked ladder matches and also design an algorithm to predict the final pick when 4 of the team are chosen.

A much clearer version of the Shiny App:
http://216.230.228.88:3838/bootcamp008_project/Project1-ExploreVis/XuGao/#sthash.YL5EpYyX.dpuf

# The Function in Shiny

This project is briefly about data visualization. It can show the top winning ratio heroes, top popular heroes, top rich heroes and top popular items the people choose. 

It can also help people to compare with different hero winning ratio if they have multiple choices and have to choose one at the moment. 

Besides, it provides the information about the specific hero by selecting hero name in "Pick One Hero to See". This information is about average GPM(Gold Per Minute), average Kill/Death/Assists Per Minute, and winning ratio and their rankings.

Last but not the least, it can predict the last pick for a team. The assumption in this algorithm is the total gold and experience for a team in a minute are fixed. By setting a buffer 90% to 110%, after we get 4 picks of a team, it can approximately predict what range the gold and experience for last pick are in. By arranging these heroes by the winning ratio, it can predict the last pick hero.

# Download by Git Clone

# This is the first Data Visualization Project from Xu Gao.
Author: Xu Gao, a graduate student learning Financial Engineering at Tandon School of Engineering in New York University.
He is highly interested in quantitative finance and data science. BTW, he loves games and enjoys analysing them by using data.

