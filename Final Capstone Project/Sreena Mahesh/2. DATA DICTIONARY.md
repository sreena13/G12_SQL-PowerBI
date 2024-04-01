# SREENA PROJECT REPORT

## Data Dictionary:

1. **Player**:
   - Description: The name of the football player who scored the goals.
   - Data Type: Categorical (String)
   - Example: "Cristiano Ronaldo", "Lionel Messi"
   - Data Type in Pgadmin: varchar(50)

2. **Competition**:
   - Description: The specific league or tournament in which the goal was scored.
   - Data Type: Categorical (String)
   - Example: "Liga Portugal", "Premier League", "LaLiga", "UEFA Champions League", "Taca de Portugal Placard", "FA Cup", "EFL Cup", "Copa del Rey"
   - Data Type in Pgadmin: varchar(50)

3. **Venue**:
   - Description: The location of the match, indicating whether it was played at home (H) or away (A).
   - Data Type: Categorical (String)
   - Example: "H" (Home), "A" (Away)
   - Data Type in Pgadmin: varchar(2)

4. **Club**:
   - Description: The football club for which the player was playing at the time of scoring the goal.
   - Data Type: Categorical (String)
   - Example: "Sporting CP", "Manchester United", "FC Barcelona"
   - Data Type in Pgadmin: varchar(50)

5. **Opponent**:
   - Description: The opposing team against which the goal was scored.
   - Data Type: Categorical (String)
   - Example: "Moreirense FC", "Portsmouth FC", "Tottenham Hotspur", "Real Zaragoza"
   - Data Type in Pgadmin: varchar(50)

6. **Kick**:
   - Description: The method used by the player to score the goal, such as a solo run, header, right-footed shot, left-footed shot, direct free kick, tap-in, or penalty.
   - Data Type: Categorical (String)
   - Example: "Solo run", "Header", "Right-footed shot", "Left-footed shot", "Direct free kick", "Tap-in", "Penalty"
   - Data Type in Pgadmin: varchar(50)


