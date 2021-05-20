# Feature extraction

Feature extraction is the process of building derived values (features) from an initial set of measured data intended to be informative and non-redundant, facilitating the subsequent learning and generalization steps, and in some cases leading to better human interpretations.[^w]

[^w]: https://en.wikipedia.org/wiki/Feature_extraction

Feature extraction involves creating variables by extracting them from some other data. For example, using[^d]:

* Principal components analysis (PCA) to create a small number of predictor variables from a much larger number.
* Orthogonal rotations of predictor variables to minimize the effect of them being highly correlated.
* Cluster analysis to create a categorical variable from multiple numeric variables.
* Text analytics to extract numeric variables, such as sentiment scores, from text data.
* Edge detection algorithms to identify shapes in images.

[^d]: https://www.displayr.com/what-is-feature-engineering/

## External links

### Tools

- [pymfe: Python Meta-Feature Extractor](https://github.com/ealcobaca/pymfe) - provides a comprehensive set of meta-features
- [tsfresh: Time Series Feature extraction based on scalable hypothesis tests](https://github.com/blue-yonder/tsfresh) - contains many feature extraction methods and a robust feature selection algorithm
- [sklearn.feature_extraction](https://scikit-learn.org/stable/modules/feature_extraction.html) - can be used to extract features in a format supported by machine learning algorithms from datasets consisting of formats such as text and image

### Courses

* [Feature Engineering on Pluralsight](https://www.pluralsight.com/paths/feature-engineering)
* [Feature Extraction on Coursera](https://www.coursera.org/lecture/data-machine-learning/feature-extraction-tBSBw)