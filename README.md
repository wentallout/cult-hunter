# Cult Hunter

Nguyen Dang Khoa's work-in-progress game concept. I will use this README and the wiki to document my design.

Project Name: Cult Hunter
Genre: Hack and Slash, Rogue-likem, Adventure
Platform: PC (Windows 10,11)

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

## So what is a cult?

A cult is a group or organization characterized by extreme devotion to a particular leader, ideology, or set of beliefs, often involving manipulative and controlling tactics to influence and retain members. These groups typically isolate their members from mainstream society and may engage in harmful or unconventional practices.

Cults have been responsible for a wide range of harmful and destructive activities throughout history:

- Mass Suicides and Murders: Jonestown Massacre (1978): The People's Temple led by Jim Jones ended in tragedy when over 900 members died in a mass murder-suicide in Guyana. Heaven's Gate (1997): 39 members of the Heaven's Gate cult committed mass suicide in California, believing they would be transported to an alien spacecraft.
- Brainwashing and Manipulation: Many cults employ psychological manipulation and brainwashing techniques to control their members' thoughts and behaviors, isolating them from friends and family and making it difficult for them to leave.
- Child Abuse: Some cults have been involved in child abuse, either through neglect, physical abuse, or sexual exploitation. Notable cases include the Children of God cult and the Branch Davidians.
- Violence and Terrorism: Cults like Aum Shinrikyo in Japan, led by Shoko Asahara, engaged in acts of domestic terrorism, including the 1995 Tokyo subway sarin gas attack.
- Financial Exploitation:Many cults pressure members to donate large sums of money or turn over their assets to the group, often leaving them financially ruined.
- Isolation from Society: Cults often isolate their members from the outside world, making it difficult for them to seek help or leave the group.
- Physical and Emotional Abuse: Cult leaders have been known to physically and emotionally abuse their followers, often using fear and intimidation to maintain control.
- Human Sacrifice and Rituals: Some cults have engaged in rituals involving human sacrifice or other extreme and harmful activities as part of their beliefs.
- Criminal Activities: Cults have been involved in various criminal activities, including fraud, theft, and drug trafficking, to finance their operations.
- Deceptive Recruitment: Cults often employ deceptive and manipulative tactics to recruit new members, such as false promises of personal growth or spiritual enlightenment.

=> I think "cult" is a great unexplored theme that can be used to design a great story because the whole concept of "cult" is just a religion and they are not always 100% evil. That will put the our heroes in a `ethical gray area` (An ethical gray area is a situation in which two or more courses of action are available, and none of them appear to be ethically "right" or "wrong.")

## Plot

![image](https://github.com/wentallout/cult-hunter/assets/76118931/8a380f26-e737-460e-ab0b-d6f12b5e104f)

In the busy city of Havenbrook, there's a nameless sushi chef (so we'll just call him `Nameless`). Nameless's out for revenge because in the past a group of people murdered his master. These evil people has formed a new religious movement in the city, they worship gods from the `Otherverse`, they use forbidden magic and human sacrifice rituals to achieve their goals for money and power. Nameless is not against religions or anything, he just want them dead. He entered one of their headquarters and proceed to exterminate all of them. But then he finds out this organization is just a small part of something bigger.

The cult realized how dangerous and powerful Nameless is so they decided to put a massive $20millions bounty on him so that every hitmen in the city would look for him. Kimberly and Jigen are one of those hitmen but their boss (Eli) ordered them to bring Nameless alive to him. The hitmen duo managed to save Nameless and bring him back to `Zenith Hotel` - a hidden safe location for international assassins. Eli begins explaining that the cult has spread too wide and will affect everyone's business. He plans to gather a group of assassins to take down the cult and bring order back to the city. He's confident that with Nameless' help, they now have a fighting chance.

There are 12 cult leaders - 12 Apostles, each of them manage a different branch of the cult. These guys have crazy supernatural powers and a lot of followers.

Can Nameless and his new allies take down the 12 Apostles?

## Basic Gameplay

- Cult Hunter is a stylish, action-adventure, hack and slash game with rogue-like features

- **Hack and Slash**: Players freely express themselves through brutal combat, use guns and katana to do beautiful combos, dashing to dodge enemies' attack.
- **Rogue-like**: If players die during a run, they have to start all over again . When they clear a floor, players receive random temporary charms that boost their survivability. These `CHARM` will disappear after the stage is over but they're very powerful and will motivate the players to clear/replay.
- **Loot**: enemies will drop weapons that you can pickup and enhance/modify with runes
- **Progression**: Players gain new weapons, skills and money when fighting. If player dies, they only lose their `CHARM`.
- **Increasing Difficulty** Leveling is an outdated system in my opinion, when players progress through the story and get more powerful gear, enemies will be scaled properly to make sure it's always engaging and fun.

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

## Unique selling point

- Multiple playable characters with unique gameplay
- Fast-paced, simplified combat system that still allows freedom and creativity
- Switching weapons and fighting styles while fighting
- Multiple endings
- Interact with the environments to attack enemies

## Genre Research

- Hack and Slash Genre: hack and slash games are known for their deep combat systems, which players enjoy mastering.
- Roguelike Features: Roguelike elements, such as permadeath and procedural generation, have gained popularity in recent years. Games like "Dead Cells" and "Hades" have been successful in blending roguelike mechanics with action gameplay.
- Loot and Progression: The inclusion of loot and progression systems can provide long-term engagement for players. Games like "Diablo" and "Borderlands" are well-known for their loot-based gameplay.
- 
Great game example:
- Action Roguelike:
	- Skul - The Hero Slayer
