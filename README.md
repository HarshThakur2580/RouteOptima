# 🚀 RouteOptima — Advanced Food Delivery Path Optimization

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Dijkstra's-6366f1?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-06b6d4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Styling-TailwindCSS-38bdf8?style=for-the-badge&logo=tailwindcss" />
  <img src="https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge" />
</p>

> **RouteOptima** is an enterprise-grade, browser-based path optimization tool built for food delivery and logistics operations. It leverages **Dijkstra's shortest path algorithm** to calculate and visually demonstrate the most efficient delivery routes through a weighted graph network.

---

## 📸 Preview

<p align="center">
  <em>Open <code>RouteOptima/index.html</code> in your browser to see the live demo.</em>
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗺️ **Interactive Graph Visualization** | SVG-based delivery network graph with animated path highlighting |
| ⚡ **Real-time Path Optimization** | Instantly computes shortest paths using Dijkstra's algorithm |
| 📊 **Detailed Metrics Dashboard** | Shows total cost, number of nodes visited, and estimated delivery time |
| 🔍 **Step-by-step Algorithm Trace** | Educational view of each iteration of Dijkstra's algorithm |
| 📱 **Fully Responsive** | Works seamlessly on desktop, tablet, and mobile devices |
| 🎨 **Dark-Themed Premium UI** | Glassmorphism design built with TailwindCSS and custom CSS |

---

## 🧠 How It Works

RouteOptima models a delivery infrastructure as a **weighted directed graph**:

```
Nodes  → Locations (Restaurant, Kitchen, Distribution Centers, Hubs, Customers)
Edges  → Routes between locations with cost/distance weights
```

**The 3-step process:**

1. **Network Modeling** — Transform your delivery infrastructure into a weighted graph with 11 nodes and 15 weighted edges.
2. **Algorithm Processing** — Dijkstra's algorithm computes the shortest path from a selected source to a destination, considering all edge weights.
3. **Optimal Path Output** — The system highlights the optimal route on the graph and displays full metrics.

### 📍 Network Nodes

| Node | Type | Description |
|------|------|-------------|
| R | 🍽️ Restaurant | Origin/main restaurant |
| K | 🏭 Kitchen | Preparation facility |
| D1, D2 | 📦 Distribution | Distribution centers |
| H1, H2 | 🏢 Hub | Intermediate hubs |
| C1–C5 | 👤 Customer | Delivery destinations |

---

## 🛠️ Tech Stack

- **HTML5** — Page structure and semantic markup
- **CSS3** — Custom dark theme, glassmorphism effects, animations
- **JavaScript (Vanilla)** — Dijkstra's algorithm implementation + SVG graph rendering
- **TailwindCSS** (CDN) — Utility-first responsive styling
- **Font Awesome** — Icons throughout the UI

---

## 🚀 Getting Started

No installation or build step required! This is a pure front-end project.

```bash
# 1. Clone the repository
git clone https://github.com/7085ashishraj/RouteOptima.git

# 2. Navigate into the project folder
cd RouteOptima

# 3. Open in browser
open RouteOptima/index.html
# or simply double-click index.html in your file explorer
```

---

## 📂 Project Structure

```
RouteOptima/
├── RouteOptima/
│   └── index.html       # Main application (self-contained single-page app)
└── README.md
```

---

## 📡 Algorithm — Dijkstra's Shortest Path

The core of RouteOptima is a JavaScript implementation of **Dijkstra's greedy algorithm**:

- **Time Complexity:** O((V + E) log V) — where V = nodes, E = edges
- **Space Complexity:** O(V)
- **Graph Type:** Weighted, undirected graph with 11 vertices and 15 edges
- **Priority Queue:** Min-heap for efficient distance extraction

**Sample Edge Weights:**
```
R → D1 : 2    (shortest direct path from restaurant)
D2 → H2: 1    (lowest cost leg in the network)
H2 → C4: 2    (fast customer delivery)
```

---

## 👥 Team — Quantam Code

| Name | Role | Registration |
|------|------|-------------|
| **Ashish Raj** | Developer | 12314533 |
| **Himanshu Raj** | Developer | 12314450 |
| **Ashish Kumar** | Developer | 12315759 |

---

## 📬 Contact

📧 **ashishrajstm2003@gmail.com**

---

## 📄 License

This project was developed as part of Computer Science research to demonstrate practical applications of graph algorithms in real-world logistics challenges.

© 2025 RouteOptima — All rights reserved.
