# cult-hunter
Khoa's work-in-progress game.

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
Japanese doomsday cult - Aum Shinrikyo: https://en.wikipedia.org/wiki/Aum_Shinrikyo

## Plot (WIP)
At the start of the game, Nameless, our ordinary sushi chef, sets out to take down a cult that killed his master years ago. At the end of the battle he found out that this is only a sub branch of the real cult. His search leads him to city where he declares war on all these evil cults.

Kimberly and Jigen are well known hitmen, are hired by the cult to kill Nameless but they chose to befriend him instead. Nameless got invited to the Zenith Hotel and he learned the rules of the underworld. As they dig deeper, they discover that the cult controls everything in the city. The Lawmaker, the secret leader of Zenith Hotel, he pretends to work for the cult but secretly helps the protagonists.

As the group continues to take down the cult's various groups, they eventually come face-to-face with the Cult Leader, the mastermind behind everything. With his charismatic leadership, the Cult Leader has managed to gain the support of the city's elite, making him a formidable, untouchable opponent.

Nameless and his allies must use all of their skills and resources to defeat the Cult Leader and his top subordinates, all while uncovering the truth about the cult's sinister plans for the city. As they fight their way through the Cult's hideouts, the group discovers that Nameless has a dark secret: he has been unknowingly hosting an eldritch god inside his mind, giving him immense power but also putting him at risk of losing control. The cult is aware that "entity" is a mythical god-eating monster and want to capture Nameless to kill it.

In the end, the fate of the city rests on the shoulders of Nameless and his allies as they face off against the Cult Leader and his minions in a final, epic battle. With their determination, wits and skills, they must stop the Cult's plan before it's too late and bring justice for those who have suffered.

## Basic Gameplay

- Cult Hunter is a stylish, hack n slash game with rogue-like features
- There are 2 main activities: `INVESTIGATE` and `RAID`
- In `INVESTIGATE`: Players will go through the city, looking for clues, talking to people, finding information about hidden cults.
- In `RAID`: Players will go into a big building (for example like: https://en.wikipedia.org/wiki/Church_of_Scientology), clearing all enemies to get to the next floor. After clearing a floor they will receive a buff (charm) to get stronger.
- Some enemies are tanky and may require long combos. They will enter a `STAGGER` stage and you have to land a `FINISHER` on them
- Roguelike: players receive temporary charms after they clear a stage/floor. These `CHARM` will disappear after the stage is over but they're very powerful and will help players survive the brutal difficulty.
- Loot: enemies will drop weapons that you can pickup and enhance/modify with runes
- Progression: If player dies, they only lose their "charms" (temporary boost items), they always keep their weapons, skills, levels,...

## Settings

| name          	| description                                                                                                                                                                                                     	                    |
|---------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Havenbrook City 	| The city which is the main location of the game. Peaceful outside but it's a very chaotic place, people live in fear, some are being scammed by sinister corporate , some are lured into these "clubs" that turns out to be doomsday cults. 	|
| Talon Street  	| It's a hidden part of the city protected by top-tier veil charms. It's well known for its high-end weapon and clothes shop. Zenith Hotel is the main location here. |
| Zenith Hotel    	| A safe haven for all Hitmen. Rules are strict: You cannot kill here. They have a membership card and unique currency which looks like casino chips |                  


## Characters

I try to keep a balance number of male and female.

### Trinity (Main Protagonists)

| name     	| gender 	| description                                                                                                                           	|
|----------	|--------	|---------------------------------------------------------------------------------------------------------------------------------------	|
| Nameless 	| ?   	        | mysterious main protag, sushi chef, he's may talks a lot when players want to be charismatic, he summons all sorts of weapons out of thin art, he throws knives and chop people up.	|
| Kimberly 	| female 	| 2nd protag, specialized in making magical bullets. She's a dual-wielding gunslinger, can sees through objects and shoot hiding enemies.                                        	|
| Jigen    	| male   	| 3rd protag, weapon collector, cool glasses dude who use katana, his slashes create waves and can recharge his waves by putting his sword back inside his katana sheath, he can also teleport to his thrown weapons     	|

### Skyline Club (friendly allies)
The Skyline racing club provides assassins with custom cars and gadgets. They hate the cult because one of their important member got seriously hurt by them. They are on the move constantly to both sabotage the cult and hide from them.

| name    | gender | description                                                                  |
|---------|--------|------------------------------------------------------------------------------|
| Tak     | Male   | hacker                                                          	          |
| Harper  | Female | car mechanic                                                                 |
| Eleanor | Female | battle racer, she modified her cars to have all sorts of weapons to fight the cult. |

### Zenith Hotel (neutral)
It's simple, you give them money, they kill for you, they don't pick sides. Zenith Hotel is neutral sanctuary for hitmen. Hitmen are people from all background, thousands of them live in the city, they usually hangout in Zenith Hotel and enjoy all the privilege: food, safety (like in John Wick).

| name           	| gender 	| description                                                                                                                                                             	|
|----------------	|--------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Eli (Lawmaker)   	| male   	| badass leader, use a cane-sword, makes all the rules for the assassins to follow, weakest but extremely intelligent, even the cults are afraid of him.                         	        |
| Raven (Accountant) 	| female 	| sniper, cold and ruthless, love cats.                                                                                                                  	|
| Ava (Spy)            	| female 	| a spy sent by Lawmaker to investigate the cult. She joined the cult and made her way up the ladder, secretly loves Nameless and give him hints to help him. 	|
| Naka (Doctor)         | male          | He will do his best to save your life as long as you're a member of the hotel.                                                                                                |
| Will (Hotel Manager)  | female        | a retired hitmen, she's very polite to everyone but don't fuck around in her hotel, rules are there for a reason.                                        |

### Shadow Dancer Clan (neutral)
An all female assassin clan. They're impressed after seeing Nameless fights and want him to join the clan. (Nameless's gender is kinda ambiguous due to not being 100% human)

