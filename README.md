# CSCI4831- Sabermetrics Final Project
## Seasonal Batter Rating (SBR)

**Project Deliverables**

• (10 pts of final grade) Explanation of you idea - Due Monday, April 15 by 3pm. This is
a one-page description of what you plan to do, including a rough idea of your statistic,
what data you plan to use, and how you’ll present the statistic. I’ll read these quickly, I
promise, and give you feedback. You should also include whether you are working alone
or as a pair.

• (80 pts of final grade) Code and data - Due Friday, April 26 by 3pm. By this data, you
should have an almost complete code base and data set. You will need to submit a web
link that I can access to check your progress.

• (10 pts of final grade) Final product - Due Wednesday, May 1 by 3pm. This is the final
writeup, working code, data, and video for your project. This is the last day of class.
If anyone wants to present their work to the class, I will give you up to 5pts of extra
credit.

## Project Sections

**Explanation of Statistic**

It can be argued that hitting a baseball is one of the hardest things to do in sports.
Swinging the bat at the ball is more than just a simple reflex; rather, it involves player’s smart
decision making, and great control of their body movement to produce enough momentum so as
to create a powerful whip action to launch the ball into the stands for a home-run. You might
know some of the legendary batters who have mastered the art of batting such as Barry Bonds,
Willie Mays, or Babe Ruth, but how efficient were these batters compared to the rest of their
career years they’ve had? In fact, you could go even further and ask how efficient were these
players at batting per season compared their career as a whole? This is exactly the statistic that I
aim to describe for my final project, which I’ve labeled as Seasonal Batter Rating (SBR), the
ratio involving numerous batting statistics in one season for a player over their career averages
for those specific statistics. In addition, I will be looking at batter's SBR over late innings. I believe that this ratio measures a player’s efficiency in a given year compared to their career as a whole, so it can be noted if a player is performing better than they
usually do or worse. In addition, I believe SBR can be used to find trends for batters’
contribution to their team and see if a pattern exists to predict players future success. The
formula is as follows:

SBR = (BA_season + wOBA_season + wRC+_season) / (BA_career + wOBA_career + wRC+_career)

These are the three baseball statistics I’ve specifically focused on when determining this ratio
because:

(1) Batting Average looks at a common, but important statistic for batters, which is a batter’s
average performance as a ratio of their hits to the number of times they were at bat. BA is
involved in the calculation because it is so prominent in baseball as one of the most famous
statistics in sports, but note that it NOT useful as a statistic of its own.

(2) woBA represents a players weighted on-base average, which is involved in my statistic
because it determines how valuable each offensive outcome for a given state truly is. The
downside is that it doesn’t account for how baseball’s play style evolves over the years,
which is why wRC+ is also involved in the calculation.

(3) wRC+ is weighted runs created plus, a statistic that involves park factor and league
adjustments in its calculation. This statistic is involved in SBR’s calculation because it solves
the issue that wOBA doesn’t highlight, which is the park and league adjustments.

**Evaluation of Statistic**

**Presentation**


**Repository Contents**

All material pertaining to my final project for CSCI 4831 - Sabermetrics is stored in this git repository. Within the checkpoints folder is all the necessary files required for each checkpoints submission including a pdf file of the initial proposal of the Seasonal Batter Rating statistic, the code base & data, and a video presentation file demonstratiing how the statistic works. 
