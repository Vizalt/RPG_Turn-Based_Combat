# RPG Turn-Based Combat
## Table of Content
- Introduction
- Differents kinds of turn-based combat system
- Pros and cons of different approaches
  -  Pros
  -  Cons
- Turn vs Real Time
- Implementation requirements
- What makes a RPG Combat good or bad?
- Summary
- Documentation

## Introduction
This work aims to analyse and display the different types of RPG turn-based combat.It will be analysed how it has evolved and the progress that different games have contributed to the genre.

## Differents kinds of turn-based combat system
### Classic Turn-Based Game
Each player can take as much time as they wish to decide and execute an action. Until the player decides, absolutely nothing in the game changes.

![Pokemon](https://user-images.githubusercontent.com/70697960/155571529-78006905-948d-4632-8309-20bc0511a25c.gif)

Example: [_Pokemon Emerald_](https://bulbapedia.bulbagarden.net/wiki/Pok%C3%A9mon_Emerald_Version) (2004)

## Timed Turns
Unlike the Classic, in this type of combat, each player has a limited period of time in which to perform an action. In this way limiting the game time and forcing the player to decide on an option.

![UltimaIIIExodus](https://user-images.githubusercontent.com/70697960/155572973-db3a05cb-9e8a-43a6-8de2-9b7d0ef53eda.png)

Example: [_Ultima III:Exodus_](https://wiki.ultimacodex.com/wiki/Ultima_III:_Exodus) (1983)

## Active Time Battles
The turns played are determined by counters that reset each time an action is performed.

![FinalFantasyIV](https://user-images.githubusercontent.com/70697960/155573658-72734b0c-a9d5-4988-972f-e7276857a2b7.gif)

Example: [_Final Fantasy_](https://en.wikipedia.org/wiki/Final_Fantasy_IV) (1991)

## Simultaneously executed Turns
It divides the turns into two distinct phases: decision and execution. During the decision phase, each player plans and determines the actions of his units.  Once in the execution phase, the decisions made by all players are put into action automatically and at the same time.

![LaserSquadNemesis](https://user-images.githubusercontent.com/70697960/155611665-ce9a5179-5e70-41b7-b0e5-c0b1249d733c.jpg)

Example: [_Laser Squad Nemesis_](https://www.old-games.com/download/9175/laser-squad-nemesis) (2002)

## Clock-Based Turns
All the unit's actions are linked directly to the game's clock. The turns begin and end depending on the duration of each action, giving a highly variable sequence of turns in no particular order.

![TyphoonOfSteel](https://user-images.githubusercontent.com/70697960/155611181-606f4c1d-2a56-423e-aa4e-994a96e5a72c.png)

Example:[_Typhoon of Steel_](https://en.wikipedia.org/wiki/Typhoon_of_Steel_(video_game)) (1988)

## Unit Initiative
The sequence of turns in some games is determined by the initiative statistic of each unit, regardless of the side to which it belongs.

![FinalFantasyTactics](https://user-images.githubusercontent.com/70697960/155609920-5dd09e10-d3e1-481c-91b5-59fef4542dda.jpg)

Example: [_Final Fantasy Tactics_](https://finalfantasy.fandom.com/wiki/Final_Fantasy_Tactics) (1997)
## Outside Turn
It allows players to perform an action outside their turn by interrupting their opponents' turns.

![X-COM](https://user-images.githubusercontent.com/70697960/155574420-f5a47170-38c6-4946-907c-b4fb84f8b54f.jpg)

Example: [_X-COM_](https://xcom.com/es-ES/) (1993-1998)
## Special turns
This is when in combat it is necessary to follow different rules, for example not being allowed to use X attack or to use the same action twice in a row.

![KingArthur](https://user-images.githubusercontent.com/70697960/155574594-2c6d1164-8436-4d6d-bdef-631d8f39a5fb.jpg)

Example: [_King Arthur_](https://en.wikipedia.org/wiki/King_Arthur:_The_Role-Playing_Wargame) (2009)
## Special phases
It's when a game is divided in differents phases. For example, players orders all units their movement in one phase and then, they attack in a later phase.

Example:  [_Battle Isle_](https://www.youtube.com/watch?v=73N6s0V_3lU)(1991-2001)

## Pros and Cons
### Pros
- It has a different turn-based game where players can choose a variety of games depending on their preference. For example, some people prefer playing classic turn-based games because they don't like playing in real time because they stress easily.
- The time you have in each turn allows you to make more tactical choices.
### Cons
- In terms of realism, the combat system can be considered unrealistic because of their mechanics. For example, in real life, people do not have specific time to attack or defend in a fight.
- It can be considered less immersive than other types of systems.
- In some cases, the mechanics and rules might be challenging for players to learn and understant.

## Turn vs Real Time
There is debate as to which system is better between real-time and turn-based video games. The arguments in support of real-time systems solve some of the problems caused by turn-based systems.
To begin with, the lack of realism. The immersion that real-time based systems bring to the players makes them feel the actions and events that take place in the game as well as taking them into the [Magic Circle](https://en.wikipedia.org/wiki/Magic_circle_(virtual_worlds)).

Secondly, real-time games are more suitable for people who prefer multiplayer. Several players tend to prefer playing real-time games since they enjoy playing with friends, and also, waiting for your round while other players take their turn can be an exhausting task. 

## Implementation requirements
How to create a turn-based combat? These are the questions you need to ask when creating a combat.
1. First of all, **have a clear idea of your game**. Think about why combat is required in your game and how you think you want to implement it. Will the combat use specific mechanics? What arena are you will be fighting in?
2. You need to **decide which system** will fit best or if you're going to try to combine any of them.
3. Then **develop a loop** for the combat. How is the combat going to start, what happens when you decide the actions, how is it going finish and finally how will the player get out of it when it is over.
4. **Design the AI**. What enemies will be more smart, what abilities should they have and how much life will they have?
5. **Design the UI**. What you want to show on the screen and why?

## What makes a RPG combat good or bad?

These are the main factors for which a turn-based RPG can be considered good or bad.
### Good
- Balanced: As the game progresses, it should remain a challenge for the player but not too difficult so that he/she does not get frustrated.
- Design: It must have an interface that does not cause rejection by the player.
- Mechanics: It should have mechanics that innovate and stand out so as not to look like just another typical game.
- Choices: Decisions made by players should have an effect on the game.

### Bad

- Boring: The game should seem dynamic and interesting, it should not contain long animations and enemies must not always use the same actions.
- Variety: It has been proven that no matter how much a game has impressive mechanics, players will always choose the most efficient mechanic for them, so if one option, such as an attack or a combo of abilities is effective, they will always use that one and not anything else, no matter how amazing it is. Therefore the strategies that the player needs to follow for each fight should change in each one of them so that they do not become monotonous.

## Documentation

**Relevant links**

V.S. (2020, 23 julio). [The Evolution of Unique Turn-based Battle Systems Guide!](https://www.reddit.com/r/JRPG/comments/hwdk8p/the_evolution_of_unique_turnbased_battle_systems/) Reddit. 

Rowett, S. (2021, 17 julio). [What Makes A GOOD Turn-Based RPG System?](https://www.cbr.com/jrpgs-turn-based-systems/) CBR. 

D.J.T. (2018, 19 diciembre). [What makes a good combat system?](https://www.reddit.com/r/RPGdesign/comments/a7nz7i/what_makes_a_good_combat_system/) Reddit.
## About me

This page has been written by [Marina Albalà](https://github.com/Vizalt) as part of a research project for the subjet Project II in Videogame Design and Development at CITM.
