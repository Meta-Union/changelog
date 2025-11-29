# Changelog
All notable changes to the Meta-Union Minecraft Network will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/). You can find a prettier version of these changelogs [here](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/Meta-Union/changelog/main&homepage=changelog.md&sidebar=true#/) unless you are already on Docsify-This, then you're already "here" :joy:

## 2025-11-30
### Changed
- Axe Master now grants the same amount of extra damage as Sword Master so Axes stay stronger than Swords like it is in vanilla (survival)

## 2025-11-29
### Changed
- Custom Enchanted Books now cost experience points instead of levels. Previously if you were level 100 and bought Poseidon for 25 levels, you would end up with 75 levels, now however you'll end up with 98 levels as going from level 0 to 25 only requires 910 experience points but going from level 99 to level 100 requires 733. This was done so it's not punishing to have more levels than a custom enchantment required (survival)
### Added
- Exiled town rank was added. Once given to a resident, they won't be able to interact with anything inside the town so it's meant as a punishment for that resident. Just make sure said resident can't remove the rank on their own or it'll be useless (survival)

## 2025-11-28
### Added
- Replanter enchantment was added which lets you replant any fully grown crop you break but it decreases the durability of your hoe. The durability decrease is less with higher levels of Replanter (survival)
### Removed
- Mana was removed entirely (survival)
- Replenish, the mana ability of the farming skill, was disabled as it was replaced by Replanter (survival)

## 2025-11-24
### Changed
- The quest "Unlock Alphabet Skulls" now requires you to kill 4 Blazes and 4 Cave Spiders instead of 4 Bats and 16 Chicken as some people don't like killing non-hostile mobs (survival)
### Added
- The rank "bank-manager" was added to Towny. This rank can withdraw and deposit from and to the town bank (survival)
- The rank "plot-manager-only-unowned" has been added which is pretty much the same as the "plot-manager" only that this one can't manage plots which are owned by players (survival)

## 2025-11-23
### Fixed
- Timber now also works on crimson and warped stems (survival)

## 2025-11-20
### Added
- Added Glowstone Dust, Mud, Tuff and Blackstone to the server shop, each costing a different amount of Elite Coins (survival)

## 2025-11-19
### Changed
- You can now buy 2 Ancient Debris instead of 2 Netherite Scraps for 1 Elite Coin in the server shop. This was done as people also want Ancient Debris to build with and because 1 Ancient Debris can be smelted into 1 Netherite Scrap (survival)
### Added
- Added 32 Nether Quartz Ore for 4 Elite Coins to the server shop. These prices will be expensive as I want to encourage people to either go out of their way for the resources **or** trade with other players (survival)
- Added 64 Ice for 1 Elite Coin to the server shop (survival)

## 2025-11-17
### Changed
- Mob damage used to give 3 XP/damage for the Defense skill. This has been increased to 5.5 XP/damage so people have less incentive to get punched by an alt account or another player and it's also viable to just use a mob (survival)
- The roof bedrock in the nether can now be mined as it turns into deepslate when you interact with it. This was done as access to the nether roof is something Mojang has said is a feature and thus I don't see the point in it being only accessible through what feels like glitches (survival)

## 2025-11-10
### Changed
- Elytra gliding will now be disabled when you're combat tagged so you can no longer fly away to avoid most risk from PvP (survival)
- What used to be called Statistics in the '/menu' is now called Leaderboards and has been reworked a little bit. Some parts didn't work, some parts were a little inconsistent in my eyes (survival)

## 2025-11-09
### Removed
- Speed Mine mana ability was disabled as announced previously since it's been replaced by the higher levels of Efficiency enchantments (survival)
### Changed
- `/baltop` no longer shows non-players like towns so the leaderboard is no longer filled with towns. `/balrank` also takes this into account (survival)
### Fixed
- Voice Chat mod was no longer working as I accidentally removed a port forwarding that was required. I simply forgot it was necessary for voice chat mod to function and thus removed it. Sorry for any inconvenience! (all servers)

## 2025-11-06
### Changed
- PSMs are now a little easier to obtain as they were never adjusted after some skills were removed quite a long time ago (survival)

## 2025-11-04
### Changed
- 1 Elite Coin is now worth 30,000 vanilla experience instead of 10,000 vanilla experience (survival)
### Fixed
- The cooldown for picking your mode was not displayed in chat anymore. That's now fixed (survival)

## 2025-11-02
### Changed
- Regular players now earn 450 MetaCoins every 6 minutes and builders earn 900 MetaCoins every 6 minutes. This was mainly done as builds can be done within 2 hours and we wanted to allow people to more easily claim more plots (creative)
- Voting now rewards 900 MetaCoins and a lucky vote even gets you 7,000 MetaCoins. Once again to more easily get new plots so you can build even bigger things (creative)
- Mobs now get their movement and flying speed set to 0 so they can't fly or walk around. Without this, happy ghasts could be controlled onto other plots where they would get stuck (creative)

## 2025-11-01
### Fixed
- Fixed custom enchantments not working for Bedrock Edition at all. This is because Bedrock Edition controls enchantments client-side and not server-side which means Geyser has no way to send custom enchantments to Bedrock Edition clients, however there is a nifty little plugin which works around this (survival)

## 2025-10-31
### Changed
- Looting 4 now costs 40 levels and can be combined in an anvil up to Looting 12 (survival)
- Timber 1 is now the only Timber level you can obtain and then you have to combine it in an anvil for higher levels (survival) 

## 2025-10-27
### Changed
- The online map now shows the town board when clicking on a town (survival)
- Custom Efficiency can now be combined up to level 12 which insta-breaks pretty much everything at deepslate level. Level 9 breaks deepslate but not deepslate ores for example (survival)

## 2025-10-24
### Changed
- The Action Bar to show HP and Mana will no longer show up as we're getting closer to removing all Mana Abilities. The only ones left are the one from Mining and the one from Farming (survival)

## 2025-10-23
### Added
- You can now buy 10,000 Vanilla Experience for 1 Elite Coin in the Server Shop (survival)
### Changed
- Elites are now bigger the higher their level (survival)

## 2025-10-22
### Removed
- The Mana Ability Treecapitator needed to be disabled. I thought I could wait until people migrated to the Timber enchantment but as it turns out you can combine Timber with Treecapitator and destroy **huge masses** of trees which was not intended to happen. As I don't have any other alternatives however and I want to move away from Mana Abilities, this change had to be done, sorry people :yellow_heart: (survival)
### Fixed
- You might know about the Anvil Discount thing which the Wisdom skill stat is meant to apply. While that was applied to low repair costs, it was not applied to high repair costs. The problem is that Minecraft by default does not allow you to repair items beyond a certain point, hence the "Too Expensive" but for some reason this lead to a situation where the skill plugin **meant** to lower the required vanilla levels **but** it couldn't be shown as Minecraft thought it was too expensive. Now I have installed a plugin however which fixes those issues and technically lets you repair past level 40. You will see "Too Expensive" past level 40 unless you have a mod which shows you the level anyway but if it shows an output, you simply need enough levels to repair it. In short: If you had items which you couldn't repair previously, now's a good time to try again :smile: (survival)

## 2025-10-20
### Changed
- As mentioned in the removed logs, Exacation Luck was increased by a factor of 4 to make up for the removed mana ability called Terraform (survival)
- You now earn 2x as much excavation skill experience and it only requires 50% of excavation skill experience to level up a skill. If you break any excavation block and level up a lot suddenly, this is why. The reason for this was because the Terraform mana skill was removed which was a big excavation skill experience boost overall (survival)
### Removed
- The mana ability called Terraform from the excavation skill was removed as it caused too many issues as described in <https://github.com/Meta-Union/Meta-Union/issues/145>. As compensation you now get more Excavation Luck, meaning more blocks which count for the excavation skill (survival)

## 2025-10-19
### Changed
- You previously did not lose hunger while you were in your own town which was not intended to be the case. Now you do lose hunger while you're in your own town (survival)
- Right clicking with a custom enchanted book no longer shows the description text (survival)
- Custom enchanted books look different now, being called Custom Enchanted Book with an aqua name to be closer to vanilla's style and also only mentioning the enchantment name, just like vanilla has it (survival)
### Removed
- The following Mana Abilities were disabled: Sharp Hook, Charged Shot, Absorption and Lightning Blade. Instead of Charged Shot the ability Bow Master was improved to give the same boost in damage. The others we think were not used enough or had a big enough impact to warrant a replacement (survival)

## 2025-10-18
### Changed
- The message shown when toggling PvP has been changed to reflect the fact that you're forced to be visible on the map and locator bar when your PvP status is on (survival)

## 2025-10-17
### Changed
- Capped the damage of maces at 10 as the mace can otherwise be too powerful and even one hit geared up and skilled up people (survival)

## 2025-10-15
### Changed
- You can no longer hide on the map or from the locator bar if you turn off PvP (survival)

## 2025-10-13
### Added
- 60 second spawn protection after you have been killed is now applied as it was deemed unfair that people can spawn camp you (survival)

## 2025-10-12
### Changed
- Server updated to run 1.21.10 (survival)
- Elite Coins are more common again (survival)

## 2025-10-10
### Changed
- Due to how Bedrock Edition handles the Haste effect differently from Java Edition, we changed the Speed Mine ability to give haste level 15 instead of 10 as level 10 was causing issues. Quite certainly related to <https://github.com/GeyserMC/Geyser/issues/3987> (survival)

## 2025-10-05
### Fixed
- Fixed a bug which prevented some auctions in the auction house to work (survival)
- Fixed a bug which made spectator mode not work properly (survival)
### Changed
- Ender Pearls will no longer load chunks even though this is vanilla behavior. The main reason is because it conflicts with the idea of Meta-Union which is that "real work" should be rewarded and not being AFK and also rules which prevent gaining resources while AFK which would be circumvented by ender pearls loading chunks (survival)

## 2025-10-03
### Changed
- PvP plugin has been updated to a new major version bringing a better timer which tells you how long you're in combat still and a better internal way of handling placeholders (this is only relevant for Folas xD). If you notice anything weird about it, let me know (survival)
- Having PvP turned on now grants an extra 70 MetaCoins every 6 minutes (survival)

## 2025-09-24
### Changed
- Some commands now work different internally but nothing should have changed function wise (lobby, creative, survival)
### Fixed
- Lots of errors were thrown in the console if you were in a non-plot world as the name above your player shows how many plots you own **but** it can't be resolved if you are in a non-plot world, so now the "Plots Owned" above your head refers to only the new plot world and ignores the ones you have in the old plot world, hopefully not too inconvenient for people <3 (creative)

## 2025-09-23
### Added
- Elite Gear for Speed, Regeneration, Wisdom, Health and Luck were added. I won't be adding Toughness as in my opinion it's no different than extra Health, same goes for Crit Damage and Crit Chance only for Strength, so that also won't become a thing (survival)
### Changed
- The Recovery Compass is back as a few people have told me that they're missing it as it made it super easy to quickly join the server of your liking. Now the "Build by ..." NPCs tell you to use the other NPCs instead if you want to play (lobby)

## 2025-09-20
### Changed
- Elites now give Elite Coins to everyone who was involved in a fight although there is a limit which is the elite's level + 3, so a level 5 Elite could give a reward to a maximum of 8 people (survival)
- Elites can no longer be killed as easily with a mace (survival)
- Non-hostile mobs were removed from Elites and a replacement with hostile mobs was added so Elites can be fought within towns more easily (survival)
- You can now interact with the "Lobby built by ..." NPCs to open the menu (lobby)
### Removed
- You no longer receive a recovery compass when you enter the server. You will have to either interact with the NPCs, use the portals or type '/menu' AKA '/?' to join a server. This was mainly done because if both the compass and the NPCs open the menu, it would glitch out and if I write in chat to interact with the NPCs to play, that'll confuse new players as the "Build by ..." NPC is also an NPC but it won't do anything so this is the best solution in my opinion (lobby)

## 2025-09-16
### Added
- Elite Gear was added to the Server Shop which currently allows you to buy armor which gives extra strength stat points. More gear might follow in the future but only on demand, so it won't be added without anyone asking (survival)
### Changed
- The spawn has gotten a little overhaul to hopefully make things even easier for new players, especially the ones that do not want to read an entire tutorial before playing (survival)

## 2025-09-14
### Added
- New quest which allows you to earn Elite Cookies Lv. 1 if you're near other players. The system is still subject to change as it's obviously quite new still. This is meant to encourage more activities together other than just fishing (survival)
### Removed
- Group Fishing was removed as it's now replaced by the Group Elite system that you unlock through the quest (survival)

## 2025-09-11
### Changed
- Looting 5 is now instead Looting 6 (survival)
- Phantoms spawned from the spawn eggs from the server shop no longer drop phantom membranes as otherwise with the high levels of Looting you can gain an unlimited amount of phantom membranes (survival)
### Added
- Looting 9 can be bought from the server shop (survival)

## 2025-09-09
### Changed
- '/local' now works and has a radiud of 128 blocks (creative)

## 2025-09-08
### Changed
- Treecapitator and Speed Mine abilities have been doubled in how long they last. Some people that shall remain unnamed complained that it didn't feel like it lasted very long :P (survival)
### Added
- Looting 5 was added as a custom enchantment for 100 levels. More might be coming soon (survival)

## 2025-09-07
### Added
- Added the first challenge which is to smelt all ores. This could mark the start of a cool new system which will be challenges but it might as well just be scrapped eventually as it doesn't catch on or whatever other reason... only time will tell :> (survival)

## 2025-09-06
### Changed
- Creating a outpost for a town now costs 24,000 while it previously costed 50,000 (survival)
- Merging towns now costs 12,000 while it previously costed 25,000 (survival)

## 2025-09-05
### Changed
- Totem of Undying and Phantom Spawn Eggs can now be obtained from the Server Shop instead of quests. It seems much more logical that way (survival)
- The Dragon Egg quest was moved to the More Content category as it was the only quest left in the Vanilla Content category, so there wasn't much reason for a category to exist just for one quest (survival)
- Menues like Custom Enchantments, Crates, Resources, Spawn Eggs, Others and Skulls were all put into one menu button which is now called "Server Shop" as all the former mentioned menu buttons are basically just a server shop in a different fasion (survival)
- The Elites button now directly leads to the Elite Cookies menu as all the other ones were moved to the Server Shop (survival)
- StatTrak Creator was moved from the Others server shop to the Custom Enchantments as the Others server shop really only had the StatTrak Creator and Mana Potions. Mana Potions were removed entirely as I don't see anyone using them (survival)

## 2025-09-01
### Changed
- Some internal changes to how the welcome message of new players is handled (lobby)
- Some internal changes to how the items you're given is handled. I also made the name and lore of the Recovery Compass look a little nicer (lobby)

## 2025-08-31
### Changed
- Elytra Unbreaking enchantments can now be bought in '/menu' -> Custom Enchantments instead of '/menu' -> Elite -> Custom Enchantments. It seemed a little disconnedted and confusing that way. I hope this won't be an inconvenience to anyone (survival)
- Elytra Unbreaking enchantments have been lowered to level 12, 24 and 48 to actually double the durability of the elytra. Also level 70 seemed a little too strong in terms of how long it makes your elytra last. This could still be subject to change but at least for a little while I'd like to try these numbers. Elytras with existing Unbreaking 70 will stay that way and not lower their enchantment level! (survival)
### Added
- Fancy Diamond Sword Crate 2 has been released and it costs 1 MetaCoin and 1 Diamond Sword to open (survival)

## 2025-08-30
### Removed
- The bidding functionality of the auction house was removed as it wasn't used much and I'm afraid it might lead to confusion of how it works (survival)
### Changed
- The bottom right book of the auction house now explains how to use '/ah sell \<price\>' instead of being rather vague about it (survival)
### Added
- You can now either use '/togglelocatorbar' or go into the '/menu' -> World Related and toggle it from there (survival)
- You can now also toggle if you're hidden or shown on the online map again (survival)

## 2025-08-29
### Fixed
- The NPCs Diamond_Sam, LenaTheEevee and an_normal_human for some reason had lost their skins a while ago and I wasn't able to fix it. Today I managed to fix this (by simply using their UUID in the command instead of the name which I wouldn't expect to make a difference but apparently it does) (survival)

