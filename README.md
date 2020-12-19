# 🚇 지하철 노선도 경로 조회 미션
- 등록된 지하철 노선도에서 경로를 조회하는 기능을 구현한다.

## 🛠 기능 구현 목록
1. 초기화된 데이터를 바탕으로 다익스트라 객체를 생성한다
    - 최단경로와 최소시간 각각을 기준으로 하는 객체 두 개를 생성한다
1. 출발역과 도착역을 입력받는다
    - [예외] 입력된 출발역과 도착역이 2글자 미만인 경우
    - [예외] 존재하지 않는 역을 출발역 또는 도착역으로 입력하는 경우
    - [예외] 입력된 출발역과 도착역이 동일한 경우
    - [예외] 경로 조회 시 출발역과 도착역이 연결되지 않는 경우
1. 최단거리와 최소시간 중 어떤 것을 기준으로 할 것인지 입력받는다
1. 다익스트라 알고리즘으로 최단거리(혹은 최소시간) 루트를 찾는다
1. 결과를 출력한다
    - 총 거리와 총 소요 시간을 함께 출력한다