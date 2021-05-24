## Normalization


Normalization is a scaling technique in which values are rescaled to range $(0,1)$.


## Why we should normalize data?

- Algorithms that use gradient descent as an optimization technique (linear regression/logistic regressionl/neural network) require scaled data.


- Distance algorithms (KNN/ SVM) are most affected by the range of features. Since both the features have different scales, there is a chance that higher weightage is given to features with higher magnitude.

***
FORMULA
***

$
\begin{align}
X'=\frac{X-X_{min}}{X_{max}-X_{min}}
\end{align}$

Where:

- $X_{min}$ - minimal feature value
- $X_{max}$ - maximal feature value



***
EXAMPLE
***

|x1|x2|
| ------ | ------ |
|1|6|
|2|2|
|3|0|


for x1:

 - $\frac{1-1}{3-1} = 0$
 - $\frac{2-1}{3-1} = 0.5$
 - $\frac{3-1}{3-1} = 1$
 
for x2:

 - $\frac{6-0}{6-0} = 1$
 - $\frac{2-0}{6-0} = 0.33$
 - $\frac{0-0}{6-0} = 0.5$

|x1_scaled|x2_scaled|
| ------ | ------ |
|0|1|
|0.5|0.33|
|1|0|


# Standardization

Standardization is scaling technique where the mean of the attribute becomes zero and the resultant distribution has a unit standard deviation.


***
FORMULA
***

$
\begin{align}
X'=\frac{X-\mu}{\sigma}
\end{align}$

Where:

- $\mu$ - mean of feature 
- $\sigma$ - standard deviation of feature

***
EXAMPLE
***

|x1|x2|
| ------ | ------ |
|0|1|
|1|0|



for x1:

$\mu = 0.5$

$\sigma = 0.5$


 - $\frac{0-0.5}{0.5} = -1$
 - $\frac{1-0.5}{0.5} = 1$

|x1_scaled|x2_scaled|
| ------ | ------ |
|-1|1|
|1|-1|


***

APPLICATION IN PYTHON
***

| Function | Readme |
| ------ | ------ |
| `MinMaxScaler()` |[MinMaxScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html#sklearn.preprocessing.MinMaxScaler)|
| `normalize()` | [normalize](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.normalize.html)|
| `StandardScaler()`| [standarization](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html#sklearn.preprocessing.StandardScaler)|




## Helpful links:

- https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/
- https://scikit-learn.org/stable/modules/preprocessing.html
- https://machinelearningmastery.com/rescaling-data-for-machine-learning-in-python-with-scikit-learn/
