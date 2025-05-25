# Introduction-to-Python(Greedy Algorithm)
# 🗺️ Shortest Path Planning with Dijkstra Algorithm

This project implements the **Dijkstra algorithm** to calculate the shortest travel time between cities in a transportation network. It simulates real-world travel routing and supports interactive and test-based queries.

## 📌 Project Overview

- ✅ Built a graph of 19 cities using an adjacency matrix.
- ✅ Implemented Dijkstra algorithm to compute the shortest path.
- ✅ Designed user input mode and sample test cases.
- ✅ Evaluated performance on both small and large networks.
- ✅ Proposed a multi-factor decision-making extension model.

---

## 🧠 Algorithm Logic

1. Initialize distances to ∞ (except start node = 0)
2. Select the nearest unvisited node.
3. Update its neighbors' distances and predecessors.
4. Repeat until all nodes are visited or target is reached.

The algorithm supports both **fixed matrix traversal** and **user-defined queries**.

---

## 🧪 Sample Input & Output

### 🔹 Input
A 19x19 **adjacency matrix** of travel times, representing city-to-city connections.

### 🔹 Output
The **shortest travel time** and the **optimal path** between two cities.

### ✅ Example

- **From Tromsø to Stockholm**  
  ➤ `Tromsø → Oulu → Stockholm`  
  ⏱️ Travel time: 4 hours

- **From Murmansk to Arkhangelsk**  
  ➤ `Murmansk → Arkhangelsk`  
  ⏱️ Travel time: 2 hours

---

## 🧾 Code Structure

| File | Description |
|------|-------------|
| `dijkstra.py` / `.ipynb` | Main implementation of Dijkstra algorithm |
| `city_matrix.csv` | Travel time matrix (19 cities) |
| `user_input_mode()` | Function for manual queries |
| `sample_tests()` | Function for small network test cases |

---

## 🚀 Features

- 📍 Works on both small and large city networks
- ⌨️ Supports user input for start/end cities
- 🔁 Reusable logic for graph-based path planning
- 📊 Outputs shortest path and time
- 🔧 Easy to adapt for other cost metrics

---

## ⚠️ Limitations

- Assumes fixed travel times (no real-time delays)
- Does not consider cost, carbon footprint, or group size
- Not ideal for transport modes like air travel that skip intermediate nodes

---

## 🛠️ Future Improvements

- Integrate **multi-objective logic** (e.g., cost, carbon emissions)
- Add **transport mode selector** (e.g., train vs plane)
- Use **real-time data feeds** to simulate delays
- Expand to weighted multi-modal networks

---

## 📚 Example Use Cases

- 🚆 Train or bus route planners
- 🗺️ Campus or city path guidance systems
- 🎮 In-game AI movement logic
- 🔍 Education & teaching shortest path algorithms

---

## 👨‍💻 Author

**TIANHAO CHEN**  
University ID: `35621168`  
Module: *Introduction to Python - Coursework 2*

---

## 📎 License

This project is for educational use only. For commercial use, please contact the author.

