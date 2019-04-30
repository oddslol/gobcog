Hello! You found the adventure page!

This cog was originally made by locastan and updated by Aikaterna and can be found at the fork link above.

This version is significantly different internally and features:

Differences from locastan version:
* Using Config for data management and more atomic user attribute saving
* Expanded mob/monster list for a stat and monster combo of over 2,800 possibilities
* Added 300% more gear possibilities
* Doubled the amount of item slots
* The game can be played on multiple servers at once

Differences from Aikaterna's version:
* New intelligence stat, magic attack and Wizard class
* Passive bonuses for classes that affect others in combat
* Updated monster list to give monsters different resistances to attack/magic
* Revamped combat with new calculation for critical hits and passive bonuses from classes
* Legendary weapons and chests
* New way of finding monsters that groups users first and uses their stats to find fair/fun challenges
* Cooldowns on loadout changes and costs currency, different repair costs (that can sell stuff from your bag)

Things I would like to improve in the future, or will very gladly welcome PRs on:

* Trade unopened loot boxes between players
* Add alternate stats like dexterity/agility that would affect things like critical chance (and revamping the entire system to accept and use other stats like that)
* Add player races (gives permanent bonus that scales with level for 1-5 additional points in a stat)
* Changing data structure to MongoDB, referencing items instead of storing each one again in the json blob
* Expand classes, add new abilities at different levels or new herotypes based on the original Wizard --> Warlock etc
* Any other cool ideas :)

If you have something you would like to request for this cog, PLEASE OPEN AN ISSUE HERE AND DESCRIBE IT. I will not be taking requests for this via DMs or Discord messages. 

# Introduction to Adventure! 

Start an adventure do `[p]adventure` and anyone can choose 🗡 to attack the monster, 🌟 to cast magic at the monster, 🗨 to talk with the monster, 🛐 to pray to the god Herbert (Customizable per server for admins or globally for bot owner) for help, or 🏃‍♀️ to run away from the monster. The more people helping the easier it is to defeat the monster and acquire its loot.

To start an adventure type `[p]adventure` and everyone can join in.
Classes can be chosen at level 10 and you can choose between Tinkerer, Berserker, Cleric, Ranger, Wizard and Bard using `[p]heroclass`. 

Tinkerers can forge two different items into a device bound to their very soul. From time to time, they will also sharpen the weapons of the party, increasing the damage caused during a fight. Use the forge command.

Berserkers have the option to rage and add big bonuses to attacks, but fumbles hurt. When arguing with an enemy, Bersekers can enter in a state of wild fury, that intimidates the enemy and makes the negotiation easier for the whole party. Use the rage command when attacking in an adventure.

Clerics can bless the entire group and add big bonuses to prayers, but these can remain unanswered... Divine aura can radiate from Clerics while praying, increasing the critical chances of fighters and wizards. Use the bless command when praying in an adventure.

Rangers can gain a special pet, which can find items and give reward bonuses. Use the pet command to see pet options.

Bards can perform to aid their comrades in diplomacy. Due to their natural intelligence, they learnt a little bit about magic and have a chance to decrease magic resistance with their melodious voices. Use the music command when being diplomatic in an adventure.

Wizards have the option to focus and add big bonuses to their magic, but their focus can sometimes go astray... The magic glyphs tattooed on their body are known to be bound with god, and can amplify the ritual participants while praying. Use the focus command when attacking in an adventure.

Occasionally you will earn loot chests from the monsters use `[p]loot <rarity>` to open them and become stronger. 

Sometimes a cart will stroll past offering new items for players to buy, this is setup through `[p]adventureset cart <#channel>`.

To view your stats and equipment do `[p]stats` and `[p]backpack`.

You can use earned credits to enter the negaverse and fight a nega version of someone on this server to earn more experience points and level up faster using `[p]negaverse <number_of_credits>`

```css
{Legendary:'items look like this'}
[epic items look like this]
.rare_items_look_like_this
normal items look like this
```

Note: some commands can be done in DM with the bot instead if the bot has a global bank and you want to take your time reviewing your stats/equipment or open loot chests.
