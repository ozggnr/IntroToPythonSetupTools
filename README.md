This package can be installed through pip
```python
pip install o_pkg
```
This package contains two different modules: newly and newhom9. By calling 
```python
from o_pkg import newly
```
user gets 4 different figures related to Breast Cancer Dataset from sklearn database. First figure shows pairplot 
of the 10 selected features. Second figure indicates the heat map of these features together with their correlation
percentage with each other. Third figure is to demonstrate the difference between highly correlated features such as
"mean area" and "mean perimeter", and weakly correlated feature like "perimeter error". Last figure shows the pairplot
of selected 3 features having least correlation together with target "diagnosis".

By calling
```python
from o_pkg import newhom9
```
user gets the best clustering (K-means) fitting score, and corresponding training and test data for Iris Dataset from 
sklearn database as a result. This score can be obtained either by when it satisfies a certain threshold (>0.80) or by
selecting the best among the scores after iterating 10000 times.
