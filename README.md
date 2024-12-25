# 스프링 DB 2편 - 데이터 접근 활용 기술

### 2024/12/23 : 데이터 접근 기술-시작 
- 진행할 프로젝트 설정 및 구조 파악
- 스프링 @Profile 개념 학습
- 의존관계 자동 주입 복습

### 2024/12/24 : 데이터 접근 기술 - 스프링 JdbcTemplate

- 스프링 JdbcTemplate을 H2에 적용 및 구조 파악 
- 이름 지정 파라미터 바인딩 기법 : Map, SqlParameterSource(BeanPropertySqlParameterSource, MapSqlParameterSource)
- SQL를 바탕으로 객체를 반환해주는 기법 : BeanPropertyRowMapper
- INSERT SQL를 자동으로 생성해주는 기법 : SimpleJdbcInsert

### 2024/12/25 : 데이터 접근 기술 - 테스트

- 테스트를 위한 데이터베이스 분리 
- 테스트의 격리성을 위한 트랜잭션 도입 
- 테스트 트랜잭션 자동화 : @Transactional 
- 스프링 부트에서 임베디드 모드 DB(H2) 실행 
