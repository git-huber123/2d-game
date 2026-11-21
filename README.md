# 2D Game

### Time spent:

At the moment, ~8.2 hours. I'm including this so it's possible for reviewers to match up my time spent with my commits.

| Commit        | Time      | Time since last commit  |
| ------------- | --------- | ----------------------- |
| Line of sight | 8.2 hours | N/A, first time tracked |

### Playing the game:

##### Controls:

WASD to move around, and spacebar to place/break blocks.

##### Mechanics:

Enemies will find the best path towards you if they can see you, but if they can't see you, they'll move randomly. For each 1 move that you make,
the enemies will also move once. Their line-of-sight lines are drawn on screen.

##### Tips and tricks:

If an enemy is within 2 blocks of you (gap of 1 block between you and the enemy), you're fried, since you won't be able to turn around and place a block
without the enemy then moving right next to you. Further from them than that, and you're fine, just find a boulder, dig into it, and block off the entrance,
and boom! Perfect hideout!

### Links:

- https://git-huber123.itch.io/2d-game - itch.io page
- https://git-huber123.github.io/2d-game/ - github page
- https://github.com/git-huber123/2d-game - github repo

### Features:

- You can move around
- There are walls
- There are enemies
- You can place and break blocks
- Enemies have intelligent pathfinding, instead of just randomly walking towards you like my other games, and also have line-of-sight movement
- There's an inventory system

### Known bugs:

##### Not fixed:

- None at the moment!

##### Fixed:

- The enemies can get stuck in each other, even though I have a checkEnemyCollisions() function.

### Work in progress:

- None as of now.

### Planned:

- Visual indication for your health
- Enemy line-of-sight attacking
- Player being able to attack the enemies
- Crafting!

### AI Usage Disclamer:

I used AI to help me with some debugging, as well as helping me with some of the more complex helper functions, such as the hash function (uses some weird bitwise math),
hslToRgb() (no clue how to do that), and some of the other ones too. However, most of the game is written by me. The functions written by AI are wrapped in a comment
block noting that they are AI-written.
