# NWHL-Rotman-Datathon
This project was part of the Summer Datathon organized by Rotman School of Management and Stathletes.

## Dataset
The dataset was comprised of women’s hockey events data from the NWHL 2021 Season.  
The various event types include shots, plays, takeaways, puck recoveries, dump-ins, dump-outs, zone entries, faceoffs and penalties.

## Goal of Analysis:
* The goal of our analysis was to help identify the top 5 Powerplay players in the league 
[<a href = 'https://en.wikipedia.org/wiki/Power_play_(sporting_term)#:~:text=In%20ice%20hockey%2C%20a%20team,there%20is%20no%20power%20play)'>Wikipedia Definition: </a>'a team is said to be on a power play when at least one opposing player is serving a penalty, and the team has a numerical advantage on the ice'].
* The 5 selected players should form a balanced team, covering various skills required during a power play scenario.

## Approach:
1. Initially dataset was filtered to only include events wherein the team performing the event had more players than the opposite team. This helped focus on the players that are trusted during power plays and analyze their performance in this particular situation. The count for each event in the powerplay, per player, was then calculated [example: number of plays by a player, number of shots by a player].

2. Identified and calculated metrics which could help us compare and rank the players’ impact during power plays. The metrics considered for this analysis included - Goals Scored, Passes, Zone Entries, Shot and Pass Accuracy, Player Pass and Goal Contribution to the team, Player Zone Entry Contribution to the team and Assists.  

3. Utilized a weighted approach to identify players who ranked the highest based on the metrics determined. This involved adding weights to each metric, to reflect its importance in determining a good power play player. 

4. Ensured that the final 5 recommendations, formed a balanced team in terms of their skill sets (passing, shooting, dribbling). This provides more diversity in the team’s abilities to win the competition.

## Acknowledgement:
* I would like to thank my team members, who were a part of this project - Jasper Gao, Ashima Mahajan and Jiaxin Xu.
* I would also like to thank Stathletes who provided the dataset for this datathon.