## 2025-08-28
### Added
- You can now buy 1 Elite Cookie for 300 vanilla levels in the Elite Cookie Shop (survival)
### Changed
- TSMs are now called PSMs as TSM stood for Toggleable Skill Multiplier and now they're Permanent Skill Multipliers. This will make the whole system simpler as they'll be always active and also they no longer cost a bit of your salary (survival)
- You now get 2 stacks of gunpowder instead of 1 for 1 Elite Coin (survival)

## 2025-08-07
### Added
- New Tutorial book called "Plot Commands" to explain different plot commands like '/plot visit ...' and some more. This should help the people that want to visit other plots or want to get back to their own plots (creative)

## 2025-07-28
### Added
- '/locatorbar color \<hex code\>' to set the color of your locator bar icon (survival, creative)
- '/locatorbar color reset' to reset the color of your locator bar icon (survival, creative)

## 2025-07-26
### Changed
- Armor Trims are now an allowed NBT compound (creative)
- Boss kills needed for TSMs previously were "Warden, Elder Guardian, Wither, Ender Dragon" and have now been changed to "Elder Guardian, Ender Dragon, Wither, Warden" in that order. This was mainly done to reflect the difficulty of each mob (survival)

## 2025-07-24
### Changed
- Updated all servers to 1.21.8 (survival, creative, lobby)

