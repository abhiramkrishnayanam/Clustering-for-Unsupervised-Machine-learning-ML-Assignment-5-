# Clustering on Iris Dataset

This project focuses on performing clustering techniques on the Iris dataset. It includes data preprocessing, exploratory data analysis, and clustering using both K-Means and Hierarchical methods. Visualizations such as scatter plots, dendrograms, and the Elbow method are utilized to evaluate and display the clustering results.

## Dataset
The Iris dataset is a popular multivariate dataset that contains 150 samples of iris flowers, each described by four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is used to classify flowers into three species:
- Setosa
- Versicolor
- Virginica

## Project Workflow

### 1. Data Preprocessing
- Loaded the Iris dataset.
- Handled basic preprocessing tasks to prepare the data for clustering.
- Standardized the features to ensure uniform scaling.

### 2. Exploratory Data Analysis
- Examined the dataset's structure and feature distributions.
- Visualized relationships between features using scatter plots.

### 3. K-Means Clustering
- Determined the optimal number of clusters using the **Elbow Method**.
- Plotted the Elbow Curve to visualize the sum of squared distances for different cluster counts.
- Fitted the K-Means model to the dataset and assigned cluster labels.
- Visualized the resulting clusters using scatter plots.

### 4. Hierarchical Clustering
- Constructed a dendrogram to visualize the hierarchical clustering process.
- Determined the optimal cluster count from the dendrogram.
- Applied the Agglomerative Clustering algorithm to the dataset.
- Visualized the resulting clusters using scatter plots.

## Visualizations
The project includes the following visualizations:
- **Elbow Curve**: To identify the optimal number of clusters for K-Means.
- **Dendrogram**: To visualize the hierarchical clustering process.
- **Scatter Plots**: To display the clustering results for both K-Means and Hierarchical methods.

## Technologies Used
- **Python**
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Scipy

## How to Run
1. Clone the repository.
2. Ensure you have Python installed with the required libraries.
3. Run the Jupyter Notebook file (`Clustering Assignment.ipynb`) to execute the code and view the outputs.

## Results
- Successfully clustered the Iris dataset into meaningful groups using K-Means and Hierarchical Clustering.
- Optimal number of clusters was determined based on the Elbow Method and dendrogram analysis.
- Clustering results were visualized for better interpretability.

## Acknowledgments
This project is based on the Iris dataset, a standard dataset in machine learning and statistical analysis. Special thanks to scikit-learn and its contributors for providing accessible tools for clustering and visualization.

---

Feel free to contribute to this project by suggesting improvements or additional analyses!

