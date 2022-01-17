
# Spring Data JPA 학습 간 알게 된 내용 정리

## Settings
- p6spy 라이브러리 : jpa 쿼리에서 파라미터에 어떤 값이 찍히는지 
좀 더 눈에 잘 들어오게 찍어주는 라이브러리..!

---
### LAZY Loading
- 연관관계가 있는 도메인에서 직접 해당 도메인을 조회하기 전까지 프록시 객체로
만들어두기만 하는 로딩 기법 (스터디 때 했던 내용 재정리)


### 쿼리 메서드 기능
- 조회 : find..By , read..By , get.. By
- 카운트 : count .. By 반환타입
- Exists : exists .. By 반환타입
- 삭제 : delete ..By, remove..By 반환 타입
- DISTINCT : findDistinct, findMemberDistinctBy
- LIMIT : findFirst3 , findFirst, findTop, findTop3