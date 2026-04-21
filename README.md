<h1 align="center">Jaeseop Kim <sub>(KoreaNirsa)</sub></h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-111827?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-111827?style=flat-square&logo=springboot&logoColor=6DB33F" />
  <img src="https://img.shields.io/badge/Spring%20Security-111827?style=flat-square&logo=springsecurity&logoColor=6DB33F" />
  <img src="https://img.shields.io/badge/JPA%20%2F%20MyBatis-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/AWS-111827?style=flat-square&logo=amazonaws&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=FCC624" />
</p>

<h3 align="center">System Engineer · Backend Engineer · Technical Instructor</h3>

<p align="center">
  <a href="https://nirsa.tistory.com">Tech Blog</a> ·
  <a href="https://github.com/KoreaNirsa">GitHub</a>
</p>

---

## Focus

| Position | What I do |
|---|---|
| **System Engineer** | Linux, Docker, AWS, 로그/모니터링, 온프레미스 기반 인프라 운영 |
| **Backend Engineer** | Java/Spring Boot 기반 REST API, 인증/인가, 데이터 처리, 응답·예외 구조 설계 |
| **Technical Instructor** | Java/Spring/React/AWS 과정 설계 및 강의, 프로젝트 코드리뷰 및 ERD/QA 피드백 |

---

## Engineering Philosophy

> “확장성만을 위한 설계”, “최신 기술만을 쫓는 설계”가 아니라 “요구사항에 맞는 적절한 설계”를 지향합니다.

- 기술 선택은 트렌드가 아닌 문제 적합성을 기준으로 합니다.
- 과도한 추상화와 오버엔지니어링을 지양합니다.
- 단순하지만 확장 가능한 구조를 선호합니다.
- 최신 기술은 신중하게 검토하되, **지속적으로 학습하고 검증하여 필요한 시점에 적용합니다.**
---

## Tech Focus

| Area | Stack |
|---|---|
| **Backend** | Java, Spring Boot, REST API, JPA, MyBatis |
| **Security** | Spring Security (JWT, Password Encoding, CORS), Network / System Security |
| **Database** | MySQL, Oracle, ERD Modeling |
| **Infra / Ops** | Linux, Docker, AWS, Nginx, Tomcat, Bash |
| **Quality** | Git/GitHub, Swagger, JUnit, Mockito, MockMvc |
| **Monitoring** | Zabbix, Grafana, rsyslog |
| **AI / Automation** | OpenAI API, FastAPI(LLM), LangChain(RAG), Spec-Driven Development |
---

## Highlights

- **2025 전자정부 표준프레임워크 컨트리뷰션 소스코드 개선 부문 최우수상 · 행정안전부장관상**
- **Spring AI / eGovFrame 오픈소스 기여**: 리팩토링, API 구조 개선, 문서화, 테스트 보완
- **기술 블로그 운영**: Java, Spring, Linux, Docker, Infra 트러블슈팅 중심 정리 · 누적 조회 200만+

---

## Selected Work

