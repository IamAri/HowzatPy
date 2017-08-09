# HowzatPy
Note : ``HowzatPy`` package aims to fetch, assess, interpret and display insightful statistics related to the wonderful sport of cricket. Initially it will deal exclusively with T20I cricket related data. I will be employing the python programming language. 

## Below is a list of questions that I aim to address (In no particular order)

1) The South African cricket team have in my opinion unfairly attracted the tag of **chokers** . While they have indeed succumbed to pressure in the past (frustratingly so) I believe that they are not the only ones. I wish to use data available on the internet to find the biggest chokers of them all.

This is how I plan on tackling the problem :

 + Define "choking" and create a choking metric.
 + Collect as much data as possible from the web, mostly scraping.
 + Use base cases (such as 1999 world cup semi final, or almost any match vs Australia in a world cup :to train the model.
 + Run the refined metric through all ODI's since some relevant date, and out should pop the king of chokers, my intuition tells me Pakistan will come out tops.

Things to consider for the metric :
 + Team rankings at the time of the match
 + Team form going in to the match
 + The ground at which the game is played (certain conditions are synonymous with certain grounds and hence certain styles of play)
 + Use this information amognst other parameters to create a probability of winning metric, this should be a dynamic (running metric)
  i.e. it can be applied to a match at any point in that match.Once the probability exceeds a certain threshold then the team that is   expected to win is known as the favourite, if the favourite ends up losing the match then they would have choked.

Results from all data collected and all metrics calculated should be stored in some sort of database with provinence being a critically essential feature.

NB : To address this question using the above approach would require ball-by-ball data or at least over-by-over data. This seems significantly more difficult to get hold of than just scorecard data.
 
