# Smart_Route_Planner

Our project, "Railway Route Optimization System," is a web-based tool designed to compute the most optimal train route between stations. Users input a start and destination station, and choose to optimize by distance, time, or cost. The system uses Dijkstra's algorithm to find the best path based on the selected criteria. All computations are done in-browser using JavaScript, with station and route data embedded directly in JS files. The application has a clean, form-based HTML interface that ensures smooth user interaction without the need for a backend or database.

---

## 📌 Project Overview

The **Railway Route Optimization System** is a lightweight, web-based tool designed to compute the most optimal train route between two stations. Users can choose to optimize routes based on **distance**, **travel time**, or **cost**, using **Dijkstra’s algorithm**. The application is entirely frontend-driven and runs in the browser — **no backend, no database**.

---

## 🎯 Features

- 🚉 Input start and destination stations using intuitive dropdowns.
- ⚙️ Select optimization criteria: shortest distance, lowest cost, or fastest time.
- 📍 Visualize the optimal path on an interactive map of India using Leaflet.js.
- 💡 View a **station code help list** for easy identification of stations.
- ⚡ Runs entirely in the browser — all logic implemented in JavaScript.

---

## 🧱 Project Architecture

### Frontend
- **HTML/CSS/JS** – Used for structure, styling, and all route computation logic.
- **Leaflet.js** – For rendering the train network and selected route on an interactive map.

### Data
- `stations.js` – Contains all station names and their corresponding codes.
- `graph_data.js` – Contains route connections and metadata (distance, time, cost) for each edge.
- `mapped_station_coordinates`-Contains all station names and their corresponding coordinates.

### Algorithm
- **Dijkstra’s Algorithm** implemented in JS for finding shortest paths based on selected criteria.

---

## 🛠️ Technologies Used

- **JavaScript** (for Dijkstra's algorithm, data handling)
- **HTML/CSS** (for UI)
- **Leaflet.js** (for map rendering)
- **Dataset**: [Indian Railways Dataset from Kaggle](https://www.kaggle.com/datasets/sripaadsrinivasan/indian-railways-dataset)

---







