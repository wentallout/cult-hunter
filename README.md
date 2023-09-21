# Cult Hunter

Nguyen Dang Khoa's work-in-progress game concept. I will use this as a guide while coding it.

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

## Plot (work-in-progress)

![image](https://github.com/wentallout/cult-hunter/assets/76118931/8a380f26-e737-460e-ab0b-d6f12b5e104f)


In the bustling city of Havenbrook, a seemingly ordinary sushi chef known as Nameless embarks on a relentless mission of vengeance. Years ago, his beloved master fell victim to a shadowy cult's sinister machinations. Armed with remarkable knife skills honed over the years, Nameless sets out to dismantle the very organization that took everything from him.

However, after a fierce battle, Nameless discovers that the cult he's been battling is merely a subsidiary of a more insidious and elusive cult. His unyielding pursuit of justice takes him to Havenbrook City, where he boldly declares war on the enigmatic cult, capturing the attention of all who reside in its shadow.

In a cinematic turn of events, we find ourselves in Zenith Hotel, a discreet sanctuary for assassins, where two renowned hitmen, Kimberly and Jigen, have been entrusted with the cult's latest contract: to eliminate Nameless. But their employer, Eli, the enigmatic owner of Zenith Hotel, has different plans. He commands them to deliver Nameless directly to him.

Within the confines of Zenith Hotel, Nameless is initiated into the intricate and treacherous rules of the criminal underworld. Eli unveils a shocking revelation: the cult's pervasive influence, clandestinely manipulating every facet of the city—how its people live, what they learn, and even the news they consume. While Zenith Hotel may have maintained an ambiguous stance, the cult's growing reach has tipped the scales, necessitating a drastic response.

Eli confides in Nameless, revealing the hotel's newfound purpose: to unite the nation's most skilled assassins and obliterate the malevolent cultists. He places his faith in Nameless's formidable abilities, believing that they finally possess the strength needed to confront the cult's menace head-on.

As Nameless and his resolute allies continue their relentless campaign against the cult's numerous factions, they eventually cross paths with the Apostles—a formidable cadre of twelve charismatic leaders who hold the reins of power within the cult. These enigmatic individuals have garnered the allegiance of the city's elite, rendering them formidable adversaries. Operating in the shadows, the Apostles remain elusive, thwarting all attempts to track them down.

Nameless and his allies must pool their skills and resources, striving to vanquish these twelve formidable adversaries. All the while, they unravel the cult's dark agenda for the city, one that threatens to plunge it into eternal darkness. The destiny of Havenbrook hinges on the shoulders of Nameless and his steadfast companions as they confront the Cult Leaders and their loyal followers in epic battles. Armed with unwavering determination, cunning intellect, and unmatched expertise, they must thwart the Cult's malevolent scheme before it engulfs the city, ensuring justice prevails for all who have suffered.

## Basic Gameplay

- Cult Hunter is a stylish, action-adventure, hack and slash game with rogue-like features
- **Rogue-like**: players receive random temporary charms after they clear a stage/floor. These `CHARM` will disappear after the stage is over but they're very powerful and will motivate the players to clear/replay.
- **Loot**: enemies will drop weapons that you can pickup and enhance/modify with runes
- **Progression**: If player dies, they only lose their "charms" (temporary boost items), they always keep their weapons, skills, levels,...


- There are 2 main activities: `INVESTIGATE` and `RAID`:
- In `INVESTIGATE`:
	- Players will go through the city, looking for clues, talking to people, finding information about hidden cults.
- In `RAID`:
	- After player pieces together clues, they will know where a cult building is located. 	
	- Players will go into that building, clearing all enemies to get to the next floor.
	- After clearing a floor they will receive a buff (charm) to get stronger.
- Some enemies are tanky and may require long combos. When they goes down to 0 HP they will enter a `STAGGER` state and you have to land a `FINISHER` on them to kill them.

## Problems players have with other hack and slash games

### ⚠Problem 1: Combos are too hard to input, too long to remember

![donguri-devil-may-cry-v (1)](https://github.com/wentallout/cult-hunter/assets/76118931/a873ef9e-e62d-4213-aa5c-ff8bdf4b020c)

Humans can easily count 1,2,3,4 and tap the table using that rhythm. Now what happens when you count in your head and do 2 different things at the same time? You're adding load to your brain.

This is a known problems in DMC5. Here's why:
- You have to hold too many buttons to do one simple thing. 
EX: Stinger is a sword thrust move you can do by `HOLD SHIFT` + `W` + `LEFT MOUSE`. These **holding inputs** will really add up and mess with your head when you have to do long combos.
- Most of these inputs were designed for controllers, not keyboards and mouse.
- You drop your combo immediately if you don't press the correct follow-up attack

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

Most combos are just:
- `LEFT MOUSE` x2, x3, x4, x5 then end the combo with `Q` or `E`
- If you go for Long Combo: your `ENDER` at the end will do the maximum damage, stun most enemies in front of you. However you leave yourself vulnerable during your attack animation. You should save this for when the enemy is `STUNNED` or you're not outnumbered.
- If you go for Short Combo: your `ENDER` does less damage but you leave more slot in the 6 slot system -> You can do `FILLER` to debuff or `DASH` away for safety.

### Finisher

What happens when players got low health? Do they restart? Let me Introduce the `FINISHER`
- `FINISHER`: some enemies don't die but enter a `STAGGER STATE` that allows you do a special finishing move on them to replenish your HP. Make sure when we design we always add a few strong enemies that can be `STAGGER` to help players survive.

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

Cult Hunter is designed for PC. I want a simplified, more accessible combat system. No more training to get a long combo. I want players to focus on precise movements instead of remembering inputs.

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

- `FORBIDDEN MAGIC` (`ACTIVE`): people with natural magic are already extinct. Most super powers in the game world comes from people making contracts with interdimensional entitie (offering something you have for power).
  
- `CURSED TATTOO` (`PASSIVE`): characters have these tattoos that modify their stats (ex: Ava has the `Equalizer` tattoo that matches her stat with the strongest person in her POV)


![image](https://github.com/wentallout/cult-hunter/assets/76118931/4cd09dd3-6480-4cad-bbe3-01657721afdd)

- `AURA` (`PASSIVE`): characters can emit a circular aura around them. Different people have different rules inside their aura. If enemies step inside that aura range then they have to obey a certain `RULE`. (ex: Nameless' aura makes people unable to use magic)


![image](https://github.com/wentallout/cult-hunter/assets/76118931/115ccad2-a6ea-4420-b2e6-26dcab14b4ae)

