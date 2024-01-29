
# **Decision Tree Project**

This project is about 'DECISION TREE' Classifire
In this, I have completed One projects.
- Iphone Purchased record project

---
##  **1 . Iphone Purchased record project**
### _Problem statement_

Based on Gender, Age ,Salary  - provide a model for purchase prediction.
### _Method_
I used `Decision Tree` to predict Whether the client can purchased iphone or not.

### This code imports `Decision Tree`

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns 
from sklearn.datasets import make_classification
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score,confusion_matrix,roc_curve, auc
``` 


---

### _Business impact_

So I created a model using `Decision Tree` which predict Whether the client can purchased iphone or not.. And the Accuracy of this Model is 83.75 %. Which means model has well fitted.


---



