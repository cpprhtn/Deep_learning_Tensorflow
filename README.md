# Deep_learning_Tensorflow

## **홍콩 과기대 김성훈 교수의 <모두를 위한 머신러닝 / 딥러닝 강의> 를 통해 공부할 예정**

<li>강의 주소</li>
* https://hunkim.github.io/ml/

<li>아나콘다 - Jupyter Notebook 사용</li>

#### 주피터 Launcher 에러가 뜰 경우
터미널에서 직접 경로지정<br>
```
jupyter notebook --notebook-dir="/Users/cpprhtn/Desktop"
```

### AttributeError: module 'tensorflow' has no attribute 'optimizers' Error
```
from tensorflow.keras import optimizers
<del>tf.optimizers~~()</del> -> optimizers~~()
```
참고주소 https://stackoverflow.com/questions/58837321/how-to-fix-attributeerror-module-tensorflow-has-no-attribute-optimizers-in



Tensorflow verson 2.20 사용
