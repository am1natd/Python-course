# 🌍 World Cities Database 

## 📜 Project Overview  
- **Dataset**: Major cities worldwide with coordinates, population, and country ([source](https://www.kaggle.com/datasets/max-mind/world-cities-database)).  
- **Travel Conditions**:  
  - Travel is always to the 3 nearest cities.  
  - Base travel times:  
    - 2 hours for the nearest city,  
    - 4 hours for the second nearest,  
    - 8 hours for the third nearest.  
  - Additional 2 hours:  
    - If the destination is in a different country.  
    - If the destination city's population exceeds 200,000.  

## 🧰 Technologies Used  
- **Python Libraries**:  
  - `pandas` for data manipulation.  
  - `numpy` for scientific computations.  
  - `networkx` for graph creation and analysis.  
  - `matplotlib` for visualizations.  
- **Graph Representation**:  
  - Nodes: Cities.  
  - Edges: Travel routes with weights as travel times.  
- **KDTree**: Efficient neighbor-finding algorithm.  

## 🚀 Features  
1. Load and clean dataset.  
2. Build a graph of cities and travel connections.  
3. Simulate traveling eastward around the world.  
4. Verify if the journey can be completed within 80 days (1920 hours).  
5. Visualize travel time distribution.  

## 🔎 Key Results  
- **Outcome**: Determines if a round trip from London is possible within 80 days.  
- **Visualization**: Travel time distribution displayed as a histogram.  

## 📂 Project Structure  
- **`data_preparation.ipynb`**: Load, clean, and prepare the dataset.  
- **`graph_logic.ipynb`**: Build the city graph and calculate travel times.  
- **`analysis_and_visualization.ipynb`**: Simulate the journey, analyze results, and visualize data.  

## 🎨 Visualization Example  
- A histogram showing travel time distribution.
