# Commands
prefix is currently fixed to pp.  
All of these can also be found with the command pp.help <command>  
## Command name (aliases)
description  
`usage`  
![command name](https://cdn.discordapp.com/attachments/644268290474115075/782993756802252860/unknown.png)
## osuset
Sets your osu! username so you don't have to type it out every command (when \<name> is blank, defaults to your osu! username)  
`pp.osuset <name>`  
![osuset](https://cdn.discordapp.com/attachments/437091189792047125/782988806050807808/unknown.png)  
## osu
Gets your osu! stats  
`pp.osu <name>`  
![osu](https://cdn.discordapp.com/attachments/644268290474115075/782989222004129822/unknown.png)  
## top (osutop, tp)
Gets the top 5 pp plays of a user  
`pp.top <name>`  
![top](https://cdn.discordapp.com/attachments/644268290474115075/782990219230183434/unknown.png)  
## strains  
Gets a graph of the difficulty spikes in the given map  
`pp.strains <link>`  
![strains](https://cdn.discordapp.com/attachments/644268290474115075/782990812358246491/unknown.png)  
## osutrack (admin only)  
Tracks when a user gets a new top play within their top 50, and posts it in the channel (remove with stoposutrack)  
`pp.osutrack <name>`  
![osutrack](https://cdn.discordapp.com/attachments/644268290474115075/782991443823558656/unknown.png)
## pp
Gets the pp that a map is worth given accuracy, combo, miss count, and mods (values of these default to SS)  
`pp.pp <link> +<mods> <acc>% <miss count>m <combo>x`   
![pp](https://cdn.discordapp.com/attachments/644268290474115075/782989866115792926/unknown.png)
## recent (rs, ors)
Gets user's most recent play (in the last 24 hours)  
`pp.rs <name>`  
![recent](https://cdn.discordapp.com/attachments/644268290474115075/782994039552606228/unknown.png)  
## scores (sc, score)
Gets user's best score on the map  
`pp.sc <link> <name>`  
![scores](https://cdn.discordapp.com/attachments/644268290474115075/782994492503359518/unknown.png)
## beatmap (bm)
Gets a beatmap's info  
`pp.bm <link>`  
![beatmap](https://cdn.discordapp.com/attachments/644268290474115075/782994799883452446/unknown.png)
## leaderboard (lb)
Ranks the top players in the server by pp (top 9, only people who have done osuset)(now takes 30 seconds less than owobot!)  
`pp.lb`  
![leaderboard](https://cdn.discordapp.com/attachments/644268290474115075/782995208236695622/unknown.png)
## multiresults (mr)
Gets the results of a multi lobby, or the result of a specific round (if \<round> is not given, will show the results overall)  
`pp.mr <link or id> <round number>`  
![multiresults](https://cdn.discordapp.com/attachments/782996958871683153/782997940569636937/unknown.png)  
## beatmaplink (admin only)
When this is enabled in a channel, bot will get information for every map link that is posted
`beatmaplink <enable or disable>`
![beatmaplink](https://cdn.discordapp.com/attachments/782996958871683153/782997169262821386/unknown.png)
