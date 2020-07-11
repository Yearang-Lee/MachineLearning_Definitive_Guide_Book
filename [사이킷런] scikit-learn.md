# **scikit-learn** 

> 파이썬 머신러닝 라이브러리 중 가장 많이 사용되는 라이브러리



Anaconda를 설치하면 기본으로 사이킷런까지 설치가 완료되기 때문에 별도의 설치가 필요 없지만

설치해야 하는 경우에는 다음과 같이 하면 된다.

 cmd창이나 Anaconda Prompt창에 

 

**conda install scikit-learn**  이나

**pip install scikit-learn**  으로 설치해주면 된다.



scikit-learn 홈페이지

https://scikit-learn.org/stable/index.html



- #### **scikit-learn은 아래와 같이 머신러닝을 위한 API를 제공한다.**

  - Classification
  - Regression
  - Clustering
  - Dimensional reduction
  - Model selection
  - Preprocessing

  

- #### **사이킷런 패키지내의 모듈**

  - **sklearn.datasets** : 사이킷런에서 자체적으로 제공하는 데이터 세트를 생성하는 모듈의 모임
  - **sklearn.tree** : 트리 기반 ML 알고리즘을 구현한 클래스의 모임
  - **sklearn.model_selection** : 학습/검증/예측 데이터로 데이터를 분리하거나 최적의 하이퍼 파라미터로 평가하기 위한 다양한 모듈의 모임



예를 들어, 붓꽃 데이터 세트를 생성하는 데는 load_iris()를 사용하며, 

ML 알고리즘은 Decision tree 알고리즘으로, 

이를 구현한 DecisionTreeClassifier를 적용한다.

```python
from sklearn.datasets import load_iris
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
```

