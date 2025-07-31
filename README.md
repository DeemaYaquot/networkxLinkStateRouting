# Link-State Routing Simulator (Python + NetworkX)

This project simulates the **Link-State Routing Algorithm** using Python and the [NetworkX](https://networkx.org/) package.

## 📌 Features

- Parse a custom text input defining nodes and directed edges.
- Visualize the original network topology.
- Calculate and display the **forwarding table** for each node (using Dijkstra’s algorithm).

---

## 📁 Input Format

The input is read from a `.txt` file.

- The **first line** contains two integers: number of nodes `n` and number of edges `m`.
- Each of the next `m` lines contains: `source_node, destination_node, weight`


---

## 📈 Outputs

1. **Forwarding Table** for each node.
2. **Graph Visualization** of the topology.

---

## 🔧 Technologies Used

- Python 3
- NetworkX
- Matplotlib
