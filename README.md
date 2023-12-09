# Strategic Insights from the Frontline: Dissecting Elite CSGO Play from 2019-2020

<a href='https://youtu.be/1awI3X7L748'>Presentation Video</a>

## 1. Context Description
**Counter-Strike: Global Offensive (CSGO)** is a round-based tactical shooter where two teams, the Counter-Terrorists (CT) and Terrorists (T), compete against each other. The game's dynamics are shaped by strategy, teamwork, in-game equipment, and environmental factors.

## 2. The Data Set(s)
**Description:**
- **Title:** CSGO Round Snapshots from 2019 and 2020 High-Level Tournaments
- **Data Points:** 122,411 snapshots
- **Source:** High-level tournament play demos from 2019 and 2020

**Attributes:** 
- **(a) General Attributes:** 
  - time_left: Time remaining in the current round.
  - ct_score: Current score of the Counter-Terrorist team.
  - t_score: Current score of the Terrorist team.
  - map: The map on which the round is being played.
  - bomb_planted: Boolean indicating if the bomb has been planted by the Terrorists.
  - round_winner: Designates the winner of the round (either CT or T).
  
- **(b) Team Vitality:** 
  - ct_health & t_health: Total health points of the CT and T teams respectively.
  - ct_armor & t_armor: Total armor points of the CT and T teams respectively.
  - ct_players_alive & t_players_alive: Number of players still alive in the round for both teams.
  
- **(c) Team Economy:** 
  - ct_money & t_money: Total in-game money for CT and T teams respectively.
  - ct_helmets & t_helmets: Number of helmets possessed by each team.
  - ct_defuse_kits: Number of defuse kits held by the CT team.
  
- **(d) Weapons:** 
  - Separate attributes for each weapon type indicating the number of players on each team with that weapon.
  
- **(e) Grenades:** 
  - Separate attributes for each grenade type indicating the number of players on each team with that grenade.

**Pre-processing:** Warmup rounds and restarts were filtered out. Snapshots were recorded every 20 seconds until the round's conclusion. The data was flattened for better readability and ease of algorithmic processing.

**Independence:** Snapshots are independent and identically distributed (i.i.d) and should be treated as separate data points, not sequential elements of a match.

## 3. Target Audience and Their Assumption(s)
**Target Audience:**
- **CSGO Players and Enthusiasts:** Those seeking insights into high-level play strategies and patterns.
- **eSports Analysts and Commentators:** Professionals looking for data-driven narratives and insights for broadcasts and articles.
- **Tournament Organizers:** Those interested in understanding game dynamics to better organize and promote their events.
- **Game Developers:** Those looking to gather insights for game balancing and future updates.

**Assumptions:**
- The dataset represents the typical dynamics of high-level tournament play.
- The data has been cleaned and is free from anomalies, inaccuracies, or biases.
- Snapshots can provide a comprehensive understanding of round dynamics.

## 4. Potential Surprising Effects and Justification of the Unexpectedness
- **Shift in Dominant Strategies:** The dataset might show that certain strategies have become less prevalent.
- **Inconsistencies in Equipment Usage:** Some weapons or equipment might be used more or less than expected.
- **Spatial Dynamics:** Certain maps or zones might become strategic hotspots.
- **Time Analysis:** Significant actions might cluster around specific times, indicating critical moments.

## 5. Interesting Stories that Could be Analyzed Out
- **Evolution of Strategies:** How strategies have evolved over the two years.
- **Key Players & Their Impact:** Identifying standout players or teams.
- **Map Dynamics:** Analysis of strategies on different maps.
- **Equipment Meta:** Insights into favored weapons and equipment in high-level plays.
- **Timing and Tactics:** Analysis of critical moments in rounds.
- **Team Dynamics:** Insights into team strategies and outcomes.
- **Fairness in CS:GO:** Analyzing if there are biases in maps, equipment, or game settings.

By delving deep into these narratives and patterns, the analysis would offer valuable insights into the dynamics of high-level CSGO play, potentially influencing future strategies, game developments, and broadcasts.
