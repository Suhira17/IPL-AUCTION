# IPL-AUCTION

## Abstract

This project conducts IPL data analysis via SQL queries, focusing on player statistics, auction strategies, and performance evaluation. It utilizes metrics such as strike rate and runs scored to aid in player selection for auctions, emphasizing the importance of all-rounders. Through data visualization, it facilitates informed decision-making during player auctions.


## Query Analysis and Solution Implementation

### Creating Table _MATCHES

- The creation of the "matches" table to store IPL match data, including match ID, city, date, teams, and umpire details.

### Creating Table balls
- The creation of the "balls" table is to capturing ball-by-ball data during IPL matches, such as inning, over, batsman, bowler, runs, and wickets.

### Bidding to Batters:
- The query for bidding to batters in IPL auctions focuses on identifying top-performing batsmen based on their performance metrics. By considering factors such as high strike rates and a significant number of balls faced, the query aims to evaluate the effectiveness and efficiency of batters in scoring runs. This analysis is crucial for teams to make informed decisions during player auctions, ensuring they acquire impactful batters who can contribute significantly to the team's success. By calculating strike rates, total runs, and other relevant statistics, the query provides valuable insights that can guide teams in selecting the right batters within their budget constraints.

### Bidding on Bowlers:
- The query for bidding on bowlers in IPL auctions is designed to help teams select bowlers with favorable economy rates. By focusing on identifying bowlers with efficient economy rates and a substantial number of balls bowled, the query aims to assess the bowling prowess and effectiveness of players. Evaluating bowlers based on their economy rates is essential for teams to build a well-balanced bowling attack that can restrict runs and take crucial wickets. This analysis provides teams with valuable insights into the performance of bowlers, enabling them to make strategic decisions during player auctions and strengthen their bowling lineup effectively.

### All-Rounder:
- The query for identifying all-rounders in IPL teams emphasizes the importance of versatile players who excel in both batting and bowling. By evaluating players based on their batting and bowling strike rates, the query aims to identify all-rounders who can make significant contributions in multiple aspects of the game. Selecting all-rounders who can perform well in both departments is crucial for team balance and overall performance. This analysis helps teams in identifying players who can add depth and versatility to the team composition, enhancing their chances of success in the IPL tournament.

### Wicket Keeper
- The query is to identify top wicket-keepers based on runouts and stumpings, highlighting their impact on match outcomes.

## Additional Questions

-It introduces further queries beyond player performance, exploring diverse aspects of IPL data analysis.

**1.Get the count of cities that have hosted an IPL match**

- A query to count the number of cities that have hosted IPL matches, providing insights into match distribution.

**2.Create table deliveries_v02 with additional column ball_result**

- The query creates a new table with a column categorizing ball results as boundary, dot, or other based on total runs.

**3.Write a query to fetch the total number of boundaries and dot balls**

- A query to calculate the total number of boundaries and dot balls from the "deliveries_v02" table.

**4.Write a query to fetch the total number of boundaries scored by each team**

- The query determines the total number of boundaries scored by each team, aiding in team performance analysis.

**5.Write a query to fetch the total number of dot balls bowled by each team**

- A query to calculate the total number of dot balls bowled by each team, reflecting bowling efficiency.

**6.Write a query to fetch the total number of dismissals**
- The query retrieves the total number of dismissals, excluding 'NA' dismissals, providing insights into player dismissals.

**7.Top 5 bowlers who conceded maximum extra runs**
- A query to identify the top 5 bowlers who conceded the most extra runs, highlighting areas for improvement.

**8.Create a table deliveries_v03 with additional columns**
- The query creates a new table by joining columns from existing tables, enhancing the dataset for further analysis.

**9.Write a query to fetch the total runs scored for each venue**
- A query to calculate the total runs scored at each venue, providing insights into venue performance.

**10.Write a query to fetch the year-wise total runs scored at Eden Gardens**
- The query determines the year-wise total runs scored at Eden Gardens, showcasing performance trends at the venue.


## Conclusion

Overall, this project delves into IPL data, revealing crucial player stats and the importance of versatile players. By leveraging SQL, it offers valuable insights for team management and auction strategies, enhancing our understanding of player performance and guiding strategic decisions effectively.
