# 2020 week 21

 - This week will be managed using GitHub. The emails will come out as normal.
 - This week will be a testing week, where stuff may break and I'll try to fix it.
 - The [r/Hermitcraft Beacon vol. 2 no. 21](https://www.reddit.com/r/HermitCraft/comments/gq5jye/the_rhermitcraft_beacon_20200525/) includes charity, birthdays, channel news, and more!
 - The [VisualEditor](https://www.mediawiki.org/wiki/VisualEditor) [is now compatable](https://phabricator.wikimedia.org/T177243) with the [Modern](https://www.mediawiki.org/wiki/Skin:Modern) skin.
 - **There is a new Discord trojan attack doing the rounds.** Read more [below](#stay-safe).

## Updates
 - [MediaWiki 1.35.0-wmf.34](https://www.mediawiki.org/wiki/MediaWiki_1.35/wmf.34) is being rolled out this week: [Phabricator task](https://phabricator.wikimedia.org/T253022) • [Roadmap](https://www.mediawiki.org/wiki/MediaWiki_1.35/Roadmap#34) • [Current status](https://versions.toolforge.org/) • [Git](https://phabricator.wikimedia.org/source/mediawiki/history/wmf%252F1.35.0-wmf.34) • [Notes](https://phabricator.wikimedia.org/maniphest/?project=PHID-PROJ-rxxuhlo4hr46ltm5xq2y&statuses=open()&group=none&order=newest#R)
    - Group 0 is scheduled for Tuesday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200526T1900  ) is 8pm to 10pm BST.
    - Group 1 is scheduled for Wednesday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200527T1900) is 8pm to 10pm BST.
    - Group 2 is scheduled for Thursday. Its [time slot](https://wikitech.wikimedia.org/wiki/Deployments#deploycal-item-20200528T1900 ) is 9pm to 11pm BST.
 - [Minecraft Dungeons](https://www.minecraft.net/en-us/about-dungeons/) has released.


## Past events
None! 

## Upcoming events
 - 🔄 The official Terraria weekly stream is every Friday at 9pm BST, on [Twitch](https://www.twitch.tv/terrariaofficial).
 - 🔄 The [Terraria Community Team](https://discord.gg/chpcEC2) meeting is every Saturday at 8pm BST.
 - 🔄 The Terraria Event forecast releses every Sunday, too late to cover here. You can find it in #activities-announcement at the [Official Terraria Discord Server](http://discord.gg/terraria).

## Stay safe
There is a new Discord trojan attack doing the rounds where it logs you out of Discord and you have to log back in... Once you log back in, it then has access to your account and user tokens. 
With this information it is disabling 2FA and locking the user out of their accounts, it then attempts to log into your linked accounts, such as YouTube, Twitch, Steam etc... if you use the same password for these accounts then it will likely be successful in doing that. 

This trojan is being passed around disguised as a link to a game. If you download this fake "game", during its install process it will modify the Discord JS files instructing Discord to load up a couple of extra scripts that convert your password into plain text that it can then harvest, which is why it logs you out and you are required to log back in.

To prevent this from happening, do not download any software at all that has been passed to you in discord, even from a friend (hacked accounts are passing the software around via friends) until Discord put a fix in place for this. 

If you have downloaded anything recently and you have been logged out of Discord, do not log back in, instead, uninstall Discord and re install it from the official Discord website. 
This does not affect the Web browser version.
