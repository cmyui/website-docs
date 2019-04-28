---
title: "Aika Commands"
old_id: 3
---
These are the commands supported by Aika, our chat bot.  

### General commands
- `!roll` - Returns a random number from 0 to 100  
- `!roll num` - Returns a random number from 0 to num  
- `!help` - Display help message  
- `!pp [mode]` - Show your current pp. If `mode` is not present, Aika will tell you the amount of PP for your current game mode. If mode is present (it can be `std/taiko/ctb/mania`), Aika will tell you the amount of PP for that gamemode. **This command works only in PMs**
- `!update` - Update the beatmapset you've `/np`ed in our beatmap mirror. Use this if you've just downloaded a beatmap from osu!direct and it shows as outdated or if a beatmap can't be downloaded from osu!direct because it's too new.
- `!request <set/map> <beatmap_id> <game_mode>` - This allows users to nominate maps to be ranked, loved, or even unranked. Essentially, this will send a request to the members of the BN and QAT teams, and they will decide what happens with the map.
- `!togglenotifs` - This allows users to toggle the notifications saying 'You have switched to Relax', and vice versa.
- `!report <user>` - This allows users to report other users for things such as cheating, and breaking other rules.
- `!bloodcat` (or `!q` for premium members) - This can be used in multiplayer, or in spectator mode to grab a quick link to download the map (Premium members get a direct akatsuki mirror link, which is generally <i>much</i> faster than bloodcat).
- `!playtime` - This allows a user to check their total playtime on osu!Akatsuki.
- `!contest` - This allows a user to check the current contests hosted by Akatsuki.
- `!overwrite` <b>(Currently disabled)</b> - This allows a user to force their previous score to overwrite the score they previously had on the map.
- `!last` - This allows a user to see details about their last played beatmap. While regular users can only use this command in private messages with Aika, Premium members can use it in all public chat channels.

### Faq commands
- `!faq rules`
- `!faq swearing`
- `!faq spam`
- `!faq offend`
- `!faq discord`
- `!faq status`
- `!faq english`
- `!faq lines`
- `!faq merge`
- `!faq relax`
- `!faq team`
- `!faq cmyui`
- `!faq changelog`
- `!faq charlotte`
- `!faq support`

### Tillerino-like commands
Aika has some commands similar to Tillerino. Those commands work only if you send them to Aika through a PM. Remember that PP system has been implemented only on osu!standard and osu!mania. The bot doesn't support beatmaps recommendations at the moment, that functionality wil come later, hopefully.

- `/np` - Show PP for the current playing song  (only if is a osu! standard song)  
- `!last` - Show info (and gained PP, if it was an osu! standard score) about the last submitted score  
- `!with <mods>` - Show PP for the previous requested beatmap with requested mods. Supported mods are `RX, NF, EZ, HD, HR, DT, HT, NC, FL, SO.`. Don't use spaces for multiple mods (eg: `!with HDHR` or `!with HDDTRX`)

### Premium-only commands
- `!c <newUsername>` - This allows users to change their username, without having to visit the website.
- `!q` - Just like the bloodcat command, this can be used in multiplayer, or in spectator mode to grab a quick link to download the map. The only difference being, the map download is directly from Akatsuki and is generally <i>much</i> faster than the bloodcat download (which is also given as a fallback).

### QAT-only commands
- `!map <rank/love/unrank> <set/map> <beatmap_id> <game_mode>` - This allows the QAT member to change the ranked status of a beatmap.

### Admin commands
- `!system restart` - Restart the server. Everyone will be disconnected and reconnected automatically  
- `!system status` - Show server status  
- `!system reload` - Reload bancho settings (the one that are editable from RAP)  
- `!system maintenance on/off` - Turn on/off bancho maintenance mode  
- `!moderated on/off` - Turn on/off moderated mode for the current channel  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence a user  
- `!unsilence <target>` - Remove target's silence   
- `!kick <username>` - Kick an user from the server  
- `!ban <username>` - Ban and kick someone  
- `!unban <username>` - Unban someone  
- `!restrict <username>` - Restrict someone  
- `!unrestrict <username>` - Unrestrict someone  
- `!Aika reconnect` - Reconnect Aika if he's not on online users list anymore  
- `!alert <message>` - Send a notification to every user connected to bancho  
- `!alertuser  <username> <message>` - Send a notification to a specific user
And many more undocumented commands..