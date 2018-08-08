# Assignment 5: Interview a dataset

The database I interviewed: [Results of the former U.S. Open female defending champions.]()(This would be expanded to include both men's and women's later.)

### Q1: How far did the former U.S. Open defending champions go, in general? Is it getting easier to defend?
A: Of the 49 U.S. Open defending champions, 28.57 percent defended their titles, 17.95 percent became runner-ups, 15.38 percent advanced to the semifinals, 12.82 percent to the quarterfinals and 25.64 percent did not make to the finals.


### Q2: Which defending champion had the best draw and fully took advantage of it?
A: Steffi Graf in 1996. The then world No.1 entered the U.S. Open in 1996 as the first seeded player and defended her title. But she did not play a seeded player until the semifinal, which was very uncommon. She defeated #16 Martina Hingis and #2 Monica Seles, against whom she held winning records, in the semifinal and final, respectively, without a tiebreaker or three setter.

### Q3: What does the hardest journey to defend a champion look like in the U.S. Open?
A: In 2001, the fourth seeded Venus Williams denfended her U.S. Open title by overcoming five seeded players - #30 Lisa Raymond, #18 Sandrine Testud, #5 Kim Clijsters, #2 Jennifer Capriati and #10 Serena Williams. Three of them were world No.1 at some point of their careers. Williams is the defending champion that played the most seeded opponents in the tournament history. However, she finished all matches in straight sets and did not even play a tiebreaker. 

## How I created the database and processed the data
1. Collect all data from Wikipedia pages and [WTAtennis.com](http://www.wtatennis.com/headtohead).
2. Weighting the seeds by assigning 32 points to the first seeded player and 1 points to the 32nd seeded player. Non-seeded players do not have points. Use the sum to calculate the difficulty rate and present it in a 100 scale. -- [Raw Data]
3. Delete rows with no data (i.e. the player did not attend during that year) and rank by difficulty rate. -- [Ranked by DR]
4. Rank by results and calculate the porportion of different results in all years and years when the defending champions returned. (=Cell/49 or =Cell/39) -- [Ranked by Results]
5. Took the "champion" data points and rank by year. -- [Defending over Years]


2. Additionally, write down all steps used to clean and analyze the data, including any Excel formulas. 
3. Lastly, write a sample headline and nut graf based on the most interesting of the three questions.

I combined Q1 and Q2 to develop a headline and because I do not have Sloane Stephens' draw this year yet, the story idea is more history-based than what I expect for the final project.
## Historical Statistics Show It's Harder to Denfend the U.S. Open Title on the Women's Side
Sloane Stephens may be unhappy about that, but data shows that dedending a U.S. Open champion has become increasingly difficult for WTA players. 
Since its launch in 1968, the U.S. Open has only witnessed its trophy reclaimed by the same player for 14 times, 10 of which were before the 2000s. The difficulty of defending, moreover, is generally higher in recent years. Despite Martina Navratilova won what seemed to be the hardest-won champion in 1987, let's not ignore that Venus Williams, in 2001, became the only defending champion that played five seeded opponents in the tournament history. 
