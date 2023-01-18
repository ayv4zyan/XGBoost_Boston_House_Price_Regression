# Boston House price prediction using XGBoost

<a href="https://colab.research.google.com/github/NeonRio/XGBoost_Boston_House_Price_Regression/blob/main/XGBoost_Boston_House_Price_Regression.ipynb"><img data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667"></a>
<br />
In this project I've created price prediction model for Boston House dataset using XGBoost.
<br />
XGBoost (eXtreme Gradient Boosting) is an open-source software library which provides a regularizing gradient boosting framework for C++, Java, Python, R, Julia, Perl, and Scala. It works on Linux, Windows, and macOS. From the project description, it aims to provide a "Scalable, Portable and Distributed Gradient Boosting (GBM, GBRT, GBDT) Library". It runs on a single machine, as well as the distributed processing frameworks Apache Hadoop, Apache Spark, Apache Flink, and Dask.

It has gained much popularity and attention recently as the algorithm of choice for many winning teams of machine learning competitions.

<img src="https://cdn-images-1.medium.com/max/800/1*V-vikG-ye2Y03R943d0CPw.jpeg" width="70%"/>

### Dataset
<bold>About the dataset</bold>
<br />
<p>Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): CRIM: per capita crime rate by town</p>
<ol>
<li>ZN: proportion of residential land zoned for lots over 25,000 sq.ft.</li>
<li>INDUS: proportion of non-retail business acres per town</li>
<li>CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)</li>
<li>NOX: nitric oxides concentration (parts per 10 million)<br>
<li>RM: average number of rooms per dwelling</li>
<li>AGE: proportion of owner-occupied units built prior to 1940</li>
<li>DIS: weighted distances to ﬁve Boston employment centers</li>
<li>RAD: index of accessibility to radial highways</li>
<li>TAX: full-value property-tax rate per $10,000</li>
<li>PTRATIO: pupil-teacher ratio by town 12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 13. LSTAT: % lower status of the population</li>
<li>MEDV: Median value of owner-occupied homes in $1000s<br>
We can see that the input attributes have a mixture of units.</li>
</ol>

### References
<hr>
<li><a href="https://www.kaggle.com/datasets/vikrishnan/boston-house-prices">
    https://www.kaggle.com/datasets/vikrishnan/boston-house-prices</a>
</li>
<li><a href="https://www.youtube.com/watch?v=XXHhrlL-FWc">
    https://www.youtube.com/watch?v=XXHhrlL-FWc</a>
</li>
<li><a href="https://xgboost.readthedocs.io/en/stable/python/python_intro.html">
    https://xgboost.readthedocs.io/en/stable/python/python_intro.html</a>
</li>
<li><a href="https://medium.com/sfu-cspmp/xgboost-a-deep-dive-into-boosting-f06c9c41349">
    https://medium.com/sfu-cspmp/xgboost-a-deep-dive-into-boosting-f06c9c41349</a>
</li>
<li><a href="https://en.wikipedia.org/wiki/XGBoost">
    https://en.wikipedia.org/wiki/XGBoost</a>
</li>
