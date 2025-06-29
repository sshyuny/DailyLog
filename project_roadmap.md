# 🛠️ 개인 프로젝트 로드맵

- [어플리케이션 웹사이트 링크](https://sshyu.com)
- [Backend Git Repository](https://github.com/sshyuny/ZibNote_Backend)
- [Frontend Git Repository](https://github.com/sshyuny/ZibNote_Frontend)
- [프로젝트 개발 기록 블로그](https://sshyu.tistory.com/category/personal-project)


## 1. Infrastructure

### Server
-  Linux Server 구축
    - Window 노트북에 Ubuntu를 멀티 OS로 설치하여 어플리케이션 서버로 사용
- Middleware (Nginx) 설정
    - 앞 단에서 백엔드와 프론트엔드 어플리케이션 요청 관리
- 도메인 연결
    - 해당 IP를 sshyu.com과 연결
- 방화벽 및 포트 관리
    - 443, 80 포트 허용

### CICD 구축
- Jenkins로 서버에 어플리케이션 배포
    - 로컬 노트북에 Jenkins 설치하여 백엔드와 프론트엔드 프로젝트 서버에 배포


## 2. Backend Application

### 🧱 Architecture & Convention
- 계층 구조 설계
    - Hexagonal Architecture 적용
- Code Convention 정립

### 🗃️ Domain & Schema
- ERD 설계 및 DB 모델링
- JPA 및 MyBatis 적용 설정
- 테이블 생성

### 🔐 인증 / 인가
- JWT 적용
- 소셜 로그인 연동 (카카오 / 네이버 등)

### 🔄 API 개발
- CRUD 기능 개발
- Validation / 예외 처리
- API 응답 포맷 통일
- Swagger API 문서화

### 🧪 Test
- 단위 테스트 (Service, Domain)
- 통합 테스트 (Controller, Repository)

### ⚙️ 도메인 문제 해결


## 3. 운영 고려사항


## 4. Frontend Application

### 🧱 Architecture & Convention
- 디렉토리 구조 설계
- 상태 관리 방식 선택(useSWR, mutate)
- API 요청 공통 함수 개발

### 💻 화면 구성
- 기본적인 화면 마크업

### 🔗 API 연동
- 백엔드 API와 통신 구현 (GET/POST/DELETE)
- JWT 기반 인증 헤더 설정



---

## TO DO LIST
1. Infrastructure
    - Server
        - [ ] HTTPS 설정
    - CICD
        - [ ] 빌드 & 배포 자동화
        - [ ] GitHub Actions
2. Backend Application
    - Architecture & Convention
        - [ ] 공통 유틸 / 에러 핸들링 / 로깅
    - Domain & Schema
        - [ ]마이그레이션 관리
    - Test
        - [ ] 테스트 데이터 관리
    - 도메인 문제 해결
        - [ ] 선착순 쿠폰 처리 전략
        - [ ] 재고 동시성 처리 전략
        - [ ] 분산락 / 이벤트 기반 처리 설계
        - [ ] 정합성 보장 방안 (예: 트랜잭션, 메시지 큐 등)
3. 운영 고려사항
    - [ ] 성능 최적화 (캐시, 비동기 처리 등)
    - [ ] 보안 이슈 대응 (XSS, CSRF, CORS 등)
    - [ ] 모니터링 / 로그 수집
    - [ ] 배포 전략 (무중단 배포, Blue-Green 등)
4. Frontend Application
    -  화면 구성
        - [ ] 반응형 / 접근성 고려
    -  API 연동
        - [ ] 로딩 / 에러 처리 UX
