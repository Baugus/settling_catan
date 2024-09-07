# settling_catan
An exploration of odds and strategies in Settlers of Catan.

## hypothesis
###### statement 1
There are games in which choosing a strategy with a lower average expected points but larger standard deviations/tails (particularly in the positive/upside direction) may be a more effective strategy for being competative (win rate) than a strategy that "plays the odds" and has a better expected average payout but less frequent outliers.

###### statement 2
Settlers of Catan may be one of these games. I suspect (holding trading ability and distribution of resources constant) a strategy that widely distributes settlements (and cities) with an eye towards covering as many numbers as possible, may underpreform (in an environment where this is the most common strategy) relative to a strategy that concentrates (i.e. specializes) in particular numbers. The specialization strategy is likely to have higher point variance, but a "good game" under specialization (says my hypothesis) is likely to constitently outpreform a "good game" with a less specialized strategy. 

###### statement 3 
If Catan can be shown to exhibit this characteristic, then statement 1 is true and some game designs will exhibit this characteristic.

`The question is of the player's goal. Under this hypothesis, the distributed strategy is better for higher average points and higher points in any given game. Yet, the specialized strategy is likely to win by a higher margin on a "good game" and likely to have such good games at least as frequently as a distributed strategy. A followup question then is how many players do you need before it is more competative to play the specialized strategy rather than the distributed strategy. 

## plan of analysis
There are several layers to exploring this hypothesis through Catan. 

### part 1
How do the die results in a typical Catan game match up to the probability-predicted outcomes?
- Run a sample of games tracking the distribution of roles.
- Compare these distributions to the raw probabilities of each role.
- 
