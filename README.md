# Graph Algorithm Visualizer

A simple Python-based visualizer for BFS (Breadth-First Search) and DFS (Depth-First Search) algorithms.

## Features

- 📊 Visual representation of graph traversal
- 🎨 Color-coded nodes (red = current, green = visited, blue = unvisited)
- 📝 Step-by-step traversal output
- 🔧 Support for custom and sample graphs
- 🚀 Easy to use and understand

## Requirements

Install the required packages:

```bash
pip install matplotlib networkx
```

## How to Run

```bash
python graph_visualizer.py
```

## Usage

1. **Choose Graph Type:**
   - Use sample graph (pre-defined)
   - Create your own custom graph

2. **Select Algorithm:**
   - BFS (Breadth-First Search)
   - DFS (Depth-First Search)
   - Both algorithms

3. **Watch the Visualization:**
   - Red nodes show the current node being explored
   - Green nodes show already visited nodes
   - Blue nodes show unvisited nodes

## How It Works

### BFS (Breadth-First Search)
- Explores nodes level by level
- Uses a queue (FIFO - First In First Out)
- Good for finding shortest paths

### DFS (Depth-First Search)
- Explores as deep as possible before backtracking
- Uses recursion (stack-based)
- Good for exploring all paths

## Example

Sample graph structure:
```
    0
   / \
  1   2
 / \ / \
3  4 5  6
 \ /
  7
```

## Project Structure

```
algorithm visualiser/
├── graph_visualizer.py  # Main program
└── README.md           # Documentation
```

## Author

Created for VIT SEM-2 CSA-2001 Fundamentals in AI and ML

## License

Free to use for educational purposes
