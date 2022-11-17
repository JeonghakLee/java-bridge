# 다리 건너기

## 기능 목록
- [ ] 게임 시작 문구를 출력한다.
- [ ] 생성할 다리의 길이를 숫자로 입력 받는다.
    - [ ] 다리 길이 입력 요청 문구를 출력한다.
    - [ ] 숫자가 아닌 입력은 예외를 처리한다.
- [ ] 위 아래가 두 칸으로 이루어진 다리를 생성한다.
    - [ ] 위 칸과 아래 칸 중 건널 수 있는 칸을 무작위 값(0 또는 1)을 이용해서 정한다.
    - [ ] 위 칸을 건널 수 있는 경우 U, 아래 칸을 건널 수 있는 경우 D값으로 나타낸다.
- [ ] 다리의 칸을 이동한다.
    - [ ] 이동할 칸 입력 요청 문구를 출력한다.
    - [ ] 사용자로부터 이동할 칸을 입력받는다.
    - [ ] U 또는 D 이외의 입력 값은 예외를 처리한다.
    - [ ] 사용자의 입력과 다리를 비교한다.
    - [ ] 다리 건너기 결과를 출력한다.
    - [ ] 종료 조건을 만족할 때까지 이동을 반복한다.
- [ ] 다리를 끝까지 건너면 게임을 종료한다.
    - [ ] 이동한 칸이 건널 수 없는 칸이면 사용자의 입력에 따라 게임을 재시작하거나 종료한다.
        - [ ] 게임의 재시작/종료 요청 문구를 출력한다.
        - [ ] 게임 재시작/종료 여부를 입력 받는다.
        - [ ] R(재시작)과 Q(종료) 중 하나의 문자를 입력할 수 있다.
        - [ ] R 또는 Q외의 입력은 예외를 처리한다.
        - [ ] 재시작 시 게임의 시도 횟수를 갱신한다.
- [ ] 최종 게임 결과를 출력한다.
    - [ ] 게임 성공 여부를 출력한다.
    - [ ] 총 시도한 횟수를 출력한다.