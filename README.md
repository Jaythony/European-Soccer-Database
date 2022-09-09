# European-Soccer-Database

### Dataset Description 

**About the data:** The European Soccer Database sourced from Kaggle contains data on *over 25,000* matches played across **11** European countries/leagues between **2008 - 2016**. It also contains data on *over 10,000* players and about *300* teams.

> **Tables:** The database contains 7 tables:
1. **The *Country* Table:** This contains 2 columns, a unique **id** and associated country **name**.
2. **The *League* Table:** 3 columns - League **id**, **country_id** (this corresponds to **id** in the *Country* table) and League **name**.
3. **The *Match* Table:** contains 115 columns on match details such as date, country_id, league_id, stage, season, stage, team IDs, goals, betting odds, etc. The league_id can be used to link this table with the league table, the same goes for the country id, team IDs and player IDs that relate to the Country, Team and, Player tables respectively.
4. **The *Player* Table:** 7 columns containing player details such as id, birthday, height, weight, etc.
5. **The *Team* Table:** 5 columns - team IDs, team_long_name, team_short_name.
6. **The *Team_Attributes* Table:** contains 42 columns, can be linked to the _Team_ table using team IDs.
7. **The *Player_Attributes*  Table:** contains 25 columns, can be linked to the _Player_ table using player IDs.

### Question(s) for Analysis
1. What teams in the England Premier League improved the most over the time period?
2. What team attributes lead to the most victories?
3. Is there really such a thing as home advantage (do teams do better when they play at home)?
4. Who is the highest rated player?
5. What attributes affect player's rating?
