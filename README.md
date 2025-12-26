# 🐍 Snake Game with BFS

This project is an implementation of the classic **Snake Game** enhanced with an **AI agent using Breadth-First Search (BFS)** for pathfinding.
Instead of manual control, the snake automatically finds the shortest path to the food while avoiding collisions with walls and its own body.

The project is implemented as a **Jupyter Notebook** for better visualization and step-by-step understanding of the algorithm.

---

## 🚀 Features

* Classic Snake Game mechanics
* AI-controlled snake using **Breadth-First Search (BFS)**
* Shortest-path calculation to reach food
* Collision avoidance (walls & snake body)
* Grid-based environment
* Easy-to-follow implementation inside a Jupyter Notebook

---

## 🧠 Algorithm Used

### Breadth-First Search (BFS)

* BFS is used to explore the grid level by level
* Guarantees the **shortest path** to the food if one exists
* State space includes:

  * Snake head position
  * Obstacles (walls & snake body)

This makes BFS a good baseline algorithm for understanding **AI pathfinding in games**.

---

## ⚙️ Requirements

Make sure you have the following installed:

* Python 3.8+
* Jupyter Notebook
* Required Python libraries (commonly used):

  * `numpy`
  * `pygame` (if used for rendering)
  * `collections`

You can install missing dependencies with:

```bash
pip install numpy pygame
```

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:

   ```bash
   cd your-repo-name
   ```
3. Open the notebook:

   ```bash
   jupyter notebook snake_game_bfs.ipynb
   ```
4. Run all cells to start the game and observe the BFS-based snake behavior.

---

## 📈 Possible Improvements

* Replace BFS with more advanced algorithms (A*, Dijkstra)
* Add heuristics to improve performance on larger grids
* Visualize the BFS search process step-by-step
* Introduce reinforcement learning for comparison
* Improve UI and animations

---

## 🎓 Educational Purpose

This project is ideal for:

* Learning **pathfinding algorithms**
* Understanding **AI decision-making in games**
* Practicing **Python & algorithmic thinking**
* Demonstrating BFS in a visual and interactive way

---

## 📜 License

This project is open-source and available under the **MIT License**.

---
