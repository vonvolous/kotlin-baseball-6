### ☀️ 구현할 기능 목록

* 게임 시작 문구 출력
    - 예시) 숫자 야구 게임을 시작합니다.
<br><br>
* 컴퓨터 수 랜덤 생성
    - 1에서 9까지 서로 다른 임의의 수 3개를 선택
<br><br>
* 사용자 값 입력 받기
    - 게임 플레이어는 서로 다른 3개의 숫자 입력
    - 잘못된 값 입력시 IllegalArgumentException 을 발생시킨 후 애플리케이션 종료
<br><br>
* 사용자가 입력한 값에 대한 결과 출력
    - 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼, 같은 수가 전혀 없으면 낫싱
    - 과정을 반복하여 컴퓨터가 선택한 3개의 숫자 모두 맞히면 게임 종료
      -- 출력 예시)
        - 1볼
        - 1스트라이크
        - 1볼 1스트라이크
        - 낫싱
        - 3스트라이크
          3개의 숫자를 모두 맞히셨습니다! 게임 종료
<br><br>
* 종료 조건
    - 이때 게임을 종료한 후 다시 시작하거나 완전히 종료 가능
    - 예시) 게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.