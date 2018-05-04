# footballpred
Various ideas, datasets and analyses around football predictions

## To do
- Datasets in R : https://cran.r-project.org/web/packages/engsoccerdata/README.html
- http://www.toutlemondesenfoot.fr/blog/2018/04/26/optax-3e-partie-le-coaching-a-lere-de-lintelligence-artificielle/
- Example of cool dataviz of scorer : http://johnburnmurdoch.github.io/projects/goal-lines/all-comps/. Apparently it's based on data from http://www.worldfootball.net, investigate how to get them (contact the guy ?).

## Links
https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017/kernels

## Basic score prediction
The 1st ideal dataset would be :
- score
- team playing
- minute of every goal (because the evolution of the score is a big constraint, I guess one is more likely to score when chasing than when leading)


## Go to the player level
- get the team playing for each game would allow to get the impact of each player. Then, based on the team supposed to play, one would be able to get a probability of score based on the association on specific players
