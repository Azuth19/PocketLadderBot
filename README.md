# PocketLadderBot
Simple discord bot for pokémon pocket that uses the ELO system of pokémon showdown

Queue Commands:

!queue join - Adds you to the matchmaking queue. If there are 2+ players, automatically creates a match room
!queue leave - Removes you from the matchmaking queue

Match Commands (used in match rooms):

!win - Claims victory in a match
!confirm - Used by the losing player to confirm the match result
!help - Notifies administrators about issues

Ranking Commands:

!leaderboard - Shows the all-time top 10 players and their ratings
!leaderboard monthly - Shows the monthly top 10 players and their ratings
!ranking - Shows your own all-time and monthly rankings
!ranking clear - (Admin only) Clears all rankings
!ranking clear @player - (Admin only) Clears a specific player's rankings

The bot also handles Elo ratings automatically, starting everyone at 1000 rating and adjusting it based on match results.
