# realm
I'm slowly compiling notes for a pen and paper adventure.

## resources
### Some sites and things to keep an eye on
- http://goblinpunch.blogspot.com/
- http://monstermanualsewnfrompants.blogspot.com/
- http://monstermanualsewnfrompants.blogspot.com
- http://zigguratofunknowing.blogspot.com/
- http://www.necropraxis.com/
- http://udan-adan.blogspot.com/
- https://coinsandscrolls.blogspot.com/
- http://falsemachine.blogspot.com
- https://talesofthegrotesqueanddungeonesque.blogspot.com/
- http://falsemachine.blogspot.com/2018/07/the-wodlands-8-necropolis-of-glass.html

## structure
Ok, so the idea is to build a framework around which a game can be made. Stories and specific adventures will fall out while building the world, and as characters are developed and explored.

The basic structure is simple: A macguffin is broken into _n_ pieces. When assembled, the path to the final conflict is revealed. 

To support this, the world is also divided into _n_ major regions, each of which protects (or at least contains) one piece.

The adventurers stumble across the first piece, with a clue how to find another one. These first two pieces act as the core introduction to the game and world.

The second one contains clues to several more pieces, and if need be those contain more clues. This branch allows the players to assume responsibility over the direction of the game.

Each major region has at least one major enemy archetype. Typical archetypes, which may or may not be appropriate for the game setting, include:
- pirates/thieves guild/mafia/organized crime
- zombies/golems/robots/brainless automatons
- ninjas/bedouin/stealth assasin types
- vulcans/high elves/ents/ long-lived low-emotion logic types
- goblins/kobolds/grubby garbage dweller types
- faeries/naiads/norwegian elves/fantasy tree dwelling vicious giggle sexy things
- etc

Each "chapter" consists of entry to the region, discovery of the archetype, exploration and search for the amulet, zero or more mini boss battle(s), full boss battle, a nice reward, and a path or more information about one of the other pieces

## implementation

There are 5 major regions on a landmass that is maybe diamond-y with 5 major regions.

```
                                          3  Kobolds
                                                ^
                                             .    m m   .
                                        .         M  m       .
                              .                MMM mm         .
                        .                      m    MMMMM m          .
                    .                      mmMMMMM m                          .
2 Pirates <                           [6 dragon]                   > 4 ??
                 .              *                 M MMM                   .
                    .    [1 zom] *             mm                  .
                          .       *      *  **   * *              .
                                   .    *  *    ****      .
                                           .     ***    .
                                                 v
                                                 5 ??
```

### West
First region, contains the first two pieces of the amulet. Standard midwest country like place, gentle hills, grassy fields, forest that gets thicker and thicker as it moves south east.

Small zombie encounter (very first), cabin in the woods. Encounter occurs as players are travelling along a cart path, see some zombies, follow it to cabin and find a clue to the next piece of the amulet which is on the coast on the western edge of the island protected (guarded or whatever) by pirates led by a female captain. In theory can be negotiated with. Clues found to pieces present in the north or south, allowing a branch.

### South
Forest extends from the western area, heavily forested, possibly tropical. 

archetype to be determined. faeries and naiads, or rangers, or ninjas or something like that.

Clue to eastern piece present.

### North
Mountains. Kobolds or goblins or some other dirty scroungy type group. Maybe some dwarves? They may have a route to the mainland to be explored after the final confrontation.

### East

Desert? Unsure. Probably not a lot of opportunity for desert on a smallish island.

Unsure of archetype.

### Central

Dragon lair. Probably very high mountain type place? Some epic journey to get there. Requires each piece of the amulet to be able to cross some threshold, or all pieces to be assembled to open the door to get in, something like that. 

Perhaps entry at the bottom-ish area of the mountain then climb up to peak from the inside for the final confrontation somehow.

Amulet somehow allows group to defeat dragon, which then provides something to lead to the next major realm, somehow. Maybe. Or someone hears about the great victory and seeks them or something. 

## encounters
Since I'm specifically targeting a novice dnd group with some preconceptions about gameplay, early encounters will be pretty combat-heavy and skill-based encounters will be introduced gradually over time. 

The two are not mutually exclusive, interest skill-based attempts during combat will be heavily rewarded

### combat
Each realm has a basic progression of enemy npcs. Difficulty of encounters should float somewhere between 95 - 80% likelihood of party victory for early encounters and scale up to maximum difficulty of 60% likelihood of party victory.

- trash mobs. low-level (relative to the party) cannon fodder that provide mostly trash/sell-to-vendor type rewards maybe a chance here and there at something good.
- seargent-level, same basic type as the canon-fodder but slightly higher level and slightly better trash
- lieutenant level - roughly equivalent to one PC in terms of level, skill, etc. Named character, interesting-ish items, some back story and canned dialogue. Can be used as mini-boss, hold key information, etc.
- boss - single entity that is roughly as powerful as the party when encountered one-on-one. Reduced difficulty if any trash or seargent mobs are present. Occasionally can be boss + lieutenant. 

Some of the above changes depending on the archetype of the enemy. Zombie-type creatures are low skill, low hp, high numbers encounters so they can be overwhelming in number, as compared to say pirates where there are many but only so many people fit on a boat or something like ninjas that are few in number, but extremely difficult to hit.

### skill-based
#### environmental
- climbing, 
- trap detection/removal, 
- finding the lever to open a door, 
- do the thing to get the item to remove the barrier to move to the next section of the dungeon, 
- search to find the hidden treasure, those sorts of challenges must exist. 

Some basic early ones that focus on relatively predictable skills (someone to lift something heavy, someone to jump a gap, someone to disarm a trap) will be present in the first two major sections but some amount of time to understand the strenghts and weaknesses of the group and emphasize or exploit them will need to be made. 

The dragon encounter/zone will need to have some complicated environmental encounters that build on and combine those encountered earlier in the game.

#### conversational
- characters that can be talked out of combat, 
- characters that can provide hints to future puzzles, 
- fill in details of overarching plot, 
- opportunities with merchants for negotiation or theft
