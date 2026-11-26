# CodeTree 알고리즘 풀이 · Java

CodeTree에서 푼 문제를 Java로 정리했습니다. 각 문제 폴더에는 풀이 코드와 원문 링크가 있습니다.

## 문제 목록

### Trail 1 · 배열과 격자

- [격자 반대로 채우기](trail1/%EA%B2%A9%EC%9E%90%20%EB%B0%98%EB%8C%80%EB%A1%9C%20%EC%B1%84%EC%9A%B0%EA%B8%B0/grid-anti-fill.java)
- [동전이 있는 위치](trail1/%EB%8F%99%EC%A0%84%EC%9D%B4%20%EC%9E%88%EB%8A%94%20%EC%9C%84%EC%B9%98/Where-coins-are-located.java)
- [두 수의 차의 최솟값](trail1/%EB%91%90%20%EC%88%98%EC%9D%98%20%EC%B0%A8%EC%9D%98%20%EC%B5%9C%EC%86%9F%EA%B0%92/minimum-difference-between-two-numbers.java)
- [배열로 사각형 만들기](trail1/%EB%B0%B0%EC%97%B4%EB%A1%9C%20%EC%82%AC%EA%B0%81%ED%98%95%20%EB%A7%8C%EB%93%A4%EA%B8%B0/print-array-in-rectangle.java)
- [배열의 합](trail1/%EB%B0%B0%EC%97%B4%EC%9D%98%20%ED%95%A9/sum-of-array.java)
- [아래로 사각형 채우기](trail1/%EC%95%84%EB%9E%98%EB%A1%9C%20%EC%82%AC%EA%B0%81%ED%98%95%20%EC%B1%84%EC%9A%B0%EA%B8%B0/filling-rectangle-with-downflow.java)
- [지그재그로 정수 채우기](trail1/%EC%A7%80%EA%B7%B8%EC%9E%AC%EA%B7%B8%EB%A1%9C%20%EC%A0%95%EC%88%98%20%EC%B1%84%EC%9A%B0%EA%B8%B0/zigzag-numbering.java)
- [특정 원소들의 합](trail1/%ED%8A%B9%EC%A0%95%20%EC%9B%90%EC%86%8C%EB%93%A4%EC%9D%98%20%ED%95%A9/sum-of-specific-elements.java)

### Trail 2 · 구간 완전탐색

- [1x3 안의 최대 동전 수](trail2/1x3%20%EC%95%88%EC%9D%98%20%EC%B5%9C%EB%8C%80%20%EB%8F%99%EC%A0%84%20%EC%88%98/best-place-of-13.java)
- [구간 중 최대 합](trail2/%EA%B5%AC%EA%B0%84%20%EC%A4%91%20%EC%B5%9C%EB%8C%80%20%ED%95%A9/max-sum-of-subarray.java)
- [바구니 안의 사탕 2](trail2/%EB%B0%94%EA%B5%AC%EB%8B%88%20%EC%95%88%EC%9D%98%20%EC%82%AC%ED%83%95%202/candy-in-the-basket-2.java)
- [특정 구간의 원소 평균값](trail2/%ED%8A%B9%EC%A0%95%20%EA%B5%AC%EA%B0%84%EC%9D%98%20%EC%9B%90%EC%86%8C%20%ED%8F%89%EA%B7%A0%EA%B0%92/elemental-mean-value-for-a-particular-interval.java)

## 한 문제 실행하기

실행할 풀이 하나를 빈 폴더에 `Main.java`라는 이름으로 저장합니다. 각 풀이의 진입 클래스 이름은 `Main`입니다. JDK가 설치된 터미널에서 다음 명령을 실행한 뒤 문제 입력을 넣습니다.

```shell
javac -encoding UTF-8 Main.java
java Main
```

**예시 · 구간 중 최대 합**

입력한 다섯 수에서 연속한 세 수의 합을 비교합니다.

```text
5 3
1 2 3 4 5
```

출력은 `12`입니다. 마지막 세 수 `3 + 4 + 5`가 가장 큰 합입니다.