- Hack and Slash:
	- "Devil May Cry," "Bayonetta," and "Ninja Gaiden"
   
## Market Research

- Market Trends: Keep an eye on industry trends, such as the rise of indie games, the popularity of multiplayer experiences, and emerging gaming platforms like mobile and VR.
- Competition: Analyze competing games in the hack and slash and roguelike genres to identify gaps and opportunities. Look at player reviews and feedback to understand what players like and dislike.
- Player Feedback: Gather feedback from potential players and gamers through surveys, interviews, and social media to refine your game concept and mechanics.


## Problems players have with other hack and slash games

### ⚠Problem 1: Combos are too hard to input, too long to remember

![donguri-devil-may-cry-v (1)](https://github.com/wentallout/cult-hunter/assets/76118931/a873ef9e-e62d-4213-aa5c-ff8bdf4b020c)

Let's be real here, humans are not meant to multi-task, especially when they're playing video games to relieve stress.

This is a known problems in DMC5. Here's why:
- In Devil May Cry, you have to hold too many buttons to do one simple thing. 
EX: Stinger is a sword thrust move you can do by `HOLD SHIFT` + `W` + `LEFT MOUSE`. These **holding inputs** will really add up and mess with your head when you have to do long combos.
- Most of the game inputs were designed for controllers, not for keyboards and mouse. I'm trying to make a PC game here. => Platform problems
- You drop your combo immediately if you don't press the correct follow-up attack => Timing and memory problems

=> **SOLUTION**: just make sure all inputs are limited to `TAP`, tap 2 times, tap 3 times, tap 4 times, don't hold anything, don't combine anything. Make sure all attacks can link together. Gamers have limited memory.


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


## Locations

https://github.com/wentallout/cult-hunter/wiki/Locations       

## Characters

https://github.com/wentallout/cult-hunter/wiki/Characters

## Quests

- Main quest: related to cults' activities, `INVESTIGATION` and `RAID`
- Side quest: given by random NPC in the city. EX: find missing people, dating advice, track down perverts, stalkers, ghosts, serial killers.

## Equipments

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

## Character Status

- `HEALTH` bar: if it reaches 0 your run ends and you have to try `RAID` again from floor 1.
- `DODGE` bar: character will automatically dodge incoming attack when this bar isn't 0.
- `STRESS` bar: cult members can cast psychological attacks on player that cause debuff (slow, stun, inaccuracy, damage reduction) when it reach below 0.

## ⌨Controls

Cult Hunter is designed for PC. I want players to focus on precise movements to dodge incoming complicated enemies attacks.

### Basic Movement

- Move: `W,A,S,D`
- Jump: `SPACE`
- Crouch: `CTRL`
- Look: `MOUSE`

### Dash-related

- Dash: `SHIFT`, dash into an obstacle will make characters "parkour" through it
- Dash Attack: `SHIFT` then `LEFT MOUSE`
- Dash Jump: `SHIFT` then `SPACE`
- Dash Slide: `SHIFT` then `CTRL`
- Sprint: hold `SHIFT` to sprint, you can do `WALL RUNNING` if you run and touch a wall.

### Attack-related

- Attack : `LEFT MOUSE`
- Block: `RIGHT MOUSE`
- Launcher: `SCROLL WHEEL UP`, launch enemies into the air
- Finsher: `TAP SCROLL WHEEL` to do a fancy animation and execute an enemy
- Swap weapons: `TAB`
- Change style: `F`
- Pick/throw/kick: `G`, if your character can't pick something up, like a heavy table, they'll launch it into nearest enemies. If there's nothing to pickup, they'll kick enemies.
- Skills: `1`,`2`,`3`,`4`
- Rage: `Q`+`E` (still working on this)

### Other

- Taunt: `T`

## Style Switching (`F`)

- One character can hold 2 fighting styles that they can switch to.
- EX: you can have one mode for crowd control and one mode for bossing.
- EX: Dual wield style and Chained weapon style
- You can equip different styles in a menu.
- You can also switch style mid-combo

## Let players use everything they have
 
`RANGE` matters:
- Characters do different attacks depend on the range and the angle between them and the enemies.
- `REACHING`: If your enemies are far away, your characters will automatically do long range attack to try to reach them
- `AIMING`: you do different attacks based on the body part you aim. If you aim at someone's legs, your characters will try to chop their legs.

`ENVIRONMENT` matters: players can throw bottles into enemies, shoot oil barrels, kick tables, kick enemies down a cliff, etc

`STEALTH` matters:
- You're always outnumbered by the cult, try to sneak through, disable alarms early.

`CHARISMA` matters:
- You can clear certain missions by picking the right dialogue instead of fighting.

`INVESTIGATION` matters: gathering information about cult leaders can help you prepare for them.

## Skill Tree

- `FORBIDDEN MAGIC` (ACTIVE SKILLS): people with natural magic are already extinct. Most supernatural powers in the game world comes from people making contracts with interdimensional entitie (offering something you have for power).
  
- `CURSED TATTOO` (PASSIVE SKILLS): characters have these tattoos that modify their stats (ex: Ava has the `Equalizer` tattoo that matches her stat with the strongest person in her POV)

![image](https://github.com/wentallout/cult-hunter/assets/76118931/4cd09dd3-6480-4cad-bbe3-01657721afdd)

- `AURA` (RAGE PASSIVE): characters can emit a circular aura around them when they activate `RAGE`. If enemies step inside that aura range then they have to obey a certain `RULE`. (ex: Nameless' aura makes people unable to use magic)


![image](https://github.com/wentallout/cult-hunter/assets/76118931/115ccad2-a6ea-4420-b2e6-26dcab14b4ae)

## Prototype

work-in-progress

