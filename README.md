# 🔍 BFS vs DFS Graph Search System

### SLE-3: Architectural Design – Full C4 Model

**Course:** 02AML204 – Introduction to Artificial Intelligence  
**PRN:** 25UAM042 | **Name:** Koustubh Sampat Chorade | **Division:** A

---

## 📌 About

The **BFS vs DFS Graph Search System** is an AI-based search system that finds a target node in a graph/tree using:

- 🔵 **BFS – Breadth-First Search**
- 🟢 **DFS – Depth-First Search**

The system also compares their **execution time** and **nodes expanded**.

---

## 🎯 Objectives

- Implement BFS and DFS.
- Compare their search performance.
- Track nodes expanded and execution time.
- Visualize the search tree.
- Design the system using the **C4 Model**.

---

## 🛠️ Technologies

| Tool | Purpose |
|---|---|
| 🐍 Python | Implementation |
| 🔎 BFS / DFS | Search algorithms |
| 🌐 NetworkX | Tree visualization |
| 📊 Matplotlib | Graph display |
| ⚡ py-spy | Performance profiling |
| 🏗️ C4 Model | Architecture design |

---

## 🏗️ C4 Architecture

The project is designed using four C4 levels:

```text
Level 1 → Context
     ↓
Level 2 → Containers
     ↓
Level 3 → Components
     ↓
Level 4 → Code / Functions
```

### Main Modules

```text
User
  ↓
Input & Configuration
  ↓
Graph Generator
  ↓
Search Engine
  ├── BFS → Queue
  └── DFS → Stack
  ↓
Profiling & Output
  ↓
Search Result
```

---

## 🔑 Main Functions

```python
create_tree()
display_tree()
bfs()
dfs()
profile_bfs()
profile_dfs()
visualize_graph()
main()
```

---

## 📊 Performance Analysis

The system measures:

- ⏱️ **Execution Time**
- 🔢 **Nodes Expanded**
- 📈 **Profiling using py-spy**

These metrics are used to compare BFS and DFS performance.

---

## ▶️ Run the Project

Install required libraries:

```bash
pip install networkx matplotlib py-spy
```

Run:

```bash
python bfs_vs_dfs.py
```

---

## 🤖 AI Contribution

**AI Tools:** ChatGPT, Claude

AI was used to assist with:

- Understanding the C4 Model
- Structuring the architecture
- Designing diagrams
- Understanding BFS/DFS concepts
- Explaining `py-spy` profiling
- Improving project documentation

**My Contribution:** I developed the BFS/DFS implementation, decided the system structure, performed profiling, reviewed the architecture, and verified the final results.

📄 **Detailed Log:** [`AI_CONTRIBUTION_LOG.md`](AI_CONTRIBUTION_LOG.md)

---

## 📚 Learning Outcomes

- Understanding BFS and DFS.
- Using queues and stacks for search.
- Performance profiling with `py-spy`.
- Graph visualization with NetworkX and Matplotlib.
- Applying the C4 Model to software architecture.

---
