# 구현할 기능목록

## 기능1.

### 구매 갯수

#### _- 입력 조건_

**\- 1000단위** : `1000원당 1개`(1000원으로 나누어 떨어져야 함)

#### _- 예외 조건_

**\- 정수형** : 문자열, 실수형등 사용 불가

**\- 0제외** : 0이 아니여야 함

```JavaScript

```

## 기능2.

### 로또 발행

#### _- 출력 조건_

**\- 배열 갯수** : 구매 갯수만큼 배열 생성

**\- 배열 정렬** : `6`개 요소를 `오름차순`으로 정렬

```JavaScript

```

## 기능3.

### 당첨 내역

#### _- 당첨 번호 입력 조건_

**\- 구분** : `6`개 요소 `,`로 구분

**\- 입력 범위** : 1~45

**\- 정수형** : 문자열, 실수형등 사용 불가

#### _- 보너스 번호 입력 조건_

**\- 입력 범위** : 1~45

**\- 정수형** : 문자열, 실수형등 사용 불가

**\- 중복** : 당첨 번호랑 중복되면 안됨

```JavaScript

```

## 기능4.

### 당첨 순위 구분

**\- 당첨 조건** :

- 5등 : 3개 일치
- 4등 : 4개 일치
- 3등 : 5개 일치
- 2등 : 5개 일치 + 보너스 번호 일치
- 1등 : 6개 일치

## 기능5.

### 당첨 갯수 저장

**\- 출력조건** : 등수별 당첨 갯수(딕셔너리 활용)

## 기능6.

### 당첨 결과 출력

**\- 출력조건** : 당첨 순위와 당첨 갯수를 출력

## 기능7.

### 수익률

**\- 수익률 계산** : (등수별 가격*당첨 갯수*1000,2)/10

- Math.round : 숫자,반올림할 자리수 (ex-1000,2)

**\- 단위** : %