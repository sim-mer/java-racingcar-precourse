# java-racingcar-precourse

## 🚗 자동차 경주 게임

### 📝 기능 요구사항

## 자동차
- 자동차는 이름을 가진다.
- 자동차가 전진하는 조건은 0에서 9 사이의 랜덤값이 4 이상일 경우이다.
- 자동차가 전진하면 자동차의 위치를 1 증가시킨다.
- 자동차의 위치를 나타낼 때는 `-`를 이용한다.
- 자동차의 toString()은 자동차의 이름과 위치를 출력한다.

## 사용자
- 사용자는 자동차 이름을 입력할 수 있다.
  - 자동차 이름은 쉼표(,)를 기준으로 구분한다.
  - 이름은 5자 이하만 가능하다.
  - 이름은 공백일 수 없다.
- 사용자는 몇 번의 이동을 할 것인지 입력할 수 있다.
  - 이동 횟수는 1 이상의 10000 이하의 자연수만 가능하다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시키고 "[ERROR]"로 시작하는 에러 메시지를 출력 후 그 부분부터 입력을 다시 받는다.

## 게임
- 게임은 사용자가 입력한 자동차 이름을 가진 자동차들로 진행된다.
- 게임은 사용자가 입력한 이동 횟수만큼 자동차를 전진시킨다.
- 전진하는 자동차를 출력한다.
- 자동차 경주가 종료되면 우승자를 출력한다.
  - 우승자는 한 명 이상일 수 있다.
  - 우승자가 여러 명일 경우 쉼표(,)를 이용해 구분한다.
