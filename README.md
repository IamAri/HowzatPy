# sportyStats
Note : ``sportyStats`` package aims to fetch, assess, interpret and display insightful statistics related to sport. Initially it will 
deal exclusively woth cricket related data. I will be employing the python programming language. I'd like to use this avenue of exploration to refine my python capabilities as well as add to my pythoning arsenal(pun not intended...I'm a red devil supporter)

## Problem 1
The South African cricket team have in my opinion unfairly attracted the tag of **chokers** . While they have indeed succumbed to pressure in the past (frustratingly so) I believe that they are not the only ones. I wish to use data avaialbe on theinternet to find the biggest chokers of them all.

This is how I plan on tackling the problem :

 + Define choking and create a choking metric
 + Collect as much data as possible from the web
 + Use base cases (such as 1999 world cup semi final, or almost any match vs Australia in a world cup :( ) to train the model
 + Run the refined metric through all ODI's since some relevant date, and out should pop the king of chokers.

Things to consider for the metric :
 + Team rankings at the time of the match
 + Team form going in to the match
 + The ground at which the game is played (certain conditions are synonymous with certain grounds and hence certain styles of play)
 + Use this information amognst other parameters to create a probability of winning metric, this should be a dynamic (running metric)
  i.e. it can be applied to a match at any point in that match.Once the probability exceeds a certain threshold then the team that is   expected to win is known as the favourite, if the favourite ends up losing the match then they would have choked.

Results from all data collected and all metrics calculated should be stored in some sort of database with provinence being a critically essential feature.
 
