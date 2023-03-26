
# Always make sure you are not Kyrian covenant! (change to Necrolord, otherwise it will cause rotation to hang)
# Rogue: All classes
- Interrupts with offGCD spells like kidney, cheap, gouge might not always work if you have interrupt % > 40
- NN is not fully supported, so for now rogue rotation mgiht now work to fullest on this unlocker
- Refresh time 0.1 is more than enough
- Testing on dummies works ok only on English clients (still it is best to test on real enemies)
- If you want to have good logs in raid play with good players, kill times affect logs a lot and most of the times it is hard to get good logs if you play with bad players (there are exceptions though)
- Interrupt system: (there are DR checks for them from awful, but they dont seem to always detect DR, probably thats why they are called awful)
	- Kick - it will only use those spells for kickable spells
	- Stun - it will only use those spells for unkickable but stunnable spells
	- Both - it will only use those spells for kickable and stunnable spells
- Wheatstone won't be used in single target, if you want it to be used in ST pop it manually. Won't add it to ST because it is too situational for M+ when you want to save it and when you want to pop it ST.
## Useful macros:
	- /ap cooldown
	- /awful cast Feint
	- /awful cast [@cursor] Distract
	- /cast [@focus]Tricks of the Trade
	- /use 13
	- /use 14
# Rogue: Outlaw
 - Adrenaline Rush is set up to Time To Die check, so if it isnt popped for some enemies (because they die to fast) and you want to use it anyway, pop it manually
 - KS/BR will only be used if we have energy deficit otherwise they are not worth using
 - Mode: toggle is for specifying if you want to use Single Target only rotation or AUTO for automatic adapting for # of targets situation
 ## Useful macros:
	 - /awful cast [@cursor] Grappling Hook
	 - /ap KS_BR
![Logs](https://i.imgur.com/Jct1mlo.png)\

# Rogue: Subtlety
- Subtlety requires a bit more brain than outlaw so if you want to have good performance in M+ you need to manage your cds well, macros below help saving/popping them
- Cooldown toggle is onlt affecting Shadow Blades
- Burst toggle is affecting all major and minor CDs (I disable burst when tank is gathering packs in M+)
- Prio Rota toggle - when enabled rotation will funnel targeted enemy

 ## Useful macros:
	 - /ap cooldown
	 - /ap apburst
	 - /ap priority
	 
|![NO23](https://i.imgur.com/twuUuJf.png) ![AA24](https://cdn.discordapp.com/attachments/1037409177104027690/1086711568059871335/image.png)|
|:--:| 
| *NO 23 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ AA 24* |
|![HoV22](https://cdn.discordapp.com/attachments/1037409177104027690/1086712108240076930/image.png)|
| *HoV 22* |
|![RLP23](https://cdn.discordapp.com/attachments/1037409177104027690/1087744504225869905/image.png)|
| *RLP 23* |
| ![HoV23](https://i.imgur.com/ONUroBQ.png) | 
| *HoV 23* |
| ![CoS23](https://i.imgur.com/TuwcLHZ.png) | 
| *CoS 23* |
| ![AA23](https://i.imgur.com/11zdIfk.png) | 
| *AA 23* |
| ![AV21](https://i.imgur.com/q5OsQAY.png) | 
| *AV 21* |

# Rogue: Assassination
- Only good for terros fight, but even there I dont use it :)
## Useful macros:
	 - /ap cooldown
I don't play that spec except for testing purposes so I don't have logs for it (if anyone has some share them with me I will add them if author agrees)
# Rogue basic knowlege

I won't be providing any answers regarding what talents to use what are BiS items, enchantments or consumables. Rotations will work with every single build and if for some talent they will not work just make a ticket and post what is wrong. Before asking questions mentioned in previous sentence check those rogue knowlege sources:
- [Ravenhold discord]
- [Wowhead guides]
- [Fuu's simulation sheet]
- [Rogue WCL]
- [Subtlety Yoda's FAQ]

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)
[Ravenhold discord]: https://discord.gg/ravenholdt
[Wowhead guides]: https://www.wowhead.com/class=4/rogue
[Fuu's simulation sheet]: https://docs.google.com/spreadsheets/d/e/2PACX-1vRq3Nn1ZvFwaXf1wQTr1RalpWbJTIhQp5xGwEyDTVWyuBWLP9_2rqqsxJSPQJLJAkIiKHy49pVfqEWu/pubhtml#
[Rogue WCL]: https://www.warcraftlogs.com/zone/rankings/31#class=Rogue
[Subtlety Yoda's FAQ]: https://docs.google.com/document/d/1vHuvRLNZfDLY62ryh5RlrwCoT9OwLrTgDVzrNkQmaVM/edit
