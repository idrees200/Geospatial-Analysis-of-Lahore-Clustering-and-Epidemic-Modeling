# Geospatial Analysis of Lahore, Clustering, and Epidemic Modeling

This repository contains Python code for performing various geospatial analysis tasks, clustering, density estimation, and epidemic modeling using libraries such as `geopandas`, `matplotlib`, `contextily`, `numpy`, `seaborn`, and `scikit-learn`.

## Contents

1. **Geospatial Data Visualization**:
   - Loads shapefiles (`buildings.shp`, `landuse.shp`, `natural.shp`, `places.shp`, `points.shp`, `railways.shp`, `roads.shp`, `waterways.shp`) using `geopandas`.
   - Plots each layer on separate matplotlib figures with customized colors and background.
   - Visualizes random points within the bounding box of the data.

2. **Nearest Neighbor Classification**:
   - Defines a custom `NearestNeighborClassifierManual` class using numpy for nearest neighbor classification.
   - Trains the classifier on random points and predicts labels based on the nearest neighbors.

3. **K-Means Clustering**:
   - Applies `KMeans` clustering from `scikit-learn` to randomly generated points (`random_points`).
   - Plots clusters and their centroids with respective radii.

4. **Correlation Matrix Calculation**:
   - Computes the correlation matrix (`correlation_matrix`) for points data using `pandas` and `numpy`.
   - Prints and visualizes the correlation matrix using `seaborn`.

5. **Density Estimation**:
   - Defines a function (`calculate_density`) to estimate densities of clusters using distances and radii.
   - Uses `seaborn` to plot kernel density estimation (KDE) overlaying geospatial layers and random points.

6. **Epidemic Modeling**:
   - Simulates epidemic circles and labels random points inside these circles.
   - Uses KDE to estimate intensity of zones based on random points and epidemic circles.
   - Plots epidemic circles and heatmap showing zone intensities.

7. **Nearest Neighbor Visualization**:
   - Implements `NearestNeighbors` from `scikit-learn` to find nearest neighbors for random points.
   - Plots circles representing epidemic centers with intensity colors based on radii.

## Usage

1. **Environment Setup**:
   - Install required libraries using `pip install pandas geopandas matplotlib contextily seaborn scikit-learn`.

2. **Data Upload**:
   - Upload required shapefiles (`*.shp`) or use provided sample data.

3. **Execution**:
   - Run each script (`*.py`) to perform specific geospatial analysis or modeling task.
   - Adjust parameters and configurations based on specific use cases or datasets.

4. **Output**:
   - Each script produces visualizations, metrics, or data insights based on the executed task.
   - Refer to individual script comments or code blocks for detailed functionalities and outputs.

## Dependencies

- `pandas`
- `geopandas`
- `matplotlib`
- `contextily`
- `seaborn`
- `scikit-learn`
- `numpy`

## Future Enhancements

- Incorporate interactive plots using `Plotly` or `Bokeh` for better visualization and exploration.
- Extend clustering techniques with `DBSCAN` or `Hierarchical Clustering` for complex spatial analysis.
- Enhance epidemic modeling with dynamic parameters and real-time data integration.
![Screenshot 2024-06-23 195321](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/f0e381ef-ad4b-4017-b1e0-22e226b19ec1)![Screenshot 2024-06-23 195456](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/96c05281-6121-4432-bbd4-cc7d50a45549)
![Screenshot 2024-06-23 195443](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/63c76fa7-1fb8-41f3-8ae0-5b0abecba061)
![Screenshot 2024-06-23 195436](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/fb07dc7d-f482-4828-a5ea-d97004d8b210)
![Screenshot 2024-06-23 195430](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/60b8db32-7d79-439c-b83a-b87cfcb1f82d)
![Screenshot 2024-06-23 195424](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/382e839f-2574-4322-bee7-c8b186368989)
![Screenshot 2024-06-23 195404](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/5165b390-ab71-4bb7-8cc7-78184463f506)
![Screenshot 2024-06-23 195357](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/d65a342b-24b1-40a5-a88e-93589c1db0c2)
![Screenshot 2024-06-23 195348](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/6492d874-c6e1-4dc0-8ad8-7e79f18cb0b9)
![Screenshot 2024-06-23 195341](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/e33ddad2-d062-40b2-abdd-212263fa2d2f)
![Screenshot 2024-06-23 195332](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/fabc7ede-ea2f-45f4-a00a-7937b005c257)


![Screenshot 2024-06-23 195504](https://github.com/idrees200/Geospatial-Analysis-of-Lahore-Clustering-and-Epidemic-Modeling/assets/113856749/2b3b42ca-e430-428e-8cfd-2117b9515170)
