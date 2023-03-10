# Lesson 18

- ML/DL 서비스를 개선하는 방법에는 (1) 모델 중심 개선과 (2) 데이터 중심 개선 두 가지가 있다. 이번 장에서는 데이터 중심 개선에 대해 서술한다.
- 대부분의 분석가들이 모델 중심 개선에 익숙해하지만 데이터 중심의 개선도 시도해야 한다.

## Data iteration - 데이터 중심 서비스 개선

||<center>모델 중심 개선</center>|<center>데이터 중심 개선</center>|
|:---:|:---|:---|
|관점|1. 보유한 데이터를 최대한 잘 활용 가능한 모델 개발<br/> 2. 데이터를 고정시키고 모델/코드 개선 |1. 데이터 품질이 가장 중요 <br/>2. 오류분석이나 데이터 증강(augmentation)을 통해 개선 <br/>3. 코드를 고정시키고 데이터를 반복적으로 개선|
|분야|리서치(학문) 분야<br/> $\rightarrow$ 데이터가 고정되고 한정적이기 때문에 모델 중심 개선이 활발|응용분야<br/>$\rightarrow$ 좋은 품질의 데이터를 확보하면 여러가지 모델이 잘 작동|