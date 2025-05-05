### k-Nearest Neighbors (k-NN)
 <img src="/notes/misc/kNearestNeighbors.png" alt="kNearestNeighbor" width="350"/>
Uses proximity to existing data to classify new data. 

<a href="knn Documentation">https://scikit-learn.org/stable/api/sklearn.neighbors.html</a>

```ruby
from sklearn.neighbors import KNeightborsClassifier
import pandas as pd
import numpy as np

#X = 2D np array of features and  y = 1D np array of target values
X = df[["feature_1", "feature_2"]].values 
Y = df["target"].values

#returns array shape
print(X.shape, y.shape) 
knn=KNeighborsClassifier(n_neighbors=n)
knn.fit(X,y)

```
