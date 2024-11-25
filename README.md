# Python-course
 Around the World Travel Simulation
This project simulates traveling around the world, starting and ending in London, using a dataset of major cities. It answers whether it's possible to complete the journey within 80 days while adhering to given travel conditions.

📜 Project Overview
Dataset: Includes coordinates, population, and country for major cities worldwide (source).
Key Conditions:
Travel is always to the 3 nearest cities.
Base travel times:
2 hours for the nearest city,
4 hours for the second nearest,
8 hours for the third nearest.
Additional 2 hours:
If the destination is in a different country.
If the destination city's population exceeds 200,000.
🧰 Technologies Used
Python Libraries:
pandas for data manipulation.
numpy for scientific computations.
networkx for graph creation and analysis.
matplotlib for visualizations.
Graph Representation: Cities are nodes, and edges represent possible travel routes with weights as travel times.
KDTree: Efficiently identifies the 3 nearest neighbors for each city.
🚀 Features
Load and clean dataset.
Build a graph of cities and their travel connections.
Simulate traveling eastward around the world.
Check if the journey can be completed within 80 days (1920 hours).
Visualize travel time distribution.
🔎 Key Results
Travel Outcome: Successfully determines if a round trip from London can be achieved within 80 days.
Visualization: Displays the distribution of travel times during the journey.
📂 Project Structure
data_preparation.ipynb: Load, clean, and prepare the dataset.
graph_logic.ipynb: Build the city graph and calculate travel times.
analysis_and_visualization.ipynb: Simulate the journey, analyze results, and visualize data.
🎨 Visualization Example
Histogram of travel time distribution.
Run the notebooks in order:
data_preparation.ipynb
graph_logic.ipynb
analysis_and_visualization.ipynb
