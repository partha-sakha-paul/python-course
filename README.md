# Module 15
# `Part A`
## Iris Dataset Classification with SVM

This demonstrates how to classify the Iris dataset using a Support Vector Machine (SVM) classifier. The Iris dataset is a well-known dataset in the field of machine learning, and SVM is a powerful classification algorithm.

### Structure

- [Iris data](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/iris.data): Directory containing the Iris dataset.
- [notebook](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/iris.ipynb): Jupyter notebooks with code and explanations.
- [src](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/iris.py): Source code for data processing and model training.
- `README.md`: This file.

### Dataset

The `Iris dataset` consists of 150 samples of iris flowers, with four features: `sepal length`, `sepal width`, `petal length`, and `petal width`. The goal is to classify the samples into three species of iris flowers: `Setosa`, `Versicolor`, and `Virginica`.

### Requirements
- Python 3.0 and above
- pandas
- numpy
- scikit-learn
- jupyter

One can install the required packages using the following command:

```python
pip install pandas numpy scikit-learn jupyter
```
### Precedure
- Loading the Dataset
- Training the SVM Classifier
- Evaluate the model and making the predictions over new inputs

# `Part B`
## Carpark Locator

This aims to identify the `closest car parks` to a specified target location using `GeoPandas`, `Folium`, and `Scikit-learn`. The project involves creating a GeoDataFrame from a CSV file containing car park data, plotting these car parks on an interactive map, and determining the nearest car parks to a target location using the `NearestNeighbors` algorithm from Scikit-learn.

### Structure

- [utils.pynb](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/utils.ipynb): Contains utility functions for converting a DataFrame to a GeoDataFrame and plotting the GeoDataFrame on an interactive map.
- [carpark.pynb](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/carpark.ipynb): Main script that loads the car park data, creates a GeoDataFrame, plots the car parks, and identifies the closest car parks to a target location.
- [car-park-locations-data.csv](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/car-park-locations-data.csv): CSV file containing car park locations with latitude and longitude.
- [output.html](https://github.com/partha-sakha-paul/python-course/blob/main/module%2015%20machine_learning/output.html): Interactive map displaying for the car park locations.

### Prerequisites

- Python 3.0 and above
- Pandas
- GeoPandas
- Folium
- Shapely
- Scikit-learn

### Installation

1. Install the required Python libraries:
    ```bash
    pip install pandas geopandas folium shapely scikit-learn
    ```

2. Ensure the `car-park-locations-data.csv` file in the same directory.

### Procedure
- Converting DataFrame to GeoDataFrame
- Plotting GeoDataFrame
- Finding the Closest Car Parks



# Module 19
## Introduction to Git
### Branch Operations used
- Create a branch for a new feature:
- Checkout the branch:
- Add changes to a file:
- Add and commit changes:
- Merge the feature branch back into master:
- Handle merge conflicts if any, and finalize the merge:
- To reset and clean up your Git repository:
### Final Exercise
`Create the NIRailways map in a git tree`
