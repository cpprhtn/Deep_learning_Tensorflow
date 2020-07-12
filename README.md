# Deep_learning_Tensorflow

## **홍콩 과기대 김성훈 교수의 <모두를 위한 머신러닝 / 딥러닝 강의> 를 통해 공부할 예정**

<li>강의 주소</li>
* https://hunkim.github.io/ml/

<li>아나콘다 - Jupyter Notebook 사용</li>
### 주피터 Launcher 에러가 뜸
터미널에서 직접 경로지정<br>
jupyter notebook --notebook-dir="/Users/cpprhtn/Desktop"

### AttributeError: module 'tensorflow' has no attribute 'optimizers' Error
from tensorflow.keras import optimizers load하기 <br>
<del>tf.optimizers~~()</del> -> optimizers~~()



Tensorflow verson 2.20이지만
**import tensorflow.compat.v1 as tf <p>
tf.disable_v2_behavior()**
을 이용하여 강의 버전을 맞추어 할것 <p>

* 일부 tf.v1이 적용안되는 부분은 tf.v2 사용




## **cpprhtn의 커리큘럼**

* R, pandas, numpy 를 공부, tree 계열의 머신러닝 라이브러리인 random forest, xgboost, lightgbm 등을 공부

* 딥러닝 라이브러리인 tensorflow, keras 공부

* 하둡, 맵리듀스 등의 빅데이터 플랫폼도 공부해보기!

<li>진행상태</li>
<ol>
			<li>R basic - 독학(인터넷&유튜브)</li>
			<li>R graphics - R Graphics Cookbook(Winston Chang 지음)</li>
      <li>Pandas - 파이썬 머신러닝 판다스 데이터분석(오승환 지음)</li>
      <li>numpy(+Deep Learning) - Deep Learning from Scratch_밑바닥부터 시작하는 딥러닝(사이토 고키 지음) **진행중**</li>
      <li>Deep Learning Tensorflow - 모두를 위한 머신러닝 / 딥러닝 강의 (홍콩 과기대 김성훈) **진행중**</li>
</ol>