| Project | Summary | Backend Focus |
|---|---|---|
| [Specyn](https://github.com/KoreaNirsa/specyn) | Spec 기반 Multi-Agent AI 개발 자동화 플랫폼 | Spec → Code → Test → Contract Validation → Harness 자동화 |
| CodeArena | 사용자 참여형 알고리즘 문제 플랫폼 | Spec Kit 기반 SDD 구조 설계, 문제 생성·채점·랭킹 도메인 설계 및 개발 |

---

## Open Source

| Project | Contribution |
|---|---|
| [Spring AI](https://github.com/spring-projects/spring-ai) | OpenAI API Builder 리팩토링, null 체크 정리, 문자열 처리 최적화, JavaDocs 보완 |
| [eGovFrame Backend](https://github.com/eGovFramework/egovframe-template-simple-backend) | 게시판 API 구조 개선, Swagger 문서화, 응답 구조 리팩토링, 테스트 보완 |
| [eGovFrame React](https://github.com/eGovFramework/egovframe-template-simple-react) | 백엔드 응답 구조 변경 대응, 상태 관리 및 API 연동 구조 개선 |

<details>
<summary><strong>Selected Pull Requests</strong></summary>

### Spring AI

- [spring-ai #3654](https://github.com/spring-projects/spring-ai/pull/3654) : [Refactor] Remove redundant null check in OpenAiApi.Builder#apiKey(String)
- [spring-ai #3663](https://github.com/spring-projects/spring-ai/pull/3663) : Refactor: Add null check, optimize string joining, and add JavaDocs

### eGovFrame Backend

- [egovframe-template-simple-backend #72](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/72) : Fix(bbs): pageIndex 파라미터 처리 누락 이슈 해결
- [egovframe-template-simple-backend #73](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/73) : Refactor(bbs): 게시판 관리 컨트롤러 및 공통 유틸 개선
- [egovframe-template-simple-backend #74](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/74) : Refactor(EgovBBSAttributeManageApiController) : 요청/응답 구조 개선 
- [egovframe-template-simple-backend #78](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/78) : Refactor(bbs) : 패키지 구조 개선 및 Controller 책임 분리
- [egovframe-template-simple-backend #79](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/79) : Refactor(bbs): swagger 명확화, 구조 개선 및 버그 수정
- [egovframe-template-simple-backend #80](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/80) : Refactor(bbs): 게시글 삭제(deleteBoardArticle 메서드) 구조 변경 
- [egovframe-template-simple-backend #81](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/81) : Refactor(bbs): selectBBSMasterInf 응답 구조 로직 리팩토링 및 테스트 보완 
- [egovframe-template-simple-backend #82](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/82) : Refactor(bbs): 게시판 마스터 상세 내용(파일첨부) 조회 메서드 Swagger 문서 보완 및 API 응답 구조 리팩토링
- [egovframe-template-simple-backend #85](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/85) : Refactor(bbs): Refactor(bbs): selectBoardArticles 응답 구조 정리
- [egovframe-template-simple-backend #87](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/87) : Refactor(bbs): 게시물 상세 목록 조회 구조 개선
- [egovframe-template-simple-backend #93](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/93) : Refactor(bbs): Feature(resources-db): bbs 공지사항 및 사이트갤러리 샘플 데이터 추가
- [egovframe-template-simple-backend #94](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/94) : Refactor(bbs): refactor(bbsManage-updateBoardArticle) : JWT 유틸 분리, 파일 업로드 서비스 이전, 스웨거 호환
- [egovframe-template-simple-backend #108](https://github.com/eGovFramework/egovframe-template-simple-backend/pull/108) : docs: 리드미 참고 문서 리스트 반영 및 DB 스키마 가이드 추가 

### eGovFrame React

- [egovframe-template-simple-react #67](https://github.com/eGovFramework/egovframe-template-simple-react/pull/67) : Feat(admin.notice) : 어드민 공지사항 게시글 삭제 시 atchFileId 포함하여 API 호출하도록 수정
- [egovframe-template-simple-react #68](https://github.com/eGovFramework/egovframe-template-simple-react/pull/68) : Refactor(EgovAdminBoardEdit): 백엔드 응답 구조 변경에 따른 setBoardDetail 호출 방식 수정
- [egovframe-template-simple-react #69](https://github.com/eGovFramework/egovframe-template-simple-react/pull/69) : Refactor(admin.notice): 백엔드 응답 구조 변경에 따른 응답 상태관리 수정
- [egovframe-template-simple-react #70](https://github.com/eGovFramework/egovframe-template-simple-react/pull/70) : Refactor(board): textarea 입력 이벤트를 onChange에서 onBlur로 변경
- [egovframe-template-simple-react #74](https://github.com/eGovFramework/egovframe-template-simple-react/pull/74) : Fix(mobile-menu): 모바일 메뉴에서 '사이트 관리' 메뉴 토글이 정상 동작하지 않던 문제 수정
- [egovframe-template-simple-react #87](https://github.com/eGovFramework/egovframe-template-simple-react/pull/87) : Refactor(notice, gallery): 백엔드 로직 변경으로 인한 파일 첨부 변경 

</details>

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KoreaNirsa&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="165" />
  <img src="https://streak-stats.demolab.com?user=KoreaNirsa&theme=tokyonight&hide_border=true" height="165" />
</p>

---

## Contact

- Email: [islandtim@naver.com](mailto:islandtim@naver.com)
