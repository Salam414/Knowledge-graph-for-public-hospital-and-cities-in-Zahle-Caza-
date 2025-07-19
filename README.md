# Knowledge-graph-for-public-hospital-and-cities-in-Zahle-Caza-
A simple knowledge graph, to show the distance between cities in Caza Zahle, Lebanon and the governmental hospital in Zahle

🗺️ Bekaa Public Hospitals Accessibility - NetworkX Graph Project

This project uses **NetworkX**, **Geopy**, and **Cartopy** to build and visualize a static geographic **knowledge graph** connecting cities in the Bekaa region to public hospitals. It computes the **geodesic distance** between each city and hospital and visualizes both the nodes and edges on a map.

📌 Project Objectives

- Model the **spatial relationship** between cities and public hospitals in the Bekaa region of Lebanon.
- Compute the **distance in kilometers** between each city-hospital pair.
- Visualize this network using **NetworkX** and **Cartopy**.
- Represent the shortest path to health facilities.

📁 Files:
- "cities in bekaa": csv file includes all the city name, latitude, longtitude.
- "hospitals in bekaa": csv file includes the governmental hospital in Zahle
- "Simple graph": it's a little demo to show how the libraries work together to create a knowledge graph
- "graph with all cities": The main Python file where the graph is constructed and plotted.
- "graph using folium": the python file where the graph is constructed in a map.
- "README": this documentation

🔧 Libraries Used

- 'pandas': For reading CSV files and data manipulation
- 'networkx': To build the graph structure (nodes = cities and hospitals, edges = distances)
- 'geopy':To compute geodesic distances between coordinates
- 'matplotlib':For plotting
- 'cartopy': For geographic map plotting
- 'folium': a Python library used to create interactive maps powered by Leaflet.js

🧠 Graph Structure

- **Nodes**:
  - Cities → type=`city' 
  - Hospitals → type=`hospial' 
- **Edges**:
  - Connect every city to every hospital in black
  - Weighted by geodesic distance in kilometers

  📊 Visualization Output
The script outputs a static map:
- **Blue dots** = Cities
- **Green dots** = Public hospitals
- **Black lines** = Connections with labeled distances

▶️ How to Run
1. Install the necessary libraries
   pip install pandas networkx geopy matplotlib cartopy folium
2. Install the csv files and upload them
3. Run the code on Jupyter Notebook or python environment.

📍 Ressources:
- Name of cities: https://www.opendatalebanon.org/job/list-of-public-hospitals-in-lebanon/
- Name of the governmental hospital: https://www.moph.gov.lb/en/Pages/3/567/public-hospitals

👨‍💻 Author
Salam - Data Science, AI/ML enthusiasts
Built for healthcare equity and data-driven planning.
