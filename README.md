#  KNN Algorithm Implementation

This Python project contains an implementation of the K-Nearest Neighbors (KNN) algorithm. KNN is a simple, yet powerful, classification algorithm used for supervised learning tasks.
It's a non-parametric method used for classification and regression tasks.

## Dependencies
 To run this script, you'll need:
 - Jupyter Notebook
 - Python (version >= 3.x)
 - NumPy
 - scikit-learn

## You can install the dependencies via pip:
```
pip install numpy scikit-learn
```

## Usage
1. Clone or download this repository.
2. Launch Jupyter Notebook:
``` bash
jupyter notebook
```
3. Navigate to the directory where you cloned/downloaded the repository and open the ciciot.ipynb notebook.
4. Run the cells in the notebook to see the implementation of the KNN algorithm and its results.
5. Ensure you have the required dependencies installed.



## File Structure
 - `ciciot.ipynb`: Jupyter Notebook containing the implementation of the KNN algorithm and hyperparameter tuning.
 - `csv/`: Directory containing sample datasets for testing.

## Sample Datasets
  The `csv/` directory contains some sample datasets to test the algorithm. Feel free to use your own datasets by modifying the script accordingly.

## Algorithm Details
KNN works by finding the K nearest points in the training data to a given input data point. It then assigns the label of the majority of the K nearest neighbors to the input data point.


## Acknowledgments
- Inspired by the simplicity and effectiveness of the KNN algorithm.
- Thanks to scikit-learn for providing a reference implementation of KNN.
