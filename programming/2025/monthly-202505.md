# 2025-05

## 🌿 List
- 개인 프로젝트
    - [ZibNote 백엔드] [ZibNote_Backend](https://github.com/sshyuny/ZibNote_Backend)
    - [ZibNote 프론트엔드] [ZibNote_Frontend](https://github.com/sshyuny/ZibNote_Frontend)
- [개발 블로그] [Blog](https://sshyu.tistory.com/)
- [코딩테스트 준비] [CodingTestTraining](https://github.com/sshyuny/CodingTestTraining)

## 🌿 Daily Log

### 250501 Thu
- [ZibNote 백엔드]
    - refactor: Member 이름 필요시 직접 쿼리에서 조회하도록 변경(기존 세션 사용)
    - (feat: JWT 적용)

### 250502 Fri
- [ZibNote 백엔드]
    - feat: JWT 적용
    - chore: JWT 적용으로 인한 Swagger 설정 추가 및 테스트코드 수정

### 250507 Wed
- [ZibNote 백엔드]
    - chore: CORS 설정 변경 - 필터 방식으로 변경
- [ZibNote 프론트엔드]
    - refactor: api 요청 공통 컴포넌트 분리
    - refactor: JWT 토큰 localStorage로 처리
- [개발 블로그]
    - [스프링의 CORS 처리 방법 정리](https://sshyu.tistory.com/49)

### 250508 Tue
- [ZibNote 백엔드]
    - docs: 일괄 정리
    - chore: CORS 허용 설정 - 필터 수동 등록 방식으로 적용 해보고, 다시 CorsRegistry 등록 방식으로 변경

### 250509 Fri
- [ZibNote 백엔드]
    - (feat: SearchStructureNote 서비스 등록/조회/수정 기능 개발)

### 250510 Sat
- [ZibNote 백엔드]
    - feat: SearchStructureNote 서비스 등록/조회/수정 기능 개발

### 250512 Mon
- [ZibNote 백엔드]
    - chore: Service 메서드 JavaDoc  주석 추가
    - refactor: JPA 엔티티에 ref 메서드 추가 및 리팩토링
    - refactor: 도메인 모델에 onlyId 메서드 추가 및 리팩토링
    - refactor: 변수에 final 일괄 추가
    - docs: CODE_CONVENTION 작성, README 수정

### 250513 Tue
- [ZibNote 백엔드]
    - refactor: 컨트롤러 DTO @Builder 제거 및 사용 어노테이션 정리
    - test: TestFixture 사용

### 250514 Wed
- [ZibNote 백엔드]
    - refactor: Service의 register 메서드 ID 반환하도록 리팩토링
    - SearchService/SearchStructureService 단위테스트 보강, 통합테스트 작성

### 250515 Thu
- [ZibNote 백엔드]
    - test: TestFixture 메서드명 리팩토링 및 파일명 변경
    - test: NoteFiled/Structure에서 Service 단위테스트 보강, 통합테스트 작성

### 250516 Fri
- [ZibNote 백엔드]
    - refactor: 예외 클래스 구조 개선
    - refactor: 응답 코드 Enum 적용 및 응답 메시지 Enum 활용

### 250520 Tue
- [ZibNote 백엔드]
    - refactor: 도메인 모델 팩토리 메서드 생성
    - test: TestFixture 팩토리 메서드 리팩토링

### 250523 Fri.
- [ZibNote 백엔드]
    - refactor: Controller 및 ControllerAdvice 보완
    - test: Controller WebMvcTest 테스트 보완 및 작성

### Weekly (250526 ~ 250601)
#### ⏰ Plan
#### 📝 Evaluation

#### 250526 Mon
- [ZibNote 백엔드]
    - refactor: SearchStructureNote 엔티티 PK를 UUID로 변경

#### 250527 Tue
- [ZibNote 백엔드]
    - refactor: SearchStructure 엔티티 PK를 UUID로 변경
    - refactor: Seaech 엔티티 PK를 UUID로 변경
