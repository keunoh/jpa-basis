🔮starts with jpa basis🔧

- 양방향 매핑 정리
  - 단방향 매핑만으로도 이미 연관관계 매핑은 완료
  - 양방향 매핑은 반대 방향으로 조회(객체 그래프 탐색) 기능이 추가된 것 뿐입니다.
  - JPQL에서 역방향으로 탐색할 일이 많음
  - 단방향 매핑을 잘 하고 양방향은 필요할 때 추가해도 됨(테이블에 영향을 주지 않음)
  - 단방향으로 애플리케이션을 개발해도 전혀 문제가 없다. 그렇지만 실전은 항상 예외가 있으니 경험을 많이 해야한다. JPQL을 짜게 되면 양방향 연관관계가 필요하기 때문이다. 즉, 할 수 있으면 최대한 단방향매핑을 기준으로 하라
  - 🎇핵심 -> 단방향 설계 먼저 잘하기