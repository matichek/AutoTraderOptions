[color=cyan]AutoTrader v0.9 January 30, 2023[/color]

## Moded - Matija - no comission trader, super fast (no big cooldowns)

(see Changelog for details)

This is a "fire-and-forget" version of the "old" MK3 Universe Trader by Mkess and BurnIt!.
It is different in many ways from both, the original and my X Return version. Since some players
found the initial version too much of a "cheat" I have added a setup with various options that can
be set before and after the AutoTrader has been activated. Please read the following description,
in particular the setup options new with version 0.3, before you decide to install it.


[color=#00BF00][b]Short Description:[/b][/color]

The AutoTrade will work on any of your NPC ships which is not docked and has no
command running (i.e. default wait). This is a new condition as some players have reported problems
if the ship had orders batched or was docked.

To start the script select the ship, right-click to bring up the context menu and select "Comm"
to talk to the captain. There is only a single option "Auto Trade Menu". Once you have clicked
that a sub-menu is displayed with the options:
[list]
[*] [u]Auto Trade[/u]: Select that and the captain will receive a star "*" behind his name to indicate
that the script is running. Please be patient as it may take a while (depending on setup you chose) 
before the autotrader is moving. [b]It is strongly recommended that you do not interfere with the
ship or captain in any way.[/b]
[*][u]AutoTrade Setup[/u]: This will open a setup menu with various options which can be selected at
any time via "Comm". Any setting you choose will be confirmed by the captain in the player logbook under
"upkeep". All setting will be displayed together with the regular profit message (see below). The 
following options are available:
[list]
[*][b]"Jump"[/b] (default true): Enables/disables jumping. If you disable it then the autotrader will
fly using travel mode and, if not a capital (L/XL) ship, also highways.
[*][b]"Prefer Player Stations[/b]" (default true): Enables/disables player station trading priority. If
enabled (default) then the autotrader/autominer will serve the player-owned stations with priority. When
disabled, all trade deals will be equally considered to determine the best deal.
[*][b]"Know all Trades[/b]" (default true): Enables/disables only trade offers and system known to player.
When enabled (default) the autotraders/autominers know the entire galaxy. If you decide to disable this
feature please be aware that this can cause the autotrader/miners to idle for a rather long time until you
have discovered systems with resources (mining) and station that offer trades.
[*][b]"Trade all Wares"[/b] (default true): Enables/disables trading in spaceweed/fuel and maja dust. This
option is (naturally) only available for autotraders as autominers have no illegal wares. Disable it if
you do not wish your autotraders to get into trouble with the police.
[/list]
[/list]
The setup parameter values will be shown in the autotrader's logbook report. You can change parameters at
any time. Changing a setting again will revert them and trigger a confirming logbook entry. Also be aware
that he will charge a fee(***) for his service and use your credits for trading. The higher his skills the
higher the fee but also the more effective he will trade. He will trade or mine for you without the need for
any further actions (hence fire and forget). When you select "Auto Trade" then the captain will become an:
[list]
[*][b]AutoMiner[/b] if the ship has gas or liquid storage then the captain becomes an Autominer,
[*][b]AutoTrader[/b] if the ship has container storage then the captain becomes an Autotrader.
[/list]


[color=#00BF00][b]Features:[/b][/color]
[list]
The Autotrader ...
[*]... will prioritize trades with player stations unless "Prefer Player Station" is set to "false" in which case
he will treat all trades as equal.
[*]... will transfer credits to you after a trade transaction has been completed. There will be no credit transfer
for trades with player-owned stations. 
[*]... knows the entire galaxy which he will search for a maximum profit trade(*) unless "Know all Trades" is set
to "false" in which case he will only trade with stations and harvest resources in systems known to the player.
[*]... is able to create an anomaly to reach his destination unless "Jump" is set to "false" in which case he will
fly using travel mode but will not use no highways. 
[*]... lifts the Fog of War (not relevant if "Know all Trades" is set to "false").
[*]... set all systems and faction he trades with as known to the player (not relevant if "Know all Trades" is set
to "false").
[*]... gains a small experience for every successful trade.
[*]... provides a (very) small reputation gain for the player with each faction after a successful trade.
[*]... will send regular profit information together with his name (his level in brackets), the ship's name (and id
code in brackets) and the optional setup parameter values to the upkeep section of your logbook,
[*]... charges commission fee as a percentage(***) of the profit for his services.
[*]... will trade more effectively but also charge a higher fee the higher his skills are.
[*]... will not trade/harvest with stations/in systems which are "enemy" to the player.
[/list]

[color=#00BF00][b]Installation[/b][/color]
If this is you first install then just extract the contents of the zipped file into your extensions
folder. If you have the previous version then remove that from your extensions folder before extracting
the zipped file. 

Please note, there have been reports that an extensions folder in the X4 main root directory
does not activate any mods. Due to a current info from the developers the original idea was to place
the extensions folder into the X4 document folder. So please try that if you have trouble with starting
mods from the main root folder. In any case you are [b]strongly advised to backup your saved games.[/b]


[color=#00BF00][b]Stop Autotrade[/b][/color]
If you comm an autotrader then the "Auto Trade Menu" has two options "Stop AutoTrade" and "Auto Trade Setup".
The setup allows to change the option parameters. For example, if "Known Trades" is set to "true" and you
select it again, it will change to "false". Any parameter changes should take effect instantly, i.e. no save
and/or restart is necessary.
The option "Stop AutoTrade" removes the script from the captain, also the star "*" behind his name but preserves
his profit history and his gained skills. It will also reset all setup options to the default values. 
Stopping the script has two purposes:

[u]1# Moving the Captain to new Ship:[/u] There are several methods.
A) Order the ship to dock at the station where the new ship is docked. Fire or move the captain of
the new ship to work as a service crew at the old ship, then move the captain of the old ship to the
new ship as service crew (or directly as captain if you have fired the one at the new ship) and promote
best crew member to captain. As the autotrader has gain experience during his trade runs and hence he
will be the best choice.
B) Dock at the old ship (of course, a corresponding docking area is required for the ship you fly) and
send the captain as service crew (or captain if the position is available) to your ship. Then fly and
dock at the new ship, fire or send the captain of the new ship as service crew to your ship and then
have the captain of the old ship work as new captain.

[u]2# Uninstall the AutoTrader Mod:[/u] Once you have stopped [b]ALL[/b] of your autotraders, save the
game, exit X4 and remove the mod from your extensions folder.


[color=#00BF00][b]Feedback[/b][/color]
Any feedback is most welcome and, of course, also details on any problems you may encounter [url=https://forum.egosoft.com/viewtopic.php?f=181&t=406859]please post here.[/url]

[b]Download[/b]
The mod is available for download at Nexus. Please note that there is no need to pay anything! You just need to register.

[url=https://www.nexusmods.com/x4foundations/mods/92/]DOWNLOAD[/url]


[color=cyan][b]Changelog Version 0.9 February 30, 2023:[/b][/color]

1#  Fixed a bug that allows trades with stations unknown to the player although "Know All Trades" was set to 0 (false). Big thanks to narta for spotting this bug.



[color=cyan][b]Changelog Version 0.8 February 20, 2023:[/b][/color]

1#  Changed the code to avoid negative profit which could occure under rare circumstances.
2#  Added new wares of Split and Boron.
3#  Optimized the AutoMiner code although there is a slim chance that the harvest  area is invalid. In this case an alert is created  in  the     player logbook. Please PM me with the logbook details.


[color=cyan][b]Changelog Version 0.7 February 18, 2019:[/b][/color]

1# Fixed a bug that mismatched buy and sell offers (thanks to ROMB for spotting this).
2# Added all language references in the context file to avoid crashes/freezes for Windows 7 players
who do not have the English Steam version (thanks to Kadatherion for pointing that out).


[color=cyan][b]Changelog Version 0.6 January 11, 2019:[/b][/color]

1# Added information on the last trade to the "upkeep" part of the player's logbook.
2# Improved the format for numerical values (amount and credits).


[color=cyan][b]Changelog Version 0.5 December 18, 2018:[/b][/color]

#1 Removed the ability to use highways as this has caused issues with ship not able to leave them.



[color=cyan][b]Changelog Version 0.4 December 17, 2018:[/b][/color]

#1 Added a condition for autominers preventing them to harvest in enemy systems.



[color=cyan][b]Changelog Version 0.3 December 15, 2018:[/b][/color]

1# Added new conditions for a hailed ship to offer the "Auto Trade Menu" option.
2# Added an "AutoTrade Setup" with various options (see above).
3# Added the ship's ID code to the regular report in the player's logbook under "Upkeep".
4# Fixed a bug that under certain conditions prevented the autominer to find resources.
5# The regular logbook report will now appear right after a trade has finished.
6# Removed all credit transactions when trading with player-owned stations.

 
Cheers Euclid
