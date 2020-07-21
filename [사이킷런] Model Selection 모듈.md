# 1. train_test_split()

<img src="/image/2.png">

- test_size : 테스트 데이터 세트 비율, 디폴트는 0.25

- random_state : 호출할 때마다 같은 학습/테스트 용 dataset를 생성하기 위해 주어지는 난수 발생 값
  - train_test_split()은 무작위로 데이터를 분류하므로 random_state 를 지정하지 않으면 수행할 때마다 다른 학습/테스트 용 데이터를 만들 수 있다.
  - 숫자 자체는 어떤 값을 지정해도 상관 없다.
- shuffle : 데이터를 분리하기 전에 데이터를 미리 섞을지를 결정한다. 디폴트는 True. 데이터를 분산시켜서 좀 더 효율적인 학습 및 dataset를 만드는 데 사용한다.
- train_test_split()의 반환값은 튜플형태



# 2. 교차 검증

> - train data에만 최적화 되는 과적합을 막기 위한 것
> - 시험으로 치면 모의고사 같은 것
> - train data를 다시 분할하여 train data와 학습된 모델의 성능을 일차 평가하는 validation data로 나눈다.

### 1) K 폴드 교차 검증



# 3. GridSearchCV