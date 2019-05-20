# Junglee-Rummy-Data-Visualisation
Junglee Rummy Data Visualisation
Introduction:
Game - www.jungleerummy.com
In Rummy Game, we have a variant 101 Pool Games, that is available for users to play online.
This is just one of the 4 variants that is available. This 101 Pool Games have different ‘Entry Fee’ (the money
the user pays to play the game). Say 3 users A,B,C are playing the game with Entry Fees of INR 10. All
users will pay a certain Cut% to Junglee Games for the gaming experience.
This cut% varies according to Entry Fees. Let us say this cut% for Entry Fees of INR 10 is 15%.
All users will pay INR 1.5 each (INR 4.5 is the rake / revenue for the company) and the remaining INR 8.5
from each user goes into the final pot that is available as the winnings amount. Ultimately a single user wins.
If B wins, then (s)he wins INR 25.5 with a net winning of INR 15.5 (25.5 minus 10). Other users have a net
losses of INR 10 each.
Dataset Description:
1. Entry Fee: This is the Buy-in (money user pays) in rupees to enter the game
2. Seat: Max number of players that can sit on the table i.e. 2,6 for the data set
3. Composition: Actual number of players that actually joined the table
4. Date: It's a data set of 1st July 2018 to 30 Sep 2018 which gives daily data for each table
configuration
5. Configuration: Defined as the combination of Entry Fees – Seats – Composition
6. Cut %: %age amount deducted for each game from each user
7. '#Users': Distinct count of players (unique players) who played at least 1 game for table
configurationfor the date
8. User Cash Game Count: Total number of games played by users on table configuration for the date.
If user A,B,C play together a single game, then the value will be 3
9. Rake: Total amount generated in revenue from a table configuration for the date
10. Wager: Total amount paid by the users in terms of Entry Fees to play the game
