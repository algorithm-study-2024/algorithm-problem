# 완전탐색(Brute Force)

<br/>

## 완전탐색 알고리즘?

- 가능한 모든 경우의 수를 탐색하여 해답을 찾는 알고리즘 기법이다
- `모든 조합에 대해 모든 가능성을 시도`해보는 방식으로 동작한다

<br/>

## 특징

### 비효율성

모든 경우를 검사하기 때문에 입력 크기에 따라 시간 복잡도가 급격히 증가할 수 있다

### 확실한 해결

가능한 모든 경우의 수를 검사하므로 정확한 해결책을 찾을 수 있다

<br/>

## 활용 사례

- 문자열 조합 : 문자열에서 가능한 모든 부분 문자열을 생성하거나 문자의 순열을 찾는 경우
- 조합 최적화 문제 : 모든 가능한 조합 중에서 최적의 조합을 찾아야 하는 경우

<br/>

## 한계 및 최적화

입력 크기에 따라 시간 복잡도가 급격히 증가할 수 있으므로, 대규모 입력에 적합하지 않다.

### 최적화

- 가지치기
  - 불필요한 경우의 수를 제거하여 탐색 범위를 줄여서 성능을 향상시킬 수 있다
  - for문의 조건식, 내부 조건문 등
