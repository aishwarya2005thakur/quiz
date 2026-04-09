# 🧠 C Quiz Game 

A simple command-line based quiz game written in **C**, developed as part of my first semester coursework. This project tests basic programming concepts like structures, arrays, loops, and user input handling.

---

## 🚀 Features

* Multiple-choice quiz system (A, B, C, D)
* 12 pre-defined questions
* Immediate feedback after each answer
* Final score + percentage calculation
* Case-insensitive input handling (`toupper()` used)

---

## 🛠️ Tech Stack

* Language: **C**
* Compiler: GCC
* IDE: VS Code

---

## 📂 Project Structure

```
quiz.c       // Main source code
quiz.exe     // Compiled executable (generated)
```

---

## ⚙️ How to Run

### 1. Compile the program

```bash
gcc quiz.c -o quiz
```

### 2. Run the executable

```bash
./quiz
```

(On Windows)

```bash
quiz.exe
```

---

## 🧩 Concepts Used

This project helped reinforce:

* **Structures (`struct`)**
* **Arrays of structures**
* **String handling (`strcpy`)**
* **Loops (`for`)**
* **Conditional statements (`if-else`)**
* **Character functions (`toupper`)**
* **User input (`scanf`)**

---

## 📸 Sample Output

```
Question 1: who is the founder of c?

A) add one to a number
B) add two to a number
C) subtract one from a number
D) subtract two from a number

Enter answer: A

Correct answer!
```

---

## ⚠️ Limitations

* Questions are hardcoded (no dynamic input)
* No file handling (questions not loaded from file)
* Basic UI (terminal only)
* No input validation for invalid characters

---

## 🔮 Future Improvements

If I were to upgrade this (and you honestly should at some point):

* Load questions from a **file (CSV/JSON)**
* Add **timer-based questions**
* Improve UI using **colors or formatting**
* Add **score leaderboard**
* Convert to a **GUI or web-based quiz app**

---

## 💡 What I Learned

This project was my starting point in programming and helped me understand:

* How to structure data using structs
* How to manage multiple inputs efficiently
* How to build a complete working program from scratch

* turn this into a **file-based quiz system**
* or upgrade it into a **DSA-level project (with dynamic questions, scoring system, etc.)**