## 2025-07-22
### Changed
- Graves plugin was swapped out as the old one had bugs and was no longer maintained (survival)
- Graves no longer require 50 MetaCoins to open, they're now free (survival)
- Graves spawn in towns now but they can't really be weaponized as they're free to open, a person has a max of 8 graves at one point and you can't collide with them, so it should be alright (survival)
- Most of the other features of graves stay the same (survival)

## 2025-07-19
### Changed
- Stone now has a chance of spawning a silverfish instead of a baby zombie (extreme)
### Added
- Silverfish drop 1 iron nugget when killed (extreme)

## 2025-07-18
### Changed
- Infinite water sources have been disabled (extreme)
- Villagers can no longer spawn (extreme)
- Wandering Traders can no longer spawn (extreme)
- You can no longer craft crafters or enchanting tables (extreme)
- Experience orbs no longer spawn from anywhere (extreme)

## 2025-07-12
### Removed
- Plots in creative are no longer shown on the online map, it was causing quite a lot of lag unfortunately (creative)

## 2025-07-10
### Changed
- Updated server to 1.21.7 - wooh, doggo painting!! :D (lobby, creative, survival)

## 2025-07-05
### Changed
- Updated server to 1.21.6 (creative, lobby)

## 2025-07-03
### Changed
- Updated server to 1.21.6 (survival)

