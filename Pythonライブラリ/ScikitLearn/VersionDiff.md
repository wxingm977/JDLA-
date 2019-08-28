# 1. datasets.fetch_mldata
Br DeprecationWarning: Function fetch_mldata is deprecated; 
Br fetch_mldata was deprecated in version 0.20 and will be removed in version 0.22. 
Br Please use fetch_openml.

# Load data from https://www.openml.org/d/554
Br %time X, y = fetch_openml('mnist_784', version=1, return_X_y=True)
Br mnist = fetch_openml('mnist_784', version=1)
Br 
Br from sklearn.datasets import fetch_mldata
Br mnist = fetch_mldata('MNIST original')
