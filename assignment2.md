## Assignment 2

Think about an area you're interested in, or one you may do your final project on, and come up with a dataset you wish existed. Then submit the following:

Draws sometimes can affect how far a tennis player can go into tournaments. I am curious which former U.S. Open women's champion had the best and worst draw since 2000. That data can give readers a sense of how important draws can be to a player's performance and final result in a Grand Slam.  

Here are the features I'll be collecting, and an explanation of why:
* Qualified players
* Qualified year(s)
* Their seed condition (Their own seed may affect what opponents they met. For example, when Sloane Stephens competed and won in 2017 with her protected ranking, her opponents were sure to be of higher rankings.) 
* Opponents' seed conditions - R128, 64, 32, 16, QF, SF, F (the most direct way to see the level of their opponents)
* Sum of opponents' seed points (easy to compare with other qualified players)
* Number of opponents with whom she has a disadvantaged head-to-head record (a supplement to just seed conditions)
* Total tiebreakers played (This means she played with people that were very competitive.)
* Total sets played (This would demonstrate the difficulty of winning the championship.)

I will collect the data by turning to [the official site of the U.S. Open](https://www.usopen.org) as well as [WTA](http://www.wtatennis.com/) for offical game records and H2H. The list of former U.S. Open champions are easy to find on [Wikipedia](https://en.wikipedia.org/wiki/List_of_US_Open_women%27s_singles_champions).

Player | Year | Seed | R128 | R64 | R32 | R16| QF | SF | F | Sum | Disadvantaged H2H | Tiebreakers | Sets
 ----- | ---- | ---- | ---- | --- | --- | -- | -- | -- | --| ----| ------------------| ------------| ----
Sloane Stephens | 2017 | - | - | 11 | - | 30 | 16 | 9 | 15 | 81 | 0 | 1 | 18
Angelique Kerber | 2016 | 2 | - | - | - | 14 | 7 | - | 10 | 33 | 1 | 1 | 15
Flavia Pennetta | 2015 | 26 | - | - | - | 22| 5 | 2 | - | 55 | 0 | 1 | 17
Serena Williams | 2014 | 1 | - | - | - | - | 11 | 17 | 10 | 38 | 0 | 0 | 14
Serena Williams | 2013 | 1 | - | - | - | 15 | 18 | 5 | 2 | 40 | 0 | 1 | 15