### The Cult (Main Antagonists)

The cults are hidden in the city, they lure innocent people in and do horrible things (both violent and non-violent crime). Your main enemies in the game are cult members, the 12 Apostles and all the monsters they summon. 

There were 12 cults in total (1 main, 11 branches). One of them got wiped out by Nameless in the tutorial, this kickstarted the war.
- The Cult Leaders (Twelve Apostles): immortal, charismatic and powerful. They have crazy reality-bending powers. They manipulate and abuse people in the city for money/enjoyment. No one in the city knows who/where they are and what they look like so it forces the players to find clues to track them down.
	+ No.1: Elara (she thinks she predicts natural disaster but she is actually causing it)
	+ No.2: Malachi (controls blood, granting him enhanced strength and healing
	+ No.3: Luna (turn invisible and creates illusions, bright light nullifies her)
	+ No.4: Samson (he creates a mini Sun and burn everything in its path)
	+ No.5: Isolde (she can accelerate the growth and mutation of plants, even creating sentient plant guardians. However, her powers are weakened in barren or polluted environments.)
	+ No.6: Raziel (Raziel can manipulate and create gravitational fields, enabling him to levitate objects and create localized gravitational anomalies. However, overusing this power makes him susceptible to disorientation.)
	+ No.7: Victor (he can transmute matter, turning one substance into another, but he requires a sample of the desired material, and the process is time-consuming)
	+ No.8: Selene (she can enters and manipulate dreams)
	+ No.9: Maxwell (can create temporary breaches to other dimensions, summoning exotic creatures and objects. However, these rifts can be unpredictable and unstable)
	+ No.10: Ella (she plays music, the notes turn into flying blades, she dances with a sharp paper fan while attacking)
	+ No.11: Coin (absorb and redirect physical forces)
	+ No.12: Zeke (he's a horror painter... anything he draws come into life 😱)
  
- Corrupt Government Officials and Corporate: controlled by the cult, mostly do white collar crime
- Corrupt Cops: follow orders from the Government Officials, they take advantage of small businesses in the city to extort money.
- The Cult Members: weak minded people who got lured and controlled by the leaders to do unspeakable crimes


## Equipments

- Equipments in the game are just weapons since clothes are meant for fashion
- Normal weapon: guns, blades from the modern world
- Set weapon: the most powerful weapons in the game comes from one of the many sets. Each set is crafted made by one family.
	+ Demon Slayer Set: gives user new unique skills.
	+ Paladin Set: bless its owner with big stats and shield.
	+ Insect Set :usually weak but apply crazy debuff that stacks.
	+ ...etc
	
- Cursed Weapon: hard to use but powerful, has some small stat debuff which force players to build their character to compensate, there is a gruesome, disturbing origin behind these weapons.
- Accessories: Ring to modify attacks, Necklace to modify defense

## Character Stats

- `HP` bar: health bar, if it reaches 0 your run ends and you have to try the whole thing again (this game is rogue-like)
- `DODGE` bar (to replace SHIELD): character will automatically dodge when this bar isn't 0.
- `STRESS` bar: cult members can cast psychological attacks on player that cause debuff (slow, stun, inaccuracy, damage reduction) when it reach below 0.

 ### Unique Combat Mechanics
 
- `ENDER`: ender is a unique mechanic in Cult Hunter, after the end of a long combo, you can press `Q` or `E` to launch a devasting explosive attack. Some characters have AoE `ENDER`, some have single target `ENDER`, some even have unique `ENDER` mechanics (stacks, debuffs)
- `FINISHER`: certain enemies don't die until you do a special finishing move on them, complete this will replenish your HP.

Most complete combos are just:
- `LEFT MOUSE` x2, x3, x4, x5 then end the combo with an `ENDER` using `Q` or `E` 

## Power System

- `FORBIDDEN MAGIC`: people with natural magic are already extinct. So most super powers in the game world comes from people making contracts with interdimensional entities. You usually have to offer something precious.
- `CURSED TATTOO`: some characters have these tattoos that modify their stats (ex: Ava has the Equalizer tattoo that matches her stat with the strongest person in her POV)
- `AURA`: strong characters emit a circular aura around them. Different people have different rules inside their aura. If enemies step inside that aura range then they have to obey a certain `RULE`. (ex: Nameless' aura makes people unable to use magic)

## Style Switching

- One character can hold 2 fighting styles that they can switch to.
- For example: you can have one mode for crowd control and one mode for bossing.
- You can equip your styles in the menu.

## Controls

Cult Hunter is designed for PC. I want a simplified, more accessible combat system. No more training to get a long combo. I want players to focus on precise movements instead of remembering inputs.

- Move: `W,A,S,D`
- Jump: `SPACE`
- Crouch: `CTRL`

### Dash-related
- Dash: `SHIFT`, dash into an obstacle will make characters "parkour" through it
- Dash Attack: `SHIFT` then `LEFT MOUSE`
- Dash Jump: `SHIFT` then `SPACE`
- Dash Slide: `SHIFT` then `CTRL`
- Sprint: hold `SHIFT` to sprint, you can do `WALL RUNNING` if you run and touch a wall.

### Attack-related
- View: `MOUSE`
- Block: `RIGHT MOUSE`
- Attack : `LEFT MOUSE`
- Launcher: `SCROLL WHEEL UP`, launch enemies into the air
- Finsher: tap `SCROLL WHEEL` to do a fancy animation and execute an enemy
- Swap weapons: `TAB`
- Change style: `F`
- Pick/throw/kick: `G`, if your character can't pick something up, like a heavy table, they'll launch it into nearest enemies. If there's nothing to pickup, they'll kick enemies.
- Skills: `1`,`2`,`3`,`4`
- Rage: `Q`+`E` (still working on this)

### Other
- Taunt: `T`

## Gives players more choice, expand their creativity
 
`RANGE` matters:
- Characters do different attacks depend on the range and the angle between them and the enemies.
- `REACHING`: If your enemies are far away, your characters will automatically do long range attack to try to reach them
- `AIMING`: you do different attacks based on the body part you aim. If you aim at someone's legs, your characters will try to chop their legs.

`STEALTH` matters:
- You're always outnumbered by the cult, try to sneak through, disable alarms early.

`CHARISMA` matters:
- You can clear certain missions by picking the right dialogue instead of fighting.

`INVESTIGATION` matters: gathering information about cult leaders can help you prepare for them.
