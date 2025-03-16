# Changelog
All notable changes to the Meta-Union Minecraft Network will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/). You can find a prettier version of these changelogs [here](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/Meta-Union/changelog/main&homepage=changelog.md&sidebar=true#/) unless you are already on Docsify-This, then you're already "here" :joy:

## 2025-03-16
### Added
- MobTrak can now be obtained from killing mobs. These items act like the FishTrak but they track how many mobs you've killed with the weapon. The current chance to get one is 1 in 1,000 but this number is affected by your luck stat and the chance might vary over time (survival)
- BlockTrak can now be obtained from Mining, Excavating or Farming. BlockTrak tracks how many mobs you've killed with a weapon. I won't mention the chances cause they're different for each skill and might also be changed over time (survival)
- StatTrak can now be bought in the Others category of the Elite Shop for 16 Elite Coins (survival)

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
