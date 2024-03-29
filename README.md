주제는 제가 평소에 자주먹고 맛있어하는 하남돼지로 선정하였고, 이에 따른 데이터베이스를 구축해보자고 계획을 잡아 보았습니다.

- **어렸을 때부터 고기를 정말 좋아했어요. 고기를 적절히 잘 먹는다면 오히려 단백질 보충 및 체중 관리를 위해 돼지고기가 필수라고 생각해요.**
- DB구성
  - 매니저, 알바, 사장, 고기관리 테이블을 자세히 구성했어요.
  - 가게를 체계적으로 관리 할 수 있어요.
  - 고기, 음식들에 칼로리 정보를 기입 해 놓았어요.
  - 칼로리에 예민한 시대잖아요? 칼로리 정보를 기입해 놓는다면 소비자들이 안심하고 편하게 먹을 수 있을 것 같아요.
- 어려웠던 점
  - 테이블을 구성하고 원하는 값을 출력하는 과정에서 반복되는 오류를 발견했어요. 특히, 외래키 관련하여 데이터 무결성을 준수하지 못한 케이스가 발견되었고, 이를 해결하기 위해 외래키의 속성을 명확히 지정해주었어요. 이를 통해 데이터베이스의 일관성과 무결성을 강화하고 문제를 해결할 수 있었어요.
- 느낀점
  - DB설계과정에서 요구사항분석, 개념적설계, 논리적설계, 물리적설계 전부 중요하다고 생각이 되었어요. 특히 ER다이어그램을 정확하게 그려야 나중에 설계할 때 많은 도움이 될거라고 생각했고, 조금 더 꼼꼼히 설계를 해야겠다고 느꼈어요.

https://dinoqos.tistory.com/5

**자세한 내용은 블로그에 있습니다.**
