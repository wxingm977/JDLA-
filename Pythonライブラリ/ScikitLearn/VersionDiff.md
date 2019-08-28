# 1. datasets.fetch_mldata
DeprecationWarning: Function fetch_mldata is deprecated;  
fetch_mldata was deprecated in version 0.20 and will be removed in version 0.22.  
Please use fetch_openml.  

Load data from https://www.openml.org/d/554
```
%time X, y = fetch_openml('mnist_784', version=1, return_X_y=True)  
mnist = fetch_openml('mnist_784', version=1)  
from sklearn.datasets import fetch_mldata  
mnist = fetch_mldata('MNIST original')
```  
