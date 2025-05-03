# Supervised Learning with scikit-learn

### Supervised Learning (SL)
In SL, the **target variable** is predicted through **features**. The model's predicted values are known.

#### Types of SL
**1. Classification:** binary (fraud detection, spam filtering)
     
**2. Regression:** continuous numerical value (house prices)

#### Requirements for SL
- No NULL data.
- Only numeric data.
- Data in pandas or numpy array.
- Should begin with data exploration.
  
#### Scikit-learn general flow
```ruby
from sklearn.module import Model
model = Model()
model.fit(X,y)
model.predict(X_new)
```

#### Classification
1. Build a model
2. Model learns from labeled data (training set)
3. Unlabeled data is inputted to model
4. Model predicts labels

#### k-Nearest Neighbors




