# What do you want to play? 
This is question my friends and I often ask. Therefore, I've taken an hour to figure out Steam's API and create `steamjoin`. 

# What does steamjoin do? 
Steamjoin inputs your and your friends Steam IDs and outputs the games that you all have in common. 

# How does steamjoin work? 
Steam join is just a little script. I think I'll take some time this weekend to put this into a little stand-alone application and host it. However, it's just a bit of code to make it easy to figure out which steam games my friends and I have in common.

# How do you use steamjoin? 
Clone the repository. Install the requirments.txt (it's realy only numpy and steam). Edit the `steam_ids` list. Run. It should print out the list of overlapping games. 

`include_played_free_games = True` will include the free games that each steam ID has ACTUALLY played. If you haven't played it, it won't show up (otherwise the list would be many, many thousands of games long). 

# Do you plan to add features to this? 
Perhaps. I'd like to add some visualization components. For instance, I'd like to visualize who plays a particular game more and whether or not we can compare win/loss ratios. Lot's of places to go, but that might be too much work and not enough play. 

Thanks for stopping by and enjoy!

Best, 

Eli

