# IntelliMaze AI

A cyberpunk-inspired AI pathfinding visualizer built using Python and Arcade.
IntelliMaze AI demonstrates how different pathfinding algorithms behave inside dynamically generated weighted mazes using real-time visualization and traversal animation.

---

# Features

- Real-time pathfinding visualization
- Procedural maze generation
- Weighted node traversal
- BFS Visualization
- DFS Visualization
- Dijkstra Algorithm
- A* Algorithm
- Intelligent AUTO Mode
- Cyberpunk / TRON-inspired UI
- Real-time statistics panel
- Executable desktop version included

## Dynamic Maze Regeneration

The Reset button procedurally generates an entirely new maze every time it is pressed.

Each reset creates:

* New wall layouts
* New weighted node placements
* New traversal patterns
* New optimization challenges

This ensures:

* Infinite replayability
* Dynamic algorithm behavior
* Unique traversal visualization every execution

No two maze generations are guaranteed to be identical.

---

# Algorithms Implemented

## Breadth-First Search (BFS)
- Explores nodes level-by-level
- Guarantees shortest path in unweighted environments
- High node exploration count

## Depth-First Search (DFS)
- Explores deeply into one branch before backtracking
- Lower memory usage
- Does not guarantee shortest path

## Dijkstra Algorithm
- Weighted graph traversal algorithm
- Finds minimum traversal cost
- Optimizes weighted nodes

## A* Algorithm
- Heuristic-based optimization algorithm
- Uses Manhattan Distance heuristic
- Faster and more intelligent traversal

## AUTO Mode
- Automatically selects the most efficient algorithm
- Analyzes maze complexity and weighted distribution

---

# Technologies Used

- Python
- Arcade Library
- Graph Theory
- Procedural Generation
- Real-Time Rendering
- Event-Driven Programming
- Object-Oriented Programming

---

# Project Structure

```plaintext
IntelliMazeAI/
│
├── algorithms/
├── maze/
├── ui/
├── dist/
│
├── main.py
├── requirements.txt
```

---

# Screenshots

## A* Algorithm

<img width="1749" height="978" alt="Screenshot 2026-05-27 173425" src="https://github.com/user-attachments/assets/884e80f4-2014-45c1-a2b3-98187f765e35" />

---

## BFS Algorithm

<img width="1752" height="979" alt="Screenshot 2026-05-27 173514" src="https://github.com/user-attachments/assets/9b30f858-1a65-47fa-901f-15d6014e2308" />

---

## DFS Algorithm

<img width="1750" height="979" alt="Screenshot 2026-05-27 173601" src="https://github.com/user-attachments/assets/39635ee5-958b-47bd-ba04-fe40a641a0d4" />

---

## Dijkstra Algorithm

<img width="1749" height="979" alt="Screenshot 2026-05-27 173702" src="https://github.com/user-attachments/assets/12a6dc88-3adb-4ab0-b0ec-6dba10736270" />

---

## AUTO Mode

<img width="1749" height="980" alt="Screenshot 2026-05-27 173750" src="https://github.com/user-attachments/assets/aa0742dc-2b51-4ab9-abfc-e46eb1ac1dd6" />

---

# How to Run

## Method 1 — Executable Version

Open:

```plaintext
dist/IntelliMazeAI.exe
```

No Python installation required.

---

## Method 2 — Run Source Code

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

---

# Visualization Details

- Cyan Path → Final shortest path
- Blue Nodes → Visited traversal nodes
- Yellow Nodes → Weighted traversal nodes
- White Node → Start point
- Orange Node → Destination point

---

# Educational Purpose

This project was developed to visually demonstrate:
- AI traversal behavior
- Graph traversal techniques
- Weighted path optimization
- Heuristic-based search systems
- Real-time algorithm visualization

---

# Future Improvements

- Difficulty modes
- Heatmap visualization
- Dynamic obstacles
- Player-controlled maze mode
- Multiplayer race mode
- Machine learning based AUTO mode

---

# Author

Developed as an AI Pathfinding Visualization Mini Project using Python and Arcade.
