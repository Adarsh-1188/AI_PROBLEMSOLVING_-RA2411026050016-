#  Smart Navigation System (BFS & DFS)

## Overview

This project implements a simple **Smart Navigation System** using two fundamental graph traversal algorithms:

* **Breadth-First Search (BFS)**
* **Depth-First Search (DFS)**

It finds a path between two nodes in a graph based on user input.

---

##  Problem Statement

Given a graph, the goal is to **find a path between a start node and a goal node** using:

* BFS (shortest path in terms of edges)
* DFS (depth-based traversal)

---

##  Algorithms Used

### Breadth-First Search (BFS)

* Explores nodes level by level
* Guarantees the **shortest path** in an unweighted graph

###  Depth-First Search (DFS)

* Explores as deep as possible before backtracking
* Does **not guarantee shortest path**, but is memory efficient

---

##  Project Structure

```
 smart-navigation-system
│── sys.py        # Main Python script
│── README.md      # Project documentation
```

---

##  How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/smart-navigation-system.git
```

2. Navigate to the project folder:

```
cd smart-navigation-system
```

3. Run the program:

```
python main.py
```

4. Enter inputs when prompted:

```
Enter start node: A
Enter goal node: E
```

---

##  Sample Output

```
BFS Path: ['A', 'B', 'D', 'E']
DFS Path: ['A', 'C', 'D', 'E']
```

Or visually:

```
BFS Path: A → B → D → E
DFS Path: A → C → D → E
```

---

##  Features

* User-friendly input
* Handles invalid node entries
* Supports both BFS and DFS traversal
* Clean and simple implementation

---

##  Requirements

* Python 3.x
  (No external libraries required)

---

##  Future Improvements

* Graph input from user
* Weighted graph support (Dijkstra’s Algorithm)
* GUI visualization
* Real-world map integration

---

##  Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## License

This project is open-source and available under the MIT License.