## 2025-07-02
### Changed
- Particles to visualize the clipboard are no longer the scrape particle but redstone dust instead as scrape particles have a sound attached to them on Bedrock Edition which creates a **lot** of noise (creative)

## 2025-06-30
### Removed
- Title message that's shown every 6 minutes if you haven't voted within the last 24 hours was removed as its effects are questionable and we hopefully have a new incentive to get people to vote. It's still greatly appreciate every time you vote <3 (creative)
### Changed
- The old plugin that shows virtual books like in the Tutorial menu was removed as it's been replaced with something else (creative, survival)

## 2025-06-28
### Fixed
- Debug sticks would often complain about being an illegal item, that should now be fixed (creative)

## 2025-06-11
### Fixed
- Found out that regular users couldn't actually open crates as the permissions were bound to a role but said role was only obtained by doing a quest which was removed some time ago... sorry about that, crates should now be available to anyone! (survival)

## 2025-06-09
### Changed
- Sniffer sizes now only range from 1.3 to 0.5 as opposed to the previous 2.0 to 0.5. This change had to be made as bigger size sniffers can't breed due to a Mojang/Minecraft bug: <https://report.bugs.mojang.com/servicedesk/customer/portal/2/MC-298644>. This will be reverted whenever Mojang fixes said issue (survival)
### Added
- More items with custom models have been added through various means, mostly skill related (survival)

## 2025-06-06
### Changed
- Fishing rods with custom models/skins will now have increased durability shown in the lore which is based on the quality (survival)

## 2025-06-02
### Added
- 2 Netherite Scraps can now be bought for 1 Elite Coin (survival)

## 2025-06-01
### Added
- Collectible Cards Crate 1. It contains almost 100 collectible cards! (survival)

## 2025-05-31
### Changed
- '/vote' now looks slightly different and uses the Meta-Union default color scheme. It also now explains a little more what voting really does for Meta-Union <3 (lobby, creative, survival)
- The Steed Speed quest now grants mobs you mount a 10 minute speed 2 effect. The effect also ends when you dismount. This was changed because the quest was added when elytras were still banned, so getting around faster was rather unique but now I thought I should do horses etc justice by boosting them even outside of paths (survival)

## 2025-05-29
### Changed
- Elite Cookies now only cost 2,500 MetaCoins instead of 5,000 MetaCoins. They seemed a little expensive currently, making most people prefer fishing over the Elites (survival)
- You can now use the auction house from any chunk of a town, not just the shop plot (survival)

## 2025-05-25
### Fixed
- If you had a potion effect applied that was longer than vanilla default, it was removed when disconnecting or going to the hub. That is no longer the case now and was actually never meant to be the case. Sorry for any inconvenience this may have caused (survival)

## 2025-05-23
### Added
- Chest Shops are back!! (survival)
- Fancy Diamond Sword Crate has been added which I have asked about in a Discord poll before (survival)
- The Elytra crate can be bought with a dragon head again, additionally to the one you can buy for an Elytra (survival)

## 2025-05-18
### Changed
- If you use '/ah' outside a shop plot now, you'll get a book opened that explains how it works. The previous message in chat wasn't quite enough to really make everyone understand how auction houses work (survival)

## 2025-05-17
### Changed
- Server was updated to 1.21.5 (creative)
- Skulls are working again (survival)
- You can no longer hide on the online map (survival)

## 2025-05-15
### Changed
- You can no longer combine two Unbreaking 4 custom enchantment books to make an Unbreaking 5 custom enchantment book in an anvil. This was never intended to happen and was only made possible due to me allowing the use of anvils to add enchantments to items but it was never meant to be used to improve the enchantment's level itself. The same goes for any other Unbreaking custom enchantment book (survival)

## 2025-05-13
### Fixed
- You could previously buy crates with a full inventory which lead to you paying money and the crate telling you you can't open it with a full inventory. That's now been fixed and you're required to have an empty inventory slot before the crate even opens (survival)
### Changed
- The Diamond Sword Crate 1 has been changed. You now have to pay one unchanged, unenchanted diamond sword and 1,000 MetaCoins to get a diamond sword with a skin. This change will eventually be done to all the crates except plushies (survival)
### Added
- New WorldEdit visualizer with particles which is (according to me) better than the old one. We also decided it needs new particles which have been chosen by the community (creative)

## 2025-05-10
### Added
- New system has been installed to prevent crash items, force OP signs and similar illegal items. If you find any (legitimate) issues with this system, please let me know (creative)
### Changed
- A different plugin to visualize WorldEdit selections as the old one was not open source but the new one is! \o/ (creative)

## 2025-05-03
### Changed
- The elytras with higher durability were swapped out for custom enchantments that only work on elytras. That makes it possible to also have longer lasting elytras with custom skins (survival)

## 2025-05-02
### Added
- Due to high demand, I've added elytras with 2x, 5x and 10x the regular durability to the Elite Shop, enjoy! (survival)

## 2025-05-01
### Added
- Level 10 and 11 Elite Cookies (survival)

