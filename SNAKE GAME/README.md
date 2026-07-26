
#  Snake Game (C++)

A simple console-based **Snake Game** developed in **C++** using object-oriented programming concepts and Windows console functions. The player controls the snake using the arrow keys, collects fruits to increase the score, and avoids colliding with walls or its own tail.

---

##  Features

-  Classic Snake gameplay
-  Arrow key controls
-  Random fruit generation
-  Score tracking
-  Snake grows after eating fruits
-  Collision detection with walls and snake body
-  Press **X** anytime to exit the game

---

##  Technologies Used

- C++
- Windows Console
- `<iostream>`
- `<conio.h>`
- `<windows.h>`
- `<ctime>`

---

##  Controls

| Key | Action |
|-----|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |
| X | Exit Game |

---

##  Project Structure

```
SnakeGame/
│
├── SnakeGame.cpp
└── README.md
```

---

##  How to Run

### Using Visual Studio

1. Clone this repository.

```bash
git clone https://github.com/Ashish-Kumar9140/SnakeGame.git
```

2. Open the project in Visual Studio.

3. Build and Run the project.

---

### Using g++

```bash
g++ SnakeGame.cpp -o SnakeGame
SnakeGame.exe
```

> **Note:** This project uses `conio.h` and `windows.h`, so it runs only on Windows.

---

##  Gameplay

- The snake starts from the center of the board.
- Eat the `*` (fruit) to increase your score.
- Every fruit increases the snake's length.
- Hitting a wall ends the game.
- Hitting your own tail also ends the game.

---

##  Preview

```
######################
#                    #
#       O            #
#           *        #
#                    #
######################

Score : 20
```

---

##  Future Improvements

- Wrap-around walls
- High score system
- Multiple difficulty levels
- Pause/Resume feature
- Colored snake and fruits
- Sound effects
- Better random fruit spawning
- Dynamic game speed
- Menu screen
- Cross-platform support

---

##  Concepts Used

- Functions
- Arrays
- Loops
- Enums
- Random Number Generation
- Collision Detection
- Game Loop
- Keyboard Input Handling

---

##  Author

**Ashish Prajapati**

* GitHub: https://github.com/Ashish-Kumar9140
* LinkedIn: www.linkedin.com/in/ashish-prajapati-aaa9ba32a

If you like this project, don't forget to ⭐ the repository!

---

##  License

This project is open source and available under the **MIT License**.
