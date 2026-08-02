# 🧩 Android Sudoku Application

An Android application developed using **Kotlin** that provides a complete Sudoku experience, including puzzle generation, gameplay, automatic solving, custom puzzle solving, and persistent storage of solved games. The application combines an intuitive user interface with efficient solving algorithms to deliver an engaging and educational experience.

---

## 📌 Features

- 🎮 Interactive Sudoku gameplay
- 🧩 Random Sudoku puzzle generation
- 🤖 Automatic Sudoku solver using a backtracking algorithm
- ✍️ Custom puzzle input and solving
- ✔️ Input validation and error detection
- 🔄 Reset and restart puzzle functionality
- 📱 Responsive and user-friendly Android interface

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **IDE:** Android Studio
- **UI:** Android XML Layouts
- **Architecture:** Activity-based Android Application
- **Version Control:** Git

---

## 📂 Project Structure

```
SudokuSolver/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
│
├── gradle/
├── build.gradle
├── settings.gradle
└── README.md
```

---

## ⚙️ Working Principle

The application consists of four primary modules:

### 1. Puzzle Generation
- Generates valid Sudoku puzzles.
- Creates playable boards while maintaining Sudoku constraints.

### 2. Sudoku Solver
- Uses a recursive **Backtracking Algorithm**.
- Efficiently searches for valid solutions while satisfying Sudoku rules.

### 3. Gameplay Module
- Allows users to fill cells manually.
- Validates user inputs.
- Highlights incorrect entries.
- Detects puzzle completion.

---

## 🧠 Algorithm

The Sudoku solving engine is based on the classic **Backtracking Algorithm**.

### Steps

1. Locate an empty cell.
2. Try numbers 1–9.
3. Check if the number satisfies Sudoku constraints:
   - Row validation
   - Column validation
   - 3×3 sub-grid validation
4. If valid:
   - Place the number.
   - Continue recursively.
5. If no valid number exists:
   - Backtrack.
   - Try the next possible value.
6. Continue until the puzzle is solved.

### Time Complexity

Worst Case:

```
O(9^(n²))
```

Although the theoretical complexity is high, practical Sudoku puzzles are solved efficiently due to extensive pruning during the search process.

---

## 🎯 Learning Outcomes

This project demonstrates practical experience in:

- Android application development
- Kotlin programming
- SQLite database integration
- Algorithm implementation
- Recursive backtracking
- Object-Oriented Programming
- UI/UX design for mobile applications

---

## 🔮 Future Improvements

- Dark mode
- Timer and scoring system
- Undo/Redo functionality
- Pencil marks (candidate notes)
- Sudoku statistics dashboard
- Achievement and progress tracking
- Cloud synchronization
- Local database integration (SQLite/Room) to save unfinished games, completed puzzles, player statistics, and game history
- User authentication and profile management
- Daily Sudoku challenges
- Online leaderboard and competitive mode
- MVVM architecture with Jetpack components
- Performance optimizations and improved UI animations

---

## 👨‍💻 Author

**Sumit Chatterjee**
