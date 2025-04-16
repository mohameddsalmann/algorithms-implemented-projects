
# Algorithm Visualizer Suite

## Overview

The **Algorithm Visualizer Suite** is an interactive Python toolkit that lets users visualize the inner workings of two powerful algorithms:

1. **k-Shortest Paths Visualizer** (Tkinter GUI)
2. **Manacher’s Algorithm Visualizer** (Jupyter Widget App)

This suite is perfect for students, educators, and enthusiasts wanting to deeply understand graph traversal and string pattern detection.

---

## 1️⃣ k-Shortest Paths Visualizer

### 🔍 Description
A desktop application built with `Tkinter`, `NetworkX`, and `Matplotlib`, allowing users to visually explore the **k-shortest simple paths** between two nodes in a directed weighted graph.

### 🖥️ Features

- Predefined sample graph of 13 nodes and 19 edges.
- Choose source, target, and `k` value.
- Visualizes the full graph and lists all k-shortest paths.
- Simple and clean interface.

### ▶️ Usage

```bash
python k_shortest_paths_gui.py
```

### 🧠 Algorithm

Uses `networkx.shortest_simple_paths` with edge weights to generate k paths using Yen’s algorithm logic.

---

## 2️⃣ Manacher’s Algorithm Visualizer

### 🔍 Description
A browser-based Jupyter app that steps through **Manacher’s Algorithm** for finding the **longest palindromic substring** in a string — with optional step-by-step visualization.

### 🧩 Features

- Interactive widgets powered by `ipywidgets`
- See each expansion step and palindrome radius
- Full string transformation (`^#a#b#c#$`) included
- Visualization with highlighting of current center and radius

### ▶️ Usage

1. Run inside a Jupyter notebook:
```python
# Paste the code into a notebook cell and run
```

2. Enter your string in the input box.

3. Use:
   - `Find Palindrome` to compute and visualize result.
   - `Next Step` to step through algorithm.
   - `Show All Steps` to print all computation steps.

### 🧠 Algorithm

Implements **Manacher’s Algorithm** with full transformation and center expansion logic for O(n) palindrome detection.

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install networkx matplotlib ipywidgets
```

> For Jupyter Notebook users:
```bash
jupyter nbextension enable --py widgetsnbextension --sys-prefix
```

---

## 🛠️ File Structure

```
AlgorithmVisualizerSuite/
├── k_shortest_paths_gui.py
├── manacher_algorithm_notebook.ipynb
├── README.md
```

---

## 📸 Screenshots

*(You can add screenshots of the GUI and Jupyter steps here)*

---

## 📄 License

MIT License.  
Feel free to modify and use in educational or personal projects.
