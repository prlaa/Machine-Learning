# Supervised Learning with scikit-learn

### Supervised Learning (SL)
Predict target from features. Targets are known.

#### Types
**1. Classification:** binary (fraud detection, spam filtering)    
**2. Regression:** continuous numerical value (house prices)

#### Requirements
- No NULL data.
- Only numeric data.
- Use pandas or numpy
- Start with EDA 
  
#### Scikit-learn workflow
```ruby
from sklearn.module import Model
model = Model()
model.fit(X,y)
model.predict(X_new)
```

#### Classification flow
1. Build model
2. Train with labeled data
3. Input unlabeled data
4. Predict labels



