# Unity Challenges
A 4-hour challenge to solve 3 problems using Unity.
https://akaffenberger.github.io/challenge-unity-problems/

### Problem 1

Have a spotlight follow a ball with a smooth animation.

### Problem 2

Implement an emitter utilizing object pooling. Implement various configurable emitter settings.

### Problem 3

Have a ghost chase the player in a Pacman-like game.
- I opted to build two behaviors (Blinky & Clyde) based off of the original [Pacman](https://pacman.holenet.info/). However, I was not able to complete the path finding algorithm in time (LRTA*), so a simpler solution was used. It simply looks at the Manhattan distance and uses the next available space where there is no obstacle and Manhattan distance decreases, falling back to the first available empty space. It is possible for the ghosts to get stuck with this solution.
