# Commands List

- **X** specifies a number
- Arguments between **( )** are optional

### Manager

| Command | Arguments | Description |
|:-------:|:---------:|:-----------:|
| !afklimit | X | sets the maximum AFK time. |
| !botname | (botname) | change the default bot name. |
| !bouncer+, !bouncerplus | — | toggle bouncer+. |
| !clearchat | — | clears the chat. |
| !clearlocalstorage | — | clears basicBot data stored on the browser. |
| !cycle | — | toggle DJ cycle. |
| !cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled. |
| !language | (language) | specify the language you would like the bot to use. |
| !locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled. |
| !logout | — | logs out account bot is hosted on. |
| !maxlength | X | specify the maximum length a song can be when timeguard is enabled. |
| !refresh | — | refreshes the browser of whoever runs the bot. |
| !skippos | X | set the position to which skip and lockskip moves the dj. |
| !usercmdcd | X | set the cooldown on commands by grey users. |
| !usercommands | — | toggle user commands. |
| !voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |

### Bouncer+ 

(User with special Bouncer Permissions)

| Command | Arguments | Description |
|:-------:|:---------:|:-----------:|
| !add | @user | add user to the waitlist. |
| !afkremoval | — | toggles the AFK check. |
| !autoskip | — | skips songs automatically when they're done (use when the circles-bug happens). |
| !deletechat | @user | delete all the chats by a certain user. |
| !lock | — | lock the waitlist. |
| !lockdown | — | lock down the room: only staff can chat. |
| !meh | — | makes the bot meh the current song. |
| !move | @user (X) | moves user to position X on the waitlist, default is position 1. |
| !remove | @user | remove user from the waitlist. |
| !roulette | — | start a roulette. |
| !d | (message) | bot deletes message |
| !songstats | — | toggle song statistics. |
| !swap | @user1 @user2 | swaps the position of two users in the waitlist. |
| !unlock | — | unlock the waitlist. |
| !welcome | — | toggle the welcome message on user join. |
| !woot | — | makes the bot woot the current song. |

### Bouncer

(Note: Users with the Bouncer+ rank cannot use these commands)

| Command | Arguments | Description |
|:-------:|:---------:|:-----------:|
| !stay |	bot says "enjoy your stay!" |
| !active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default. |
| !afkreset | @user | resets the AFK time of user. |
| !afktime | @user | shows how long user has been AFK. |
| !autodisable | — | toggle the autodisable. |
| !ban | @user | bans user for 1 day. |
| !blacklist / !bl | blacklistname | add the song to the specified blacklist. |
| !blinfo | — | get information required to blacklist a song. |
| !commanddeletion / !cmddeletion / !cmddel | — | toggles if bot commands gets deleted. |
| !cycleguard | — | toggles the cycleguard. |
| !dclookup / !dc | (@user) | do dclookup on a user. |
| !english | @user | ask user to speak english (asked in the language they set plug to). |
| !eta | (@user) | shows when user will reach the booth. |
| !filter | — | toggles the chat filter. |
| !forceskip / !fs | — | forceskips the current song. |
| !historyskip | — | toggles the history skip. |
| !jointime | @user | shows how long the user has been in the room. |
| !kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds). |
| !kill | — | shut down the bot. |
| !lockguard | — | toggle the lockguard. |
| !lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with `!skippos)`. |
| !motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message. |
| !mute | @user/(X) | mute user, for X minutes if X is specified, otherwise for an undefined period. |
| !reload | — | reload the bot. |
| !restricteta | — | toggles the restriction on eta: grey users can use it once an hour. |
| !sessionstats | — | display stats for the current session. |
| !skip / !smartskip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with `!skippos`). |
| !status | — | display the bot's status and some settings. |
| !timeguard | — | toggle the timeguard. |
| !togglebl | — | toggle the blacklist. |
| !togglemotd | — | toggle the motd. |
| !togglevoteskip | — | toggle the voteskip. |
| !unban | @user | unban user. |
| !unmute | @user/all | unmute user. |
| !uptime | — | displays how long the bot has been running. |
| !voteratio | @user | display the vote statistic for a user. |
| !whois | @user | returns plug related information about user. |

### Resident DJ

| Command | Arguments | Description |
|:-------:|:---------:|:-----------:|
| !link | — | bot gives a link to the current song. |

### User

| Command | Arguments | Description |
|:-------:|:---------:|:-----------:|
| !rcs | link to rcs script/plugin to use for autowooting. |
| !plug3 | — | links to plug3 plugin |
| !plugit | — | links to plug-it plugin |
| !event | — | there are events coming up pretty soon! |
| !guide | — | how to use/navigate plug.dj!. |
| !8ball / !ask | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
| !autowoot | — | links to plugcubed, the advised script/plugin to use for autowooting. |
| !ba | — | explains the brand ambassador rank. |
| !commands | — | gives a link to the commands. |
| !cookie | (@user) | give a cookie to user. |
| !discord | 	— 	links an invite to the room's Discord |
| !dclookup / !dc | — | use dclookup on yourself. |
| !emoji | — | returns a link the emoji list. |
| !eta | — | shows how long before you will reach the booth. |
| !fb | — | links to the room's facebook page (if set in the settings). |
| !ghostbuster | @user | checks if user is ghosting. |
| !gif / !giphy | (message) | returns gif (from giphy) related to the tag provided. returns a random gif if no tags are provided. |
| !help | — | mentions the room's staff, use wisely! |
| !join | — | join the roulette if it's running. |
| !leave | — | leave the roulette if you joined. |
| !link | — | gives a link to the current song playing. |
| !op | — | links to the overplayed (op) list (if set in the settings). |
| !ping | — | returns pong! |
| !rules | — | links to the rules. |
| !source | — | returns a link to the source information on Github. |
| !theme | — | links to the room's theme. |
| !thor | — | users get moved to position 1 in the waitlist if they're worthy of Thor's hammer. |
| !website | — | links to the room's website. |
| !youtube | — | links to the room's youtube page. |

### If there are missing commands on this list, please let me know!

##### If you are reporting a messing command please use the following format:

**Command:** Name of command.

**Rank:** User/Bouncer etc.

**Optional:** What the command does.

Thank you! - Fluted