## 2025-04-28
### Added
- PvP button to toggle PvP from the '/menu' (survival)

## 2025-04-23
### Changed
- PvP can now be toggled again with '/togglepvp'. PvP is turned on by default (survival)
- Technically we're using a different PvP plugin again (survival)
- The PvP status now ignores the PvP setting of a town or rather, technically speaking, towns have PvP force on but if you toggle it off, that'll override the forced on PvP of a town (survival)
### Removed
- '/killstats' is no longer a command as it was a feature of the old plugin which we swapped out (survival)

## 2025-04-20
### Added
- Votes now have a 10% chance to pay 4,000 MetaCoins (creative)
- Votes now have a 10% chance to pay 2,000 MetaCoins (survival)
### Removed
- Quests no longer increases how much money you earn from voting and any previously gained advantage is obsolete (survival)
- Quests no longer grant 2,000 MetaCoins for things like sprinting, farming, chopping trees and so on. It simply felt like favoring certain activities while others weren't and if I wanted to keep it balanced, I would have needed to add an infinite amount of quests which would have to be expanded on every update (survival)

## 2025-04-18
### Added
- 3 more levels of Elites, up to level 9 now (survival)

## 2025-04-16
### Added
- 3 more levels of Elites (survival)

## 2025-04-13
### Changed
- The Strike enchantment no longer deals damage to players, mobs or blocks nearby (survival)
- You now have to put custom enchantments on items through the anvil, just like in vanilla (survival)
### Removed
- The Strike enchantment was removed from the menu so it can no longer be obtained (survival)
- Curse of Masking had to be removed as you could otherwise enchant a stack of player heads with just one book. Hopefully we'll find a replacement at some point (survival)

## 2025-04-08
### Added
- Plushy Crate has been added for only 1k MetaCoins! (survival)
### Changed
- Newly obtained plushies can now be worn on your head (survival)

## 2025-04-04
### Added
- Elite Cookies can now be bought in '/menu' -> Elites for 5k MetaCoins. These cookies spawn an Elite where you stand and currently there are 3 levels. Expect more in the future! (survival)

## 2025-04-02
### Changed
- Newly spawned mobs should no longer burn in sunlight (creative)
- Newly spawned ghasts can be killed again (creative)

## 2025-03-30
### Added
- You can now see everyone on all servers in the tab list (except lobby2 and test servers). It still needs some final touches but the feature generally works and you can finally see at a glance who's online again! (all servers)

## 2025-03-24
### Changed
- Elite Spawn rates increase. Overworld went from 1% to 2%. Nether went from 2% to 3%. End went from 3% to 4%. (survival)

## 2025-03-22
### Changed
- The menu and all sub-menues provided by Meta-Union have received a facelift. Other servers will follow :) (creative)
- Please make sure to read '/rules' again. Rule 12 was added, some of the clarifications were changed and added onto and some rules slightly rewritten! (all servers)
- The '/rules' menu has gotten a new look, you might want to check it out (all servers)

## 2025-03-20
### Changed
- The economy plugin was changed but all the money was migrated to the new one so nothing was lost. Currently you have to use commands that start with '/money' such as '/money pay <user> <amount>' to pay someone but on the next restart '/pay' and '/bal' and the likes will be back (survival, creative)

## 2025-03-16
### Added
- MobTrak can now be obtained from killing mobs. These items act like the FishTrak but they track how many mobs you've killed with the weapon. The current chance to get one is 1 in 1,000 but this number is affected by your luck stat and the chance might vary over time (survival)
- BlockTrak can now be obtained from Mining, Excavating or Farming. BlockTrak tracks how many mobs you've killed with a weapon. I won't mention the chances cause they're different for each skill and might also be changed over time (survival)
- StatTrak can now be bought in the Others category of the Elite Shop for 16 Elite Coins (survival)
- Fishing rods with custom model data you get from fishing now have a quality which can range between 1 and 100. It has no technical meaning though (survival)

## 2025-03-13
### Added
- You now earn extra money when near other players. For now it's an extra 15% of income when there are 2 or more players within 64 blocks. Any AFK players are not taken into the equation at all. (survival)
- Rule 11 now clearly states that you're not allowed to use alts to earn extra resources, coins or anything similar (all servers)
### Changed
- The salary message now only states that you earned money, not how much as with the new system it can get confusing for players to see earning more or less with no clear indication as to why (survival)

## 2025-03-12
### Changed
- Pretty much all quests that used to be related to skills have been changed. They no longer reward skill exp as that throws off the balance of which tasks for certain skills are most beneficial. Also some of the quest categories have been reworked (survival)

## 2025-03-09
### Added
- Curse of Masking has been added to the Custom Enchantments. It'll add Curse of Binding and Curse of Vanishing to any player head (survival)
### Changed
- Crates are now unlocked after 25 hours instead of requiring 25,000 MetaCoins in your '/bal'. Only really active players were likely to reach the 25k and even some of those would deposit their money into the town and thus never unlocking crates. The new requirement of 25 hours makes it possible for anyone to unlock them while not having to specifically aim for it (survival)

## 2025-03-09
### Changed
- The quest to unlock chest shops has been removed and everyone was given the permission to create up to 100 as that's the maximum. This was mainly done because people often got confused how to unlock chest shops and they had forgotten about quests at all at that point (survival)
- The tutorial book on chest shops was updated (survival)
- The quest to unlock custom enchantments has been removed and everyone was given the permission to see and open the custom enchantments button in '/menu' (survival)

## 2025-03-05
### Changed
- The quest to unlock hiding on the map has been removed and everyone was given the permission to use both '/map hide' and '/map show' as well as see the buttons in the menu. This was mainly done because due to PvP it's now much more important to be able to hide on the map (survival)
### Added
- Elite Fishing. That means you'll now have a chance to earn Elite Coins when you're fishing with someone else nearby, up to 4 players in total where the chance also increases the more players you are! (survival)

