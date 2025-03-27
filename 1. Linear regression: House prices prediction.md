# Work in progress

## Linear regression
House price prediction
Dataset:
Evaluation Metrics: MSE, RMSE, MAE, R^2

```ruby
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression

# Sample Data
X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)  # Feature
y = np.array([2, 4, 6, 8, 10])  # Target

# Train model
model = LinearRegression()
model.fit(X, y)

# Predict
predictions = model.predict(X)

# Plot
plt.scatter(X, y, color="blue")
plt.plot(X, predictions, color="red")
plt.show()
```
