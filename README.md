# Tensorflow

* data flow graphs를 사용해서 numerical 한 computation을 하는 라이브러리

### What is a Data Flow Graph?

* Nodes : mathematical operations
* Edges : multidimensional data arrays (or tensors)

### How to use?

```
>>> import tensorflow as tf
>>> tf.__version__
'version'
```



# Lecture 1

## Machine Learning Basics

* What is ML?
* What is learning?
* What is regressions?
* What is classification?



### Machine learning (기계학습)

* Limitations of explicit programming
  * 명시적 프로그래밍. 개발자가 코드로 rules를 주어, 
* Machine Learning

#### Supervised learning (지도 학습)

* learning with labeled examples - training set 이라고 한다.

#### Unsupervised learning (비지도 학습)

* Google news grouping
* Word clustering



### Supervised learning

* Most common problem type in ML
* for example,
  * Image labeling
  * Email spam filter
  * Predicting exam score



### Training data set

* supervised learning에서 학습하는데 필요한 데이터 셋



### Types of supervised learning

* Predicting final exam score based on time spent
  * ex) 0 ~ 100 예측 : **regression** 
* Pass/non-pass based on time spent
  * ex) pass, non-pass 분류 : **binary classification**
* Letter grade (A, B, C, D, F) based on time spent
  * ex) A, B, C, D, F 분류 : **multi-label classification**