## 2025-03-03
### Fixed
- Shops that sell or buy more than 1 item now show the proper prices in the GUI (survival)
- Shops now update their signs again as they should (survival)
- Decapitation used to have 5, 10 and 15% chance for their respective levels while in the GUI it said it was 33, 66 and 100%. The enchantment is now actually properly set to 33, 66 and 100% (survival)
### Added
- Simple Voice Chat mod support. It might take a little bit until it's rolled out for everyone connecting but after at most 24 hours it should work for anyone connecting (all servers)

## 2025-02-28
### Added
- There is now a '/pvpstats [user]' command which tracks things such as kills, deaths and PvP points (survival)
- You now earn PvP points from killing people but you also lose them from dying in general, to more incentivise not dying constantly (survival)
- There is now '/killrecaps' which shows a list of recent PvP kills (survival)
- New Farming quest for sugar cane (survival)
### Changed
- Technically the PvP plugin was swapped out but should function almost identical to the old one except for the previously mentioned additions (survival)

## 2025-02-25
### Changed
- Anyone that's tagged due to PvP will be glowing during combat and stop glowing after combat (survival)

## 2025-02-23
### Added
- Elites for the end dimension have been added, being called End Elites. These will take at least 3 players to be killed and spawn quite frequently alongside endermen. They also have a guaranteed chance to drop an elite coin (survival)
### Changed
- Elites in the nether are now called Nether Elites (survival)

## 2025-02-22
### Changed
- You are now given the same "Changes You Must Know About" book when you join for the first time as the one you find in '/menu' -> Tutorials (survival)
### Added
- There is now a "Newbie Guide" in '/menu' -> Tutorial. This same book is also handed out to people that join for the first time. It explains all the most essential things we recommend you do on the server (survival)

## 2025-02-21
### Changed
- You can no longer glide with the elytra in the overworld or the nether. It's now only possible in the end dimension (survival)
- You can now boost an elytra with firework rockets just like in vanilla. The previous change still applies to this of course (survival)

## 2025-02-17
### Changed
- You can now change custom model data of items with '/ie custommodeldata <number>' instead of renaming it in the anvil (creative)
### Added
- Strength Gear has been added to the Elite Shop (survival)

## 2025-02-15
### Changed
- Due to some issues with the old plugin, the server now uses a new villager optimization plugin but it functions pretty much the same (survival)
- Villagers now only get optimized when called 'Optimize' (survival)
- You'll have to once more rename your villagers to 'Optimize' if you want to be able to trade with them again (survival)
### Removed
- Villagers no longer get optimized when standing on a brick block (survival)

## 2025-02-03
### Changed
- PvP is now turned on outside of towns with no option to opt-out (survival)
- PvP is turned off inside of towns by default but can be toggled on by using '/town toggle pvp' (survival)
- The menu button to toggle PvP has been removed (survival)
- The permission to toggle PvP with '/pvp' has been removed (survival)
- PvP death messages are now shown globally again (survival)
- PvP status is no longer shown next to the name above the player (survival)

## 2025-01-26
### Changed
- The merge radius of items was changed to 3. This means similar items will stack from farther away once again but only if their Y level is the same. This should hopefully reduce lag for some people and it will effectively change after a server restart (survival)
- Creative has been updated to 1.21.4 and along with it all its plugins have been, too (creative)
- More NPCs now have custom model items. We might also add them to the creative spawn soon enough :) (survival, lobby)

## 2025-01-23
### Added
- New, more sophisticated anti spam system which should work MUCH more efficiently against people sending messages in chat real fast (all servers)
### Fixed
- Items with custom model data did not give enchanting skill experience, now they do (survival)

## 2025-01-20
### Changed
- Mobs that die from suffocation no longer drop items because rescaled mobs drop their items too often and mobs like zombies pick up their loot and then can no longer despawn naturally (survival)
- The monster cap per player has been reduced from 28 to 22 which should hopefully result in less crowds of mobs near towns but still have enough mobs on the surface to be tough. This also means any monster farms have been reduced in output by roughly 20% (survival)
### Added
- 3 new quests for the excavation skill as the dirt quest was a little tedious to achieve as lots of people use dirt for terraforming and place it (survival)

## 2025-01-19
### Fixed
- You no longer stop being AFK immediately when you go AFK on a redstone ore, pressure plate or similar blocks (survival)
### Changed
- Slightly changed how the '/stuck' command works as there have been reports of it sometimes not giving the chorus fruit (survival)

## 2025-01-18
### Added
- '/changescale <0.01 - 16>' lets you change your own player's scale (creative)
### Changed
- Downloading the server resource pack is now handled slightly differently. You'll have to change if you want to have it enabled or disabled through the Minecraft server list from now on (all servers + proxy)

## 2025-01-17
### Added
- Added a new crate with custom skin axes (survival)

## 2025-01-16
### Added
- Rule 10 now states that you are not allowed to build traps of any kind. Although I think it already falls under respecting other players and building traps isn't doing so because you aren't respecting their PvP status, I still feel like it helps clarify it's against the rules (all servers)

## 2025-01-14
### Added
- 2 second cooldown on messages in global chat so we won't see as bad of an outcome from spammers as we did lately. This is more of a temporary fix, something more sophisticated will follow as soon as possible (survival, lobby, creative)
- Builders can now use '/pw set <warp_name>' as well as '/pw remove <warp_name>' again. This was apparently forgotten as the builders server was merged into creative. Only builders have access to create, delete and warp to them, regular users do not! (creative)

## 2025-01-12
### Fixed
- craftFlower now shows the heads for navigation properly again (creative)
### Added
- craftFlower has added the new blocks such as Hanging Roots, Moss Carpet and Pale Blocks (creative)
### Changed
- Elites no longer spawn glowing so you'll only see their nametag behind walls. This should hopefully make them less frightening and intrusive as the glowing effect can be pretty strong and irritating. I'm just experimenting with them right now, so bear with me while we're trying to figure their visuals out properly (survival)
- Elites are now zombies instead of creepers (survival)
- Elites now wear an orc custom skull to visualize that they're different (survival)
- Elites no longer have a chance of dropping their regular loot. This was mainly done as otherwise you could farm custom skulls with Elites (survival)

