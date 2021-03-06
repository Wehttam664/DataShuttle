#DataShuttle#
***

### What is DataShuttle? ###
***
DataShuttle was a project developed by Mayateck Networks in attempt to create one central account system, saving the player time and effort when it comes to creating several hundred accounts. At first, DataShuttle was a small project with only a few services locked in such as some of the Mayateck small servers, the web server, and a few other smaller systems. DataShuttle is slowly growing, and, after some testing on the Mayateck server (mc.mayateck.net:25565) it can be released to the public to allows players to keep one rank across many servers (and in some situations, funds!). This project, the port of DataShuttle to Java for use as a Bukkit plugin, will allow many Minecraft servers to have ease of not having to deal with setting ranks themselves AND have extreme simplicity in rank set-up.

### Commands ###
***
**PLAYERS:** For the normal player, DataShuttle has almost no commands, as all work is done when the player connects to the server. Some servers may allow players to use some of the information commands, listed below.

**ADMINS:** Admins have access to the /datashuttle (Alias /ds) command to fetch DataShuttle info, run some tasks, and edit configuration in-game.
 - /ds info &lt;player&gt; || Returns public account information on sender or optional player.
 - /ds resync &lt;player|all&gt; || Resyncs account data for the command sender. Optional player or 'all' param to specify target.
 - /ds desync || Removes the sender's Minecraft name from his/her account.
 - /ds config [type] [val] || Edits DataShuttle configuration for your server in-game.

### Accounts ###
***
Accounts are managed by [Mayateck Networks](http://www.mayateck.net/home.ws "Mayateck Website") and can be contolled by the account holder under 'Account Management.' Please note: DataShuttle is **NOT** intended for cracked servers, and can be **EXTREMELY** damaging to any offline server using DataShuttle, as there is no authentication for offline play. (Meaning any person could connection to a server as the name of a Director and instantly have all permissions.) This can also be detrimental to players account along the lines of theft on Minecraft names. To counteract this, DataShuttle will disable itself on offline servers.

Accounts will automatically attempt to sync when the player joins. DataShuttle searches the Mayateck database for an account with the Minecraft name entered on the website. 

Something wrong? Take a look at this before posting an issue:
 - Minecraft name taken by an account you don't own? Simple! When you join the server, DataShuttle will run a first time "setup" when you join the for the first time with your name synced. When the plugin asks if the account belongs to you, simply respond 'no' and DataShuttle will remove you from that account. If it does not prompt on first-time join, using '/ds desync' will also remove your name from any account it's synced to. (If you don't have permission, use the Mayateck server: mc.mayateck.net:25565) Note: If your Minecraft name is already registered, it cannot be regisered to annother account without desyncing!

### Extra Information ###
***
List of administrative account holders:
 - Director: Wehttam664 (Matt, Director of Research and Development)
 - Director: ShinyNarwhal (Ken, Director of Logistics)
 - Administrator: Ssej64 (Jess)

