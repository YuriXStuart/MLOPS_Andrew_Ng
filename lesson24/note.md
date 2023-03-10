# Lesson 24

## 빅데이터에서 고품질 데이터로

- 빅데이터를 가지고 있다면 모델 알고리즘 성능 향상에 도움이 된다. 구글과 같이 거대한 사용자 데이터를 갖고 있는 회사의 경우 인공지능 분야에서 엄청난 성장을 이루었다. 그러나 인터넷 사용자 기록만큼 방대한 데이터를 가진 회사는 드물다. 
- 단순히 "빅"데이터를 갖는 데에 초점을 둘 것이 아니라 높은 품질의 "좋은(고품질)" 데이터를 갖는 데 집중해야 한다.
- 앞서 설명한 모든 ML 프로젝트 단계에서 좋은 품질의 데이터를 보유한다면, 높은 성능을 가지면서 안정적으로 작동하는 ML 서비스를 배포할 수 있다.

## 좋은 데이터란?
1. 다양한 중요 케이스를 포괄할 수 있는 입력 변수(input, X)의 범주
2. 일관성있는 데이터 정의(특히 정답지 y의 라벨이 명확)
3. 생산 데이터로부터 적시적인 피드백을 받은 데이터(data drift, concept drift 포괄)
    - 데이터 분포가 변화하거나 비즈니스 변동/생산과정 변동 등으로 인해 데이터 컨셉이 변화하는 것을 지속적으로 모니터링&추적하고 상황에 맞게 데이터를 조정
4. 합리적인 데이터 사이즈
