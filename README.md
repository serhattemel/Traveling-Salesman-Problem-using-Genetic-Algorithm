# Traveling-Salesman-Problem-using-Genetic-Algorithm

This application is used to plan the shortest route between randomly selected locations in a specific area on the map. Initially, 20 locations are randomly chosen on the map.

## How It Works

1. **Location Selection:** 20 locations are randomly selected in a specific area on the map.

2. **Driving Distance Matrix Creation:** The driving distances between the selected points are calculated using the Open Source Routing Machine (OSRM) API. These driving distances are saved as a matrix and exported to a CSV file.

3. **Shortest Route Calculation with Genetic Algorithm:** The shortest route is calculated using a genetic algorithm based on the driving distances in the CSV file.

4. **Route Visualization:** The calculated shortest route is drawn on the map for visual representation.
