# Video-Game-by-Unreal-Engine

:blush: :smiley: :relaxed: :laughing: :smile:
## Project Description
This project contains 4 simple video game implementations by Unreal Engine 4.22 Gameplay framwork and C++.
- Triple X(Warm-up)
- Bulls and Cows Game(Warm-up)
- Escape(For real)
- Battle Tank(For real)

I built the 3D user interface in Unreal Engine software(it provides starter content pack) and generated the project framework from software **automatically**.

:warning: :warning: :warning:

**I didn't write all the things by myself :)** I wrote the game logic and implemented the specific game with the existing game component/actor template and environment.
(See the source files for each game)

:warning: :warning: :warning:

There many [unreal engine](https://docs.unrealengine.com/en-US/Programming/Introduction/index.html) special data structures and types were utilized in the projects, which are totally different from general C++ library and focus on the game.

It is painful for me to design a 3D game since I feel sick whenever I played a video game.
:dizzy_face: :dizzy_face: :dizzy_face:

### Bulls and Cows Game
This is the word version of game.

- A person (Host) thinks of any isogram word, and gives out the number of letters in the word.
- Other players (Guessers) try to figure that word by guessing isogram words containing the same number of letters.
- Host responds with the number of Cows & Bulls for each guessed word. As with the digit version, "Cow" means a letter in the wrong position, while "Bull" means a letter in the right position.


### Escape Game
A 3D secret room for the escape game. 

Game starts at a locked room and players need to use environmental clues such
as light and sound to determine what to do next.

Using Blueprint to open the door gradually rather than 90 degree directly.
 
Solution: the left corner of room is a pressure pad to open the door.

![Image of Escape Room](https://github.com/JadeWang96/Video-Game-by-Unreal-Engine/blob/master/Building_Escape/Display.png)

### Battle Tank
The players control a tank to beat other tanks in this world.

Boring, but that's it.

![Image of Tank World](https://github.com/JadeWang96/Video-Game-by-Unreal-Engine/blob/master/BattleTank/Display.png)

## Requirement
- Epic Game
- Unreal Engine 4.2+ (Recommended 4.22 (I encountered some problems when used 4.24))
- C++11
- Blueprint

## Run
```
Run *.uproject 
```

## Acknowledgements
:snowman: Boring Winter Break :) Do this for fun.

All credits go to GameDev.tv Instructors

