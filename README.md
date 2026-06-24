# ♟️ Cyrus AI (کوروش AI)

**Cyrus AI** is an experimental Iranian UCI chess engine focused on artificial intelligence, search algorithms, and computer chess research.

> **Cyrus AI is a chess engine, not a chess GUI.**
>
> Applications such as Arena and PyChess only display the board and pieces. The actual thinking, analysis, and move selection are performed by the engine.

---

## What is Cyrus AI?

Cyrus AI is a long-term research project aiming to build a competitive Iranian chess engine and provide a platform for experimenting with:

* Artificial Intelligence (AI)
* Search Algorithms
* Position Evaluation Techniques
* Move Ordering Heuristics
* Performance Optimization
* Future Machine Learning Integration
* Computer Chess Research

---

## Current Features

* UCI Compatible
* Alpha-Beta Search
* Iterative Deepening
* Transposition Table
* Move Ordering
* Quiescence Search
* Checkmate and Draw Detection
* Performance Statistics and Benchmarking

---

## Project Status

⚠️ **Experimental / Research Project**

The initial prototype has already shown promising results and, in one of the tests, managed to defeat **Stockfish 14 running with limited strength settings**.

This result should not be interpreted as superiority over Stockfish. Rather, it demonstrates that the current research direction and architecture of the engine are encouraging and worth pursuing.

---

## Vision

Long-term objectives:

* Build a competitive Iranian chess engine
* Participate in computer chess competitions
* Explore novel AI and search techniques
* Serve as a research platform for game AI
* Contribute to computer chess research and engineering

---

# Playing with PyChess

## Step 1 – Install PyChess

Download and install PyChess:

👉 https://pychess.github.io/download/

---

## Step 2 – Download Cyrus AI

Download the latest executable from the Releases page.
**https://github.com/jazavaja/CyrusEngine/releases/download/V1.0.3/cyrus.exe**

---

## Step 3 – Add Cyrus AI to PyChess

1. Open **PyChess**
2. Go to:

```text
Edit → Preferences → Engines
```

3. Click **Add**
4. Select:

```text
cyrus.exe
```

(or `cyrus` on Linux)

PyChess should automatically detect Cyrus AI as a **UCI Chess Engine**.

Save the configuration.

---

## Step 4 – Play Against Cyrus AI

1. Open:

```text
Game → New Game
```

2. Select:

```text
Play against Engine
```

3. Choose **Cyrus AI**
4. Select your preferred color and time control
5. Press **Start Game**

Enjoy playing against Cyrus AI.

---

## Contributing

Ideas, bug reports, testing results, and contributions are welcome.

---

## Support the Project

Cyrus AI is an independent research project.

If you are interested in:

* Artificial Intelligence
* Computer Chess
* Search Algorithms
* Supporting scientific and technological projects

your feedback, suggestions, sharing, and support are greatly appreciated.

---

**Author:** Javad
**Language:** Rust 🦀
**Protocol:** UCI
**Status:** Active Development 🚧
