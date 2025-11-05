## 🧮 Real-World Problems Using Graph Algorithms

### 📘 Overview

This project demonstrates the **application of fundamental graph algorithms** to real-world problem scenarios such as:

* **Social Network Friend Suggestions**
* **Shortest Path Algorithms (Bellman-Ford & Dijkstra)**
* **Minimum Spanning Tree (Prim’s & Kruskal’s)**

It also includes **execution time profiling and visualization** for different graph sizes to show how algorithm performance scales with input size.

## 📊 Problem Summary Table

| **Problem**                 | **Graph Algorithm**        | **Time Complexity** | **Application Domain** | **Notes / Insights** |
|-----------------------------|----------------------------|---------------------|-------------------------|-----------------------|
| Social Network Suggestion   | BFS / DFS                  | O(V + E)            | Social Media            | Suggest mutual friends |
| Google Maps Routing         | Bellman-Ford               | O(V × E)            | Navigation              | Works with negative weights |
| Emergency Path Planning     | Dijkstra’s                 | O(E log V)          | Disaster Response       | Fastest path in positive-weighted map |
| Cable Installation          | MST (Prim’s / Kruskal’s)   | O(E log V)          | Infrastructure          | Minimum cable cost |

---
### ⚙️ Technologies & Libraries Used

- **Python 3.x**
- **NetworkX** – for graph generation and algorithms
- **Matplotlib** – for visualizing time complexity
- **Memory Profiler** – for measuring memory usage
- **Time** – for measuring execution performance

---

### 📂 Project Structure

```
real-world-problems-using-graph-algorithms-aaradhya/
│
├── graph_realworld.ipynb        # Main Jupyter Notebook
├── requirements.txt             # Required Python libraries
└── README.md                    # Project overview (this file)
```

---

### 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/real-world-problems-using-graph-algorithms-aaradhya.git
   cd real-world-problems-using-graph-algorithms-aaradhya
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**

   - Open `graph_realworld.ipynb` in **Jupyter Notebook** or **VS Code**.
   - Execute each cell step-by-step to view:

     - Friend suggestion results
     - Shortest path calculations
     - Minimum Spanning Tree costs
     - Performance and memory profiling
     - Time complexity visualizations

---

### 📊 Visualization Example

#### Execution Time vs Number of Nodes

Each algorithm’s efficiency is visualized with automatically generated random graphs:

- **Bellman-Ford Algorithm**
- **Dijkstra’s Algorithm**
- **Minimum Spanning Tree (Prim/Kruskal)**

```python
plt.plot(sizes, times)
plt.title("Execution Time vs Graph Size")
```

You’ll see separate and combined plots comparing how time increases with node count.

---

### 🧠 Key Learnings

- Understanding **graph representation and traversal** techniques
- Comparing **time complexity** between shortest-path algorithms
- Profiling and **visualizing algorithm performance**
- Interpreting **scalability** of graph algorithms in real data problems

---

### 📈 Future Enhancements

- Add **real-world datasets** (e.g., social networks, maps)
- Include **parallelized algorithms** for large-scale graphs
- Implement **interactive dashboard** (using Plotly or Streamlit)

---

### 👩‍💻 Author

**Aaradhya**
2301201029
📚 BCA (AI & Data Science)
Section A

---


