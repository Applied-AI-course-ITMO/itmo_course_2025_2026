# ITMO Course 2025/2026

Repository for the Applied AI course 2025/2026.

## Contents

This repository contains educational Jupyter notebooks covering various topics in data science and machine learning:

### Network Science Analysis
- **Location**: `notebooks/network_science/network_analysis.ipynb`
- **Topics**:
  - Introduction to Graph Theory
  - Creating and Visualizing Networks
  - Network Metrics and Centrality Measures
  - Community Detection
  - Random Graph Models (Erdős-Rényi, Barabási-Albert, Watts-Strogatz)
  - Path Analysis and Shortest Paths
  - Directed and Weighted Graphs

### Spatial Data Analysis
- **Location**: `notebooks/spatial_data_analysis/spatial_analysis.ipynb`
- **Topics**:
  - Introduction to Geospatial Data
  - Working with GeoPandas and Shapely
  - Coordinate Reference Systems (CRS)
  - Spatial Operations (Buffers, Intersections, Unions)
  - Distance Calculations and Nearest Neighbor Analysis
  - Spatial Joins and Relationships
  - Interactive Map Visualization with Folium
  - Spatial Clustering (K-means, DBSCAN)

## Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation

1. Clone this repository:
```bash
git clone https://github.com/Applied-AI-course-ITMO/itmo_course_2025_2026.git
cd itmo_course_2025_2026
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

### Running the Notebooks

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the desired notebook in the `notebooks/` directory:
   - `notebooks/network_science/network_analysis.ipynb`
   - `notebooks/spatial_data_analysis/spatial_analysis.ipynb`

3. Run the cells sequentially to explore the analysis and visualizations.

## Dependencies

The main libraries used in this course:
- **NetworkX**: Network analysis and graph algorithms
- **GeoPandas**: Geospatial data manipulation and analysis
- **Matplotlib**: Data visualization
- **Folium**: Interactive map visualization
- **Scikit-learn**: Machine learning algorithms for clustering
- **Pandas & NumPy**: Data manipulation and numerical computing

See `requirements.txt` for the complete list of dependencies.

## License

This repository is for educational purposes as part of the ITMO Applied AI course.
