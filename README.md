# 🏰 Treasure Hunt: Dungeon Escape

### Programming Fundamentals – CCA Project (CT-175)

**Treasure Hunt: Dungeon Escape** is a console-based maze adventure game developed using the **C programming language** as part of the Programming Fundamentals course.

In this game, players explore mysterious dungeons, collect hidden treasures, avoid dangerous traps, and find the exit to complete each level. Players must use their moves wisely, manage their limited lives, and overcome challenges to achieve the highest possible score.

---

## 👥 Group Members

| Name | Roll Number |
|---|---|
| Fatima Shad | CT-26201 |
| Ayesha Noor | CT-26208 |
| Adan Shahid | CT-26209 |
| Hiba | CT-26243 |

---

## 🎮 Game Features

Our game includes the following features:

### 1. Difficulty Levels
- **Easy:** Suitable for beginners.
- **Medium:** Offers moderate challenges.
- **Hard:** Provides a more challenging experience.

### 2. Game Modes
- **Normal Mode:** Standard dungeon exploration.
- **Torch Mode:** Limited visibility with double score rewards.

### 3. Maze Exploration
Explore the dungeon using keyboard controls and discover hidden treasures.

### 4. Treasure Collection
Find and collect all hidden treasures before reaching the exit.

### 5. Trap System
Avoid dangerous traps to protect your lives.

### 6. Limited Lives
Each player starts with three lives.

### 7. Exit Challenge
The exit can only be reached after collecting all required treasures.

### 8. Hint System
Get hints about the nearest treasure. However, each hint costs three moves.

### 9. Scoring System
Scores are calculated according to the player's performance.

### 10. Player Ranking
Players receive ranks based on their final scores.

### 11. Leaderboard
View previously saved player scores and rankings.

### 12. Player Search
Search for a player's saved record by entering their name.

### 13. File Handling
Player scores and records are saved and loaded using `scores.txt`.

### 14. Quit Option
Players can quit the game whenever they want.

---

## 🕹️ Game Controls

| Key | Action |
|---|---|
| W | Move Up |
| A | Move Left |
| S | Move Down |
| D | Move Right |
| H | Get Hint |
| Q | Quit Game |

---

## 🚀 How to Compile and Run

Follow these steps to run the game on your computer.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Ayeshanoor608/Treasure-Hunt-Dungeon-Escape.git
cd Treasure-Hunt-Dungeon-Escape
```

### Step 2: Open the Project Folder

```bash
cd Treasure-Hunt-Dungeon-Escape
```

### Step 3: Compile the Program

Make sure GCC is installed, then execute:

```bash
gcc main.c -o project
```

### Step 4: Run the Game

**For Windows:**

```bash
project.exe
```

**For Linux/macOS:**

```bash
./project
```

---

## 💻 Sample Input

1
1
1
XYZ
W
A
S
D
H
Q
```

## 🖥️ Sample Output

```text
====================================
          TREASURE HUNT
          DUNGEON ESCAPE
====================================

MAIN MENU

1. Play
2. Leaderboard
3. Instructions
4. Exit

Enter choice: 1

SELECT LEVEL

1. Easy
2. Medium
3. Hard
4. Back

Enter choice: 1

SELECT MODE

1. Normal
2. Torch Mode

Enter choice: 1

LEVEL 1

Controls:

W = Move Up
A = Move Left
S = Move Down
D = Move Right
H = Get Hint
Q = Quit

Enter move: W
Enter move: A
Enter move: S
Enter move: D
Enter move: H

HINT: The nearest treasure is 4 steps away.

Enter move: Q

Enter your name: Javeria

GAME SUMMARY

Treasures: 0
Moves: 5
Score: 0

MAIN MENU

1. Play
2. Leaderboard
3. Instructions
4. Exit

Enter choice: 4

Goodbye, adventurer!
```

---

## 📚 Programming Fundamentals Concepts Used

This project demonstrates the practical implementation of the following C programming concepts:

- **Variables and Data Types:** Storing player information, scores, lives, and game data.
- **Conditional Statements:** Making decisions using `if`, `else`, and `switch`.
- **Loops:** Repeating game operations and controlling gameplay.
- **Functions:** Dividing the program into smaller, reusable modules.
- **Arrays:** Managing maze layouts and game elements.
- **Strings:** Handling player names and other text data.
- **File Handling:** Saving and retrieving player records using files.

---

## 📁 Project Folder Structure

```text
Treasure-Hunt-Dungeon-Escape/
│
├── Source_Code/
│   └── main.c
│
├── Screenshots/
│   └── game_output.png
│
├── scores.txt
│
├── Project_Report(5).pdf
│
└── README.md
```

---

## 🎯 Project Objectives

- Apply fundamental C programming concepts in a practical project.
- Develop logical thinking and problem-solving skills.
- Understand how arrays, functions, loops, and conditions work together.
- Implement file handling to store player records.
- Create an interactive and enjoyable console-based game.

---

## 🏆 Conclusion

**Treasure Hunt: Dungeon Escape** combines programming logic with an exciting adventure experience. Through this project, we have applied the fundamental concepts of C programming to develop an interactive game featuring maze exploration, treasure collection, traps, hints, scoring, and a leaderboard.

This project represents our practical understanding of Programming Fundamentals and our teamwork in developing a creative software application.

---

### ⭐ Thank You for Exploring Our Project!

**Developed with ❤️ using C Programming Language.**
