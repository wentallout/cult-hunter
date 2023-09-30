# Cult Hunter

Nguyen Dang Khoa's work-in-progress game concept. I will use this README and the wiki to document my design.

- Project Name: Cult Hunter
- Engine: Unity or Godot? (Unreal might be difficult to learn)
- Genre: Hack and Slash, Rogue-likem, Adventure
- Platform: PC (Windows 10/11)
- Control: Mouse and Keyboard

## Project MVP

Plan 1: make a 2D game to learn the basics

Plan 2: slowly implement a 3D version when there are enough assets

- [ ] Working Movement and Combat (Mouse+Keyboard)
- [ ] One playable character
- [ ] One Minion
- [ ] One Boss
- [ ] One Map

## Development

- Step 1:
Download the latest Godot here: https://godotengine.org/download/windows/

- Step 2:
```
git clone https://github.com/wentallout/cult-hunter.git
```

- Step 3:
Open `project.godot` with your Godot application

## Inspiration

![image](https://github.com/wentallout/cult-hunter/assets/76118931/fa864754-4cd0-4c80-9569-87b2279dc694)

https://en.wikipedia.org/wiki/Aum_Shinrikyo

Aum Shinrikyo was a Japanese doomsday cult led by Shoko Asahara. In the 1990s, they carried out a series of deadly attacks, including the Tokyo subway sarin gas attack in 1995, resulting in deaths and injuries. The group believed in a mix of apocalyptic and mystical beliefs, blending elements of Buddhism, Hinduism, and science fiction. Asahara and several members were arrested, tried, and some executed, leading to the group's decline.

## What is a cult?

https://github.com/wentallout/cult-hunter/wiki/What-is-a-cult%3F

## Plot

![image](https://github.com/wentallout/cult-hunter/assets/76118931/8a380f26-e737-460e-ab0b-d6f12b5e104f)

In the busy city of Havenbrook, there's a sushi chef named "Nameless" seeking revenge. Some time ago, a group of people killed his master. These evildoers have formed a new religious cult in the city, worshiping gods from the "Otherverse" and using forbidden magic and human sacrifices to gain power and money. Nameless isn't against religions, but he wants these cultists gone. He entered one of their hideouts and started taking them out. But Nameless soon discovers that this organization is just a small part of something much bigger

Realizing Nameless' immense threat, the cult puts a massive $20 million bounty on him, making every hitman in the city hunt for him. Kim and Jigen are two of these hitmen, but their boss, Eli, wants Nameless brought in alive. They manage to capture Nameless and bring him to the "Zenith Hotel," a hidden spot for assassins. Eli explains that the cult has grown too powerful and threatens everyone's business. His plan: gather a team of assassins to take down the cult and bring order back to the city. Eli is confident that they now have a fighting chance thanks to Nameless.

The cult has 12 leaders, known as the "12 Apostles," each with supernatural powers and a lot of followers. Can Nameless and his new allies defeat these Apostles and end the cult's reign of terror? The battle ahead promises excitement and danger.

## Research

### Genre Research:

- Hack and Slash (https://en.wikipedia.org/wiki/Hack_and_slash): hack and slash games are known for their deep combat systems, which players enjoy mastering.
- Roguelike (https://en.wikipedia.org/wiki/Roguelike) Features: Roguelike elements, such as permadeath and procedural generation, have gained popularity in recent years.
- Progression: players gain money to unlock/upgrade their skills. weapons and other equipments will be dropped by enemies, equipments will have fixed stats (to easily balance the game, avoid overpowered one-shot builds)

Some modern games example:
- Roguelike:
	- Hades, Dead Cells, Cult of the Lamb, Skul - The Hero Slayer, The Binding of Isaac, Slay the Spire
   
- Hack and Slash:
	- Devil May Cry, Bayonetta, Onimusha, Sengoku Basara, Dynasty Warrior, God of War, No More Heroes

 Preference: 
 - https://fptshop.com.vn/tin-tuc/giai-tri/roguelike-153478
 - https://rulaesports.vn/blog/roguelike/

### Market Research

- Market Trends: Keep an eye on industry trends, such as the rise of indie games, the popularity of multiplayer experiences, and emerging gaming platforms like mobile and VR.
- Competition: Analyze competing games in the hack and slash and roguelike genres to identify gaps and opportunities. Look at player reviews and feedback to understand what players like and dislike.

### User Research
- Playtest: test a new game for bugs and design flaws.
- Player Feedback: Gather feedback from potential players and gamers through surveys, interviews, and social media to refine your game concept and mechanics.

## Basic Gameplay

- Cult Hunter is a stylish single-player, third person shooter, action-adventure, hack and slash game with rogue-like features.
- **Hack and Slash**: Players freely express themselves through brutal combat, use guns and katana to do beautiful combos, dashing to dodge enemies' attack.
- **Rogue-like**: If players die during a run, they have to start all over again . When they clear a floor, players receive random temporary charms that boost their survivability. These `CHARM` only exists during that run and will disappear after players cleared the last stage.


- There are 2 main activities: `INVESTIGATE` and `RAID`:

- In `INVESTIGATE`:
	- Players will go through the city, looking for clues, talking to people, finding information about hidden cults.
   	- Players can accept side-quests while roaming.
- In `RAID`:
	- After player pieces together clues to find the location of a cult building. 	
	- Players will go into that building, clearing all enemies to get to the next floor.
	- After clearing a floor they will receive a buff (charm) to get stronger.
 	- `RAID` ends when players successfully kill the boss at the top of the building

Other activities: 
- `AMBUSH`: sometimes players will be ambushed by a group of bounty hunters or cultists. The goal is to simply beat all of them up and get out.

## Core Philosophy

1/ Allow players to be aggressive and constantly attacking. Some game force players to wait for enemies animation to dodge/parry which might not work on our project.

Example: https://www.reddit.com/r/DevilMayCry/comments/13v7mem/the_reason_dmc_is_so_good_its_core_philosophy_on/

2/ Slowly introduce new mechanics, split the tutorials

- If the game is complex, delay the tutorials, don't dump all tutorials in one location, split them into smaller chunks and only show them when it's relevant.
- Let players learn by playing is the best way.

EX: We can force them into a fight scenario where they have to do a specific attack input to progress, that will teach them how to use that attack.
EX: The game only pops up the crafting tutorial when players find a crafting table.

3/ Simplify the UI

- UI being too complex will be the downfall of most modern games

4/ Fun first, Difficult later

- We need to be aware of the fact that making a difficult but tedious games with misleading signals will only annoy players.
- Make the `Core Loop` fun is the first goal. We can always add elements to make the game challenging later.

## Unique selling point

- Multiple playable characters with unique gameplay
- Fast-paced, simplified combat system that still allows freedom and creativity
- Switching weapons and fighting styles while fighting
- Multiple endings
- Interact with the environments to attack enemies

## Problems players have with other hack and slash games

### ⚠Problem 1: Combos are too hard to input, too long to remember

![donguri-devil-may-cry-v (1)](https://github.com/wentallout/cult-hunter/assets/76118931/a873ef9e-e62d-4213-aa5c-ff8bdf4b020c)

Let's be real here, humans are not meant to multi-task, especially when they're playing video games to relieve stress.

This is a known problems in DMC5. Here's why:
- In Devil May Cry, you have to hold too many buttons to do one simple thing. 
EX: Stinger is a sword thrust move you can do by `HOLD SHIFT` + `W` + `LEFT MOUSE`. These **holding inputs** will really add up and mess with your head when you have to do long combos.
- Most of the game inputs were designed for controllers, not for keyboards and mouse. I'm trying to make a PC game here. => Platform problems
- You drop your combo immediately if you don't press the correct follow-up attack => Timing and memory problems

=> **SOLUTION**: just make sure all inputs are limited to `TAP`, tap 2 times, tap 3 times, tap 4 times, don't hold anything, don't combine anything. Make sure all attacks can link together. Let's just assume gamers have limited memory and design easier combat.


### ⚠Problem 2: The Paradox of Choice

![image](https://github.com/wentallout/cult-hunter/assets/76118931/04d51a5a-c7d1-485e-aaf9-667b3a09b68a)

- Giving players too many options for attacking is a HUGE PROBLEM. This might be ok for fighting games but not hack and slash games. You accidentally made players unable to play because they keep thinking about what they should do.
- Players usually have to deal with 2 situations: multiple Minions with less health and single Boss with more health

=> **SOLUTION**: Give them 2 clear buttons for single target and AoE.


### ⚠Problem 3: Character Balance

![image](https://github.com/wentallout/cult-hunter/assets/76118931/9d0647f1-b06d-404e-8046-9af5923f2fae)

When your games have multiple characters, you're gonna run into the TIER LIST problem. Some characters have better attack range, speed and always perform better than others. Players are gonna underuse most of your cast and pick the S-tier.

=> **SOLUTION**: Give every characters almost the same toolkits: Evasive attacks, AoE attacks, single target attacks. When one character does way more damage than the others, you can change their passive, make their combo string longer, requires better timing, etc.


## ⭐My Simplified Combat Mechanics

Here are the controls, all of them are just you tapping so no more headache.

![image](https://github.com/wentallout/cult-hunter/assets/76118931/a7a4d396-99a0-4c6f-9945-f53bc0fbc906)

- Combos always have 6 slots/steps. Players execute their combo by filling in these 6 slots with whatever they like, players can now easily design how they fight in their head without any memorization

![image](https://github.com/wentallout/cult-hunter/assets/76118931/86ace323-d96b-47f6-937c-e190de539bf5)


- `ENDER`: ender is a unique mechanic in Cult Hunter, after the end of a tapping combo, you can press `Q` or `E` to launch an ending explosive attack. `Q` for AoE/Range, `E` for single-target/kill boss
- `FILLER`: fillers are less-damaging attacks you add after `ENDER`, their job is to break `ARMOR`, apply `DEBUFF` to enemies or even `BUFF` yourself.

### Benefits of Long and Short Combo

- If you go for Long Combo: your `ENDER` at the end will do the maximum damage, stun most enemies in front of you. However you leave yourself vulnerable during your long attack animation. You should save this for when the enemy is `STUNNED` or when you're not outnumbered.
- If you go for Short Combo: your `ENDER` does less damage but you leave more slot in the 6 slot system -> You can do `FILLER` to debuff or `DASH` away for safety.

### Finisher

What happens when players got low health? Do they restart? Let me Introduce the `FINISHER`
- `FINISHER`: some enemies don't die but enter a `STAGGER STATE` that allows you do a special finishing move on them to replenish your HP. Make sure when we design we always add a few strong enemies that can be `STAGGER` to help players survive.

## How to design better boss experience?

### Tip 1: Telegraphing the Attack

Boss won't attack immediately, they will have wind up animations or show red range on the ground to show an attack is coming and you need to move away.

![image](https://github.com/wentallout/cult-hunter/assets/76118931/05059032-a334-4a99-99e8-6f06012d5145)

![image](https://github.com/wentallout/cult-hunter/assets/76118931/ad9cf80a-e5ea-4657-b141-45e1209f3070)

### Tip 2: Prep Corridor

The 2 gates in Mega Man trains player to prepare for the incoming boss.

![image](https://github.com/wentallout/cult-hunter/assets/76118931/6ba0c0e9-a000-46a5-b7ec-444bd3af7c78)

## Game Elements

### Characters

https://github.com/wentallout/cult-hunter/wiki/Characters

### Locations

https://github.com/wentallout/cult-hunter/wiki/Locations

### Equipments

- Stats in the game comes from `WEAPONS` and `ACCESSORIES` since **clothes are meant for fashion**. Players want to look good while they fight.

  ![image](https://github.com/wentallout/cult-hunter/assets/76118931/db5c9b1e-9c56-4947-a66b-160c2dafc6c0)

- Normal weapon: guns, blades from the modern world
- Set weapon: Certain weapons in one collection are created similarly and have similar powerful effects.
	+ Demon Slayer Set: gives user new unique skills.
	+ Paladin Set: bless its owner with big stats and shield.
	+ Insect Set :usually weak but apply crazy debuff that stacks.
	+ ...etc
- Cursed Weapon: hard to use but powerful, has some small stat debuff which force players to build their character to compensate.
- Accessories: Rings modify attacks, Necklaces modify defense, Earrings give you a passive.


## Game Mechanic

### ⌨Controls

https://github.com/wentallout/cult-hunter/wiki/controls

### Main mechanics
 
`RANGE` matters:
- Characters do different attacks depend on the range and the angle between them and the enemies.
- `REACHING`: If your enemies are far away, your characters will automatically do long range attack to try to reach them
- `AIMING`: you do different attacks based on the body part you aim. If you aim at someone's legs, your characters will try to chop their legs.

`ENVIRONMENT` matters: players can throw bottles into enemies, shoot oil barrels, kick tables, kick enemies down a cliff, etc

`STEALTH` matters:
- You're always outnumbered by the cult, so try to sneak through, disable alarms, kill long-range enemies early.

`CHARISMA` matters:
- You can clear certain missions by picking the right dialogue instead of fighting.

`INVESTIGATION` matters: gathering information about cult leaders can help you prepare for them.

### Skill System

- `FORBIDDEN MAGIC` (ACTIVE SKILLS): people with natural magic are already extinct. Most supernatural powers in the game world comes from people making contracts with interdimensional entitie (offering something you have for power).
  
- `CURSED TATTOO` (PASSIVE SKILLS): characters have these tattoos that modify their stats (ex: Ava has the `Equalizer` tattoo that matches her stat with the strongest person in her POV)

![image](https://github.com/wentallout/cult-hunter/assets/76118931/4cd09dd3-6480-4cad-bbe3-01657721afdd)

- `AURA` (RAGE PASSIVE): characters can emit a circular aura around them when they activate `RAGE`. If enemies step inside that aura range then they have to obey a certain `RULE`. (ex: Nameless' aura makes people unable to use magic)

![image](https://github.com/wentallout/cult-hunter/assets/76118931/115ccad2-a6ea-4420-b2e6-26dcab14b4ae)

### Character Status

- `HEALTH` bar: if it reaches 0 your run ends and you have to try `RAID` again from floor 1.
- `DODGE` bar: character will automatically dodge incoming attack when this bar isn't 0.
- `STRESS` bar: cult members can cast psychological attacks on player that cause debuff (slow, stun, inaccuracy, damage reduction) when it reach below 0.

### Style Switching (`F`)

- One character can hold 2 fighting styles that they can switch to.
- EX: you can have one mode for crowd control and one mode for bossing.
- EX: Dual wield style and Chained weapon style
- You can equip different styles in a menu.
- You can also switch style mid-combo

### Quests

- Main quest: related to cults' activities, `INVESTIGATION` and `RAID`
- Side quest: given by random NPC in the city. EX: find missing people, dating advice, track down perverts, stalkers, ghosts, serial killers.
