---
title: "FAQ"
old_id: 2
---
- **My antivirus is blocking the switcher**
- That's because our switcher edits the hosts file. Turn off your antivirus and run the switcher again.

-----------------------

- **I get "Connection failed" when I try to connect to Akatsuki**  
- Click the "Inspect" button on the server switcher and make sure that all the labels are green (like [this](http://oi66.tinypic.com/2v9q90p.jpg)). If you still can't solve this problem, come on our [Discord](https://discord.gg/5cBtMPW) and we'll help you.

-----------------------

- **I get "Bancho authentication failed" (wrong password) when I try to log in, but my password is correct!**

This means that your osu! is connected to either Akatsuki or Bancho (or whatever other server you were playing on), but is failing on login. This usually either means:.

A. You did not restart your osu! after switching servers
Fix: Simply restart your game and try again.

B. Your switcher did not properly write to the hosts file, and you are still connected to a different server (most likely Bancho).
Fix: Refer to the first FAQ in the [Discord](https://discord.gg/5cBtMPW) to locate your hosts file, and ensure the ppy.sh related lines are there. If not, add them and try again. If you cannot solve your problem, move to #help in our [Discord](https://discord.gg/5cBtMPW) channel.

-----------------------

- **I can't download maps from osu!direct.**
- Some maps can't be downloaded from our beatmap mirror due to technical reasons.

-----------------------

- **I can't download maps when I'm in multiplayer, but I can download them from the main menu**
- Disable **Automatically start osu!direct downloads** from the options and try again.

-----------------------

- **How do I play on the normal osu! again?**
- Close osu!, run the switcher and click the **Switch to osu!** button

-----------------------

- **My switcher is off but when I open osu.ppy.sh in my browser I get an error or I get redirected to Akatsuki's website!**
- Make sure the switcher is off, then empty your browser cache and restart your browser. [Google it](http://lmgtfy.com/?q=How+to+empty+browser+cache) if you don't know how to do it.

-----------------------

- **I get strange errors on osu!'s website after playing on Akatsuki (beatmaps not found etc)**
- Delete `s` and `t` cookies relative to osu.ppy.sh using a [cookie editor](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg). If you don't know how to remove specific cookies, just delete all cookies from your browser settings.

-----------------------

- **Can I keep playing while the server is restarting because it's updating?**
- Yes, your scores will be sent as soon as the server gets back online (usually less than a minute). Just make sure to not close the client.

-----------------------

- **Is there a patcher for Akatsuki?**
- No, you can change server by editing the hosts file with our switcher. [Instructions here](/doc/1).

-----------------------

- **Why are osu!direct and other in-game supporter perks free?**
- We think that osu! direct is very cool and it's a shame people have to pay to have it, that's why we're offering it for free on Akatsuki. If you like what we do, please consider a [donation](/donate).

-----------------------

- **My problem is not listed here**
- Join our [discord](https://discord.gg/5cBtMPW) and ask your question in the #help channel of the server.