# 🍕 Domino's Dehradun Smart Route Optimizer

A route optimization and visualization system developed for efficient Domino’s delivery routing in Dehradun using graph algorithms and geospatial analysis.

## 📌 Project Overview

This project helps optimize delivery routes between Domino’s branches and customer destinations by calculating the shortest possible driving path using Dijkstra’s Algorithm and real-world road network data.

The system provides:
- Automatic nearest branch detection
- Manual branch selection
- Interactive route visualization
- Real-time map generation
- Distance-based optimization

## 🚀 Features

- 📍 Automatic nearest branch selection
- 🛣️ Shortest path calculation using Dijkstra Algorithm
- 🗺️ Interactive route visualization with Folium
- 🌐 Real-world road network integration using OSMnx
- 🏠 Address geocoding support
- 🧭 Manual and automatic routing modes
- 📊 CSV dataset-based branch management

## 🛠️ Technologies Used

- Python
- Streamlit
- Folium
- OSMnx
- Pandas
- OpenCage Geocoder
- Geopy

## 📂 Project Structure

```text
project-folder/
│
├── app.py
├── dataset_ddun.csv
├── route_map.html
└── README.md
```

## ⚙️ Working Principle

1. User enters delivery destination.
2. System converts address into coordinates using geocoding.
3. Nearest Domino’s branch is identified.
4. Road network graph is generated using OSMnx.
5. Dijkstra’s Algorithm calculates shortest route.
6. Route is displayed interactively on map.

## 🧠 Algorithms Used

- Dijkstra’s Shortest Path Algorithm
- Graph-based Routing
- Geodesic Distance Calculation

## ▶️ How to Run

### Install dependencies

```bash
pip install streamlit folium osmnx pandas geopy opencage
```

### Run the application

```bash
streamlit run app.py
```

## 📍 Dataset

The project uses a CSV dataset containing:
- Domino’s branch names
- Latitude and longitude coordinates
- Location-based delivery data

## 🎯 Learning Outcomes

- Understanding graph-based routing systems
- Applying shortest path algorithms in real-world scenarios
- Geospatial data visualization
- Interactive web application development

## 👥 Contributors

Developed as a collaborative academic project.
