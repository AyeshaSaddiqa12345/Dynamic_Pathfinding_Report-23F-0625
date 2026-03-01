# Dynamic Pathfinding Agent

## 📌 Description

This project implements and compares two search algorithms:

- A\* Search
- Greedy Best-First Search (GBFS)

The system operates on a grid environment with:

- Static obstacles
- Dynamic obstacles
- Real-time visualization using Pygame
- Performance metrics display

---

## 🛠 Requirements

Python 3.8+

Install dependencies:

```bash
pip install pygame
```

---

## ▶ How to Run

Clone repository:

```bash
git clone <your-repository-link>
cd <project-folder>
```

Run:

```bash
python main.py
```

---

## 🎮 Controls

- Mouse Click → Add/Remove obstacles
- Click "Algorithm" → Toggle A\* / GBFS
- Click "Heuristic" → Toggle Manhattan / Euclidean
- Press SPACE → Start simulation
- Close window → Exit

---

## 📊 Metrics

- Nodes Visited
- Path Cost
- Execution Time (ms)

---

## 🧪 Test Scenarios

Best Case:

- No obstacles
- Straight path

Worst Case:

- Maze-like obstacles
- Heavy exploration required
