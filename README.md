# Flappy Bird Game in Java (Java Swing)

## Project Overview

This project is a desktop-based clone of the classic Flappy Bird game developed using Java Swing. It simulates real-time gameplay mechanics where the player controls a bird navigating through procedurally generated pipes using keyboard input. The project demonstrates core game development concepts such as rendering, collision detection, game loops, and event handling in Java.

---

## Key Features

* Realistic bird physics with gravity and jump mechanics
* Procedurally generated pipes with random vertical gaps
* Real-time scoring system
* Game over detection and restart functionality
* Custom background and character assets
* Smooth real-time rendering using Java Swing

---

## Technologies Used

* Java
* Java Swing
* Object-Oriented Programming
* Event handling and graphics rendering

---

## How to Run

### Prerequisites

* Java JDK 8 or higher
* Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) or terminal

### Steps

1. Clone or download the repository.
2. Ensure all image assets are placed in the `/resources/` folder and referenced using `getResource()`.
3. Compile and run the project:

```bash
javac App.java FlappyBird.java
java App
```

Make sure the resources folder is correctly added to the classpath when using an IDE.

---

## Controls

* Spacebar – Jump / Start game / Restart after game over
* Up Arrow – Move bird upward
* Down Arrow – Move bird downward

---

## Game Logic Summary

* The bird is continuously affected by gravity.
* A jump provides upward velocity.
* Pipes are generated every 1.5 seconds and move left across the screen.
* The game ends if the bird collides with a pipe or goes out of bounds.
* Each successfully passed pipe contributes to the score.

---

## Applications

* Desktop game development demos
* Object-oriented programming practice
* Real-time simulation projects
* Java graphics and event-handling demonstrations

---

## Conclusion

This project demonstrates the implementation of a complete 2D game using Java Swing. It highlights real-time rendering, physics simulation, procedural obstacle generation, and interactive user input handling.

---

## Future Enhancements

* Add background music and sound effects
* Implement high score tracking
* Improve animations and visual effects
* Migrate to JavaFX or LibGDX
* Add mobile or touch-based controls

---
