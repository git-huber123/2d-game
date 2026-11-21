# 2D Game

## Time spent:

At the moment, ~8.2 hours. I'm including this so it's possible for reviewers to match up my time spent with my commits.

| Commit          | Time       | Time since last commit  | Notes                                                                  |
| --------------- | ---------- | ----------------------- | ---------------------------------------------------------------------- |
| Explosions      | 11.1 hours | 0.6 hours               | This'll be incorporated into a weapon or powerup later                 |
| Enemy Attacking | 10.5 hours | 0.9 hours               | This'll also be turned into a weapon, instead of being point-and-click |
| Powerup System  | 9.6 hours  | 1.1 hours               | Pretty cool, step away from a pure sandbox game                        |
| Scoring         | 8.5 hours  | 0.3 hours               | Simple yet effective                                                   |
| Line of sight   | 8.2 hours  | N/A, first time tracked | Proud of this one!                                                     |

## Playing the game:

##### Controls:

WASD to move around, and spacebar to place/break blocks.

##### Mechanics:

Enemies will find the best path towards you if they can see you, but if they can't see you, they'll move randomly. For each 1 move that you make,
the enemies will also move once. Their line-of-sight lines are drawn on screen.

Your score is based on how many milliseconds you survive, 100 points for 1 second. If you stop moving for too long, or try to camp in a box, then
time doesn't count, and it's pretty accurate.

You can get powerups! See the powerups section for more info.

You can also attack enemies - your mouse position is highlighted via a blue line and a box is drawn on the selected cell. If you click,
you can attack an enemy, but the enemies will also take a turn and move, even if you miss. It's kinda fun to just hold down the mouse
and run, beaming enemies while you're at it!

##### Tips and tricks:

If an enemy is within 2 blocks of you (gap of 1 block between you and the enemy), you're fried, since you won't be able to turn around and place a block
without the enemy then moving right next to you. Further from them than that, and you're fine, just find a boulder, dig into it, and block off the entrance,
and boom! Perfect hideout!

## Powerups:

##### Box:

Creates a 5x5 box around you, with a 3x3 space of air inside. Any enemies located in or on the box are relocated.

##### Invisiblity:

Makes the enemies just wander randomly for the next 10 seconds, they can't see you.

##### Teleport:

Checks a bunch of spots, and teleports you to the one with the furthest distance from any enemies.

## Links:

- https://git-huber123.itch.io/2d-game - itch.io page
- https://git-huber123.github.io/2d-game/ - github page
- https://github.com/git-huber123/2d-game - github repo

## Features:

- You can move around
- There are walls
- There are enemies
- You can place and break blocks
- Enemies have intelligent pathfinding, instead of just randomly walking towards you like my other games, and also have line-of-sight movement
- There's an inventory system
- Time-based scoring, with common score-farming methods patched
- Powerups!

## Known bugs:

- None at the moment!

## Work in progress:

- Improvements on the powerup system.

## Planned:

- Visual indication for your health
- Player being able to attack the enemies
- Crafting!

## AI Usage Disclamer:

I used AI to help me with some debugging, as well as helping me with some of the more complex helper functions, such as the hash function (uses some weird bitwise math),
hslToRgb() (no clue how to do that), and some of the other ones too. However, most of the game is written by me. The functions written by AI are wrapped in a comment
block noting that they are AI-written.