## 2025-01-10
### Changed
- You can now optimize and un-optimize villagers much quicker, the cooldown was previously set to 10 minutes, it is now 8 seconds (survival)
- Gunpowder and String was added to the Elite Shop (survival)
- People can now damage each other (PvP) even within the same town also known as friendly fire (survival)

## 2025-01-08
### Added
- Several more map arts were added to the map art shop (survival)
- A new Tutorial book explaining how merging towns works as it's been reason for confusion in the past (survival)

## 2025-01-07
### Added
- NPCs were added near the portals which let you join servers by simply clicking on them (lobby)
- Both the portals and the NPCs now tell you that you can use '/queue \<server\>' instead so if they ever fail, which they technically can, you still have the option to type in the command which works differently than the portals or the NPCs themselves. And while I could technically make them work the same way, that poses a security risk which is why it's not done (lobby)
### Removed
- The "Built by..." NPCs no longer open the Menu when clicked as it seems rather unintuitive and the compass already does that (lobby)

## 2025-01-06
### Fixed
- When opening shulker boxes within your inventory while standing on redstone ore wouldn't allow you to open them. That's now possible (survival)

## 2025-01-04
### Added
- Plugin to see plots on the online map through another plugin which doesn't seem to cause the lag the previous plugin did (creative)

## 2025-01-03
### Removed
- Plugin to see plots on the online map BUT it might make a return with another plugin. The reason was that it was causing periodical lag which is now gone (creative)

## 2025-01-01
### Added
- You can now buy spider eyes in the Elite Shop (survival)
- You can now buy phantom membranes in the Elite Shop (survival)
### Removed
- Bats no longer drop phantom membranes as they can now be bought in the Elite Shop (survival)

## 2024-12-31
### Added
- Unbreaking 6 has been added to the Custom Enchantments (survival)

