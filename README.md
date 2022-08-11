# java-racingcar

자동차 경주 미션 저장소

## 우아한테크코스 코드리뷰
- [온라인 코드 리뷰 과정](https://github.com/woowacourse/woowacourse-docs/blob/master/maincourse/README.md)

## 🚀 기능 구현 목록
- 각 자동차의 이름을 입력받는다.
  - 자동차 이름은 쉼표(,)를 기준으로 구분한다. 
  - 이름은 5자 이하만 가능하다.
- 레이싱할 횟수를 입력받는다.
  - 횟수는 1이상 이어야한다.
- 입력받은 횟수만큼 레이싱을 시작한다.
  - 0에서 9 사이에서 random 값을 구한 후 random 값이 4 이상일 경우 전진하고, 3 이하의 값이면 멈춘다.
  - 매 라운드마다 자동차 이름과 이동한 거리를 같이 출력한다.
- 레이싱이 완료된 후 우승자를 정한다.
  - 우승자는 한 명 이상일 수 있다.