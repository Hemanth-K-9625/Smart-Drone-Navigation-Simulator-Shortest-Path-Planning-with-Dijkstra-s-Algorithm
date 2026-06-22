# 🚁 Drone Path Simulation using Dijkstra's Algorithm

A simple Python project that simulates drone navigation by finding the shortest path between locations using **Dijkstra's Algorithm**. The project visualizes the graph and highlights the optimal route.

## 📌 Features

- Implements Dijkstra's shortest path algorithm
- Models locations as a weighted graph
- Finds the optimal route between source and destination nodes
- Visualizes the graph and shortest path using Matplotlib
- Beginner-friendly implementation

## 🛠️ Technologies Used

- Python
- NetworkX
- Matplotlib
- Heapq

## 📂 Project Structure

```
drone-path-simulation/
│
├── drone_path_simulation.ipynb
├── README.md
|-- images
└── requirements.txt
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Hemanth-K-9625/Smart-Drone-Navigation-Simulator-Shortest-Path-Planning-with-Dijkstra-s-Algorithm.git
cd Smart-Drone-Navigation-Simulator-Shortest-Path-Planning-with-Dijkstra-s-Algorithm
```

Install the dependencies:

```bash
pip install networkx matplotlib
```

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook drone_path_simulation.ipynb
```

Run all cells to generate the graph and visualize the shortest path.

## 📖 How It Works

1. Locations are represented as nodes in a graph.
2. Connections between locations are assigned weights.
3. Dijkstra's Algorithm computes the shortest path.
4. NetworkX and Matplotlib visualize the graph and the optimal route.

## 📸 Output

The program displays:

- A graph of connected locations.
- The shortest path from the source to the destination.
- Visualization of the selected route.

## 🎯 Learning Objectives

- Graph data structures
- Dijkstra's Algorithm
- Priority queues using Heapq
- Graph visualization with NetworkX
- Pathfinding applications in autonomous systems

## 📜 License

This project is open-source and available under the MIT License.
