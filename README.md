# Pathfinding Visualizer

> *An interactive web app that visualizes pathfinding algorithms in real time.*

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript) ![Tailwind](https://img.shields.io/badge/Tailwind-3-38BDF8?logo=tailwindcss) ![License](https://img.shields.io/badge/license-MIT-white) ![Status](https://img.shields.io/badge/status-in%20development-orange)

---

## 🔍 About

**Pathfinding Visualizer** is an interactive web app that brings pathfinding algorithms to life. Draw walls, place a start and end point, pick an algorithm, and watch it think in real time — step by step.

Built entirely from scratch with no algorithm libraries. Every line of A*, Dijkstra, BFS and DFS is hand-written in TypeScript.

---

## 🎮 Features

- **4 algorithms** — A*, Dijkstra, BFS and DFS
- **Draw walls** by clicking and dragging
- **Move start and end** nodes freely
- **Adjustable animation speed** — from slow motion to instant
- **Maze generator** — recursive backtracking algorithm
- **Stats panel** — path length, nodes visited, time taken
- **Side by side comparison** — run two algorithms simultaneously

---

## 🧠 Algorithms

| Algorithm | Guarantees shortest path | Weighted | Notes |
|-----------|--------------------------|----------|-------|
| **A\*** | ✅ Yes | ✅ Yes | Uses heuristic to guide search — fastest in practice |
| **Dijkstra** | ✅ Yes | ✅ Yes | Explores all directions equally — guaranteed optimal |
| **BFS** | ✅ Yes (unweighted) | ❌ No | Best for unweighted grids |
| **DFS** | ❌ No | ❌ No | Does not guarantee shortest path — shown for contrast |

---

## 🛠️ Built With

- **React 18** — UI and component state
- **TypeScript** — type-safe algorithm implementation
- **Tailwind CSS** — styling
- **Vite** — build tool
- **Vercel** — deployment

All algorithms implemented from scratch — no pathfinding libraries used.

---

## 🚀 Live Demo

▶️ [Try it live](#) *(coming soon)*

---

## 📁 Project Structure

```
src/
├── algorithms/
│   ├── aStar.ts
│   ├── dijkstra.ts
│   ├── bfs.ts
│   ├── dfs.ts
│   └── mazeGenerator.ts
├── components/
│   ├── Grid/
│   │   ├── Grid.tsx
│   │   └── Node.tsx
│   ├── Toolbar/
│   │   └── Toolbar.tsx
│   └── StatsPanel/
│       └── StatsPanel.tsx
├── types/
│   └── index.ts
├── hooks/
│   └── usePathfinding.ts
├── App.tsx
└── main.tsx
```

---

## 🗺️ Roadmap

- [x] Project setup — React + TypeScript + Tailwind
- [ ] Grid component with click and drag wall drawing
- [ ] BFS implementation and animation
- [ ] DFS implementation and animation
- [ ] Dijkstra implementation and animation
- [ ] A* implementation and animation
- [ ] Speed control
- [ ] Stats panel
- [ ] Maze generator
- [ ] Side by side comparison mode
- [ ] Deploy to Vercel

---

## 🏃 Run Locally

```bash
git clone https://github.com/tuniet/pathfinding-visualizer
cd pathfinding-visualizer
npm install
npm run dev
```

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Antonio Fernández Juan**
[GitHub](https://github.com/tuniet) · [LinkedIn](https://linkedin.com/in/tuniet) · [Portfolio](https://tuniet-portfolio.netlify.app)
