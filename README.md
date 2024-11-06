# Flying Monster
A fun, interactive game where you guide a monster through obstacles! Inspired by the classic Flappy Bird, Flying Monster provides a new twist and a unique challenge.

## About the Project

**Flying Monster** is a game developed in **Java** where players control a monster character, navigating it through pipes and avoiding obstacles. This project is designed to enhance understanding of game development concepts, including animation, collision detection, and event handling in Java.

Below is the simulation for the Flying Monster game:

<img src="assets/game.gif" alt="Flying Monster Game GIF" width="270" height="450">

## Features

- **Smooth animations** and responsive controls.
- **Randomly generated obstacles** for unique gameplay each time.
- **Score tracking** to challenge yourself and improve.
- **Fun graphics and sound effects** for an immersive experience.

## Gameplay

The objective is simple: guide the monster through the gaps in the pipes without hitting them. The game ends when the monster collides with a pipe or the ground. Try to survive as long as possible and score points by passing through the pipes!

## Technologies Used

```text
- Programming Language: Java
- Libraries: 
    - javax.swing (for GUI)
    - java.awt (for handling events, graphics, and animations)
- Development Environment: Visual Studio Code (VSCode)
```
## Code Overview
```text
1. Main Game Loop:
   - Controls the flow of the game, including updates to the monster's position, checking for collisions, and redrawing the screen.

2. Player Character (Monster):
   - The monster is controlled using the keyboard (up/down or spacebar) to avoid obstacles.

3. Obstacles (Pipes):
   - Randomly generated pipes that move across the screen. The player must navigate through gaps in the pipes.

4. Collision Detection:
   - The game checks if the monster collides with a pipe or the ground, which ends the game.

5. Score System:
   - The game tracks the player's score based on the number of pipes successfully passed.
```