## 2024-12-28
### Added
- You can now buy Bones in the Elite Shop. Expect more mob drops to make up for (intentionally) broken mob farms due to differently sized mobs (survival)
### Removed
- The plugin which allowed you to see farther. It turned out this plugin causes lag on connections with low bandwidth. (survival)
### Fixed
- Elite Coins were no longer accepted in the Elite Shop as the item data had changed since version 1.21.4 (that's something Mojang did). That should now be fixed (survival)
### Changed
- Some color adjustments to the output of commands such as '/fs <0-10>' (creative)

## 2024-12-27
### Added
- 1.21.4 support which adds all the 1.21.4/Pale Garden content! (survival, lobby)
- Speed Gear has been added to the Elite Shop (survival)
### Removed
- The plugin which allowed you to repair items for higher vanilla level cost was removed as it was too buggy, leading to unexpected and inconsistent outcomes of repairs (survival)
- Speed Crates have been removed from the Crates menu as it's been moved to the Elite Shop instead. Expect more cosmetic items in the Crates soon however :) (survival)

## Survival's Changelogs up to 2024-12-21 (this isn't pretty and it isn't even supposed to be... but it'll stay this way unless someone takes the time to make it pretty)

- **2024-12-21**
- + Mana Potions can now be bought from the Elite Shop!
- **2024-12-20**
- + The Fighting skill now has the ability called Recovery which recovers more health from hunger/food.
- + The Enchanting skill now has the ability called Splasher which makes splash potions last longer depending on players hit.
- **2024-12-17**
- + Elite Shop got diamond chestplate luck gear
- * Wisdom has been reworked and especially the Anvil Discount
- * Fixed a bug where you could repair anything in an anvil without increasing its repair cost
- **2024-12-16**
- + Elite Shop has been added to '/menu' with the first few items but more will follow soon!
- - Stat Gear Quest was removed as it'll be replaced by the Elite Shop
- - Stat Gear Menu was removed as it'll be replaced by the Elite Shop
- **2024-12-13**
- * Merging towns is now 25,000 MetaCoins to make it easier for smaller towns to merge and to allow people to more easily play together
- **2024-12-08**
- + Elites have been added and Elite Coins along with them but there is currently no Elites Shop to spend the coins on, that'll come later :)
- **2024-12-07**
- * You no longer get kicked out of boats on the ice path if you're on a client version older than 1.21.3
- * After the next restart some items like cobblestone will not despawn on the ground as fast anymore
- **2024-11-26**
- + Added Diamond Sword Crate 1 which contains diamond swords with SKINS!
- **2024-11-25**
- * Server now runs 1.21.3!
- - Removed quest for bundles as they can now be crafted
- **2024-11-24**
- + Armor stands can now be locked with the Armor Stand Editor tool. This should help so armor stands do not get broken accidentally.
- **2024-11-14**
- * Made repeatable quests give less money
- * Made Meta-Union Crate 1 reward less iron and diamonds
- + Added '/crate' to open the crates menu right away
- **2024-11-08**
- + Added Speed Crate to '/menu' -> Crates
- - Removed Stat Gear Armor as it'll be moved to Crates soon enough
- **2024-11-05**
- * You can no longer change color or format of lore or use MiniMessage format in them. This was done so it's reserved for Custom Enchantments and the likes.
- **2024-11-02**
- + You can now add, set and reset lore of items once you unlocked it in the Quests. This lore can also contain color code and MiniMessage format.
- + The sames goes for renaming items through a command. Learn more by finishing the quest.
- **2024-11-01**
- * Fixed a critical issue where you could break chest shops
- **2024-10-27**
- * Zombie and Skeleton Horses no longer despawn when they enter a town
- **2024-10-17**
- + Lots more mobs that can vary in size cause they're fun :D
- **2024-10-08**
- + Crates have been added along with a quest to unlock them. You can also see the odds of any crate before opening it :) Enjoy spending your money <3
- **2024-09-28**
- + You can now use '/stat' or '/statistic' to look up all vanilla statistics in many cool ways! Try it out!
- * Changed it so certain amounts of residents don't result in an increase of upkeep which for example allows having a second resident in your town without increasing the upkeep right away. A third resident however would increase it just like before.
- **2024-09-26**
- * You now have to sneak and left click to create a shop which is mainly done so you aren't spammed when trying to break lots of chests
- * Towny permissions have been changed drastically but hopefully without losing anything of importance. If you notice anything, contact Folas1337!
- **2024-09-23**
- + You can now fish up tridents
- * Drowned are now roughly 3x as likely to drop a trident
- **2024-09-22**
- * PvP kills now steal 10% of the victim's balance and nothing from the town's bank anymore
- **2024-09-11**
- * Salary Quests are working again, each granting +25 MetaCoins
- * Active TSMs impact your salary again but their dent in your salary has been decreased
- **2024-09-02**
- * Lots of changes were made to the skill system. There will be a lot more tweaking, details can be found on the GitHub if you want them. It's too much to explain it all here...
- **2024-08-30**
- * You now require Enchanting level 12 to unlock higher vanilla enchants as it was annoying for newer players to combine two bows with Unbreaking 3 only to be told it's too expensive.
- **2024-08-25**
- * Custom Enchantments now only need one quest to unlock, not a separate one for each slot anymore.
- **2024-08-21**
- + Added a Fourth Salary Raise Quest
- * Made the previous Salary Raise Quests easier so especially early players can have a little more money :)
- **2024-08-11**
- + Lure 4 was added
- + Luck of the Sea 4 was added
- - Custom Enchantment Lucky Hook has been removed
- **2024-08-10**
- - Custom Enchantments Ravenous and Replenish have been removed
- * Hunger Loss in the Endurance skill now starts with 10% instead of 5% and increases by 4.5% instead of 5% each level
- **2024-08-09**
- * Towns now have an unlimited amount of chunks they can claim since the limiting factor is money, really.
- **2024-08-08**
- + You can now GLIDE with Elytras in any dimension but not use firework rockets or riptide to boost yourself while flying!
- **2024-08-07**
- - '/res spawn' or '/p spawn' have been disabled as they were never meant to work
- **2024-07-31**
- + Looting 4 has been added
- - Diplopia has been removed
- - Hasten has been removed
- - Timber has been removed
- - Replanter has been removed
- **2024-07-30**
- + Chest Shops have been added again!
- + You can now search for chest shops by using '/finditem'
- + Quests for Chest Shops have been added again!
- **2024-07-20**
- + Efficiency can now go up to level 6!
- - Hasten is no longer obtainable through custom enchants
- - Custom enchants can no longer be toggled through the menu
- **2024-07-19**
- - You can no longer obtain Timber from '/e' as it has too many incompatibilities, sorry :(
- * Second Salary Raise quest now requires votes instead of daily quests as daily quests will be removed soon.
- * Salary Raise quests are now a little easier in terms of how many votes you need.
- **2024-07-17**
- - You can no longer obtain Replanter from '/e'
- * Mining gives way less armor durability protection, back to the default of the skill plugin! Use Unbreaking 5 on your armor for it to last :P
- * Diamonds drop much rarer from Excavation now (1/4th as likely as before)
- **2024-07-16**
- + Newly spawned Pigs, Chicken, Cows and Sheep can now have a random scale between 0.5 and 1.5, so they can be 50% larger and 50% smaller and everything in between.
- **2024-07-08**
- * Mayors now also pay town taxes but they can never be kicked from the town! This is mainly so your town doesn't die while you are away and there was money left in the mayor's pockets.
- **2024-07-07**
- * Unbreaking now goes up to level 5!
- **2024-07-06**
- The server now runs 1.21 so you can enjoy all the blocks, mobs and features it has!! Enjoy!! <3
- 
- - Chest Shops. The developer has stopped support but we're searching for a replacement
- - Daily Quests. It currently has a bug but it'll hopefully be resolved soon :)
- + Exploration Maps work again but they can lead to similar/already generated structures!
- * Opening Angel Chests only costs 50 MetaCoins from now on!
- * Reworked Hard Mode and Easy Mode, the latter is now called Vanilla Mode.
- + Added Extreme Mode which is only available with at least 100 hours playtime.
- **2024-06-25**
- + Unbreaking 4 can now be made by combining 2 Unbreaking 3 books in an anvil!
- - Reforged, Nylon Thread and Reinforced have been removed due to Unbreaking which will slowly replace it
- * Town bankruptcy has been simplified. You now have 14 days when going bankrupt and afterwards your town's deleted.
- * Mayors, co-mayors and Assistants now also pay taxes unless they give themselves the tax-evader rank.
- However mayors can not be kicked from the town and co-mayors and assistants will only be kicked if using flat taxes
- * TSMs have been reduced to a 20% multiplier as skills are now generally easier than previously.
- * Plots now automatically get set up for sale if the owner can't pay the taxes
- * The XP Convert skill of Enchanting has been changed, its formula now makes it so that you still have a pretty strong start and allows for up to 4x the vanilla exp at max level compared to the first level
- **2024-06-24**
- + Newbies can now teleport to their Angel Chests (for the first 4 hours of playtime)
- - Boss Mobs have been removed as I do not have enough time to properly maintain or integrate them, maybe another day...
- 
- + Newbies with less than 4 hours of playtime can now use '/rtp' and '/tpa <user>'
- * Skills are generally 2.5x easier to level up than previously!
- 
- * The -75% Skill XP that were mentioned for Easy Mode up until now were not active yet but have been made active now!
- These last two changes combined mean that playing in Easy Mode now means you'll have it harder than before to level up your skills but also that it's now easier if you play in hard mode.
    

## 2024-12-14
### Changed
- The water in Patpack's lobby is now bouncy, for no reason other than it being fun (lobby)

## 2024-12-07
### Changed
- You now spawn in the Christmas lobby when joining the lobby and are greeted with a firework explosion (lobby)

## 2024-12-06
### Added
- Meta-Union now supports Java clients 1.21.4 as well as Bedrock Edition 1.21.50 (all servers)
- A new allowance was added to '/rules' which mentions that you're allowed to host events on Meta-Union within your abilities. This was always allowed but I thought it might help to make it clear (all servers)
