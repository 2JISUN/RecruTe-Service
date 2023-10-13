# 채용 관리 서비스 - RecruTe

과제 수행을 통한 학습을 목적으로 진행하는 프로젝트입니다.

## 📋 프로젝트 소개

RecruTe는 기업들의 채용 프로세스를 대신 진행해주는 채용관리 플랫폼입니다.

제공하는 핵심 서비스는 다음과 같습니다.

-   채용공고 사이트 제공 및 관리
-   지원자 개인정보 관리
-   일정 안내 메일 발송
-   기업별로 진행되는 테스트 환경 제공

## 📝 시나리오

1. 모집공고 웹 페이지에서 지원자의 개인정보 입력을 통해 채용에 대한 지원을 받음
2. 지원자가 수십만 명이 몰린 상황
3. 지원자에 대한 정보를 조회해 시험 응시 페이지 링크를 포함한 이메일을 발송함
4. 지원자는 정해진 시간에 응시 페이지에 접속해 시험을 응시함

## 🛠️ 기술 스택

-   [ ] Java
-   [ ] MySql
-   [ ] Tomcat
-   [ ] MyBatis
-   [ ] Redis
-   [ ] nGrinder

## 🔥 수행 과제

### 필수 과제

-   [ ] **Mission 1.** 간단한 웹 페이제 설계 및 제작
-   [ ] **Mission 2.** 지원자에 대한 인증정보 처리
-   [ ] **Mission 3.** 수십만 명의 지원자에 대한 데이터 조회 성능 처리
-   [ ] **Mission 4.** 수십만 명의 지원자를 대상으로
        동시에 이메일 발송
-   [ ] **Mission 5.** 수십만 명의 지원자가 동시에 시험을 응시환경 구축

### 추가 과제

-   [ ] 코드 컨벤션 적용해보기
-   [ ] 테스트 코드 작성하기
-   [ ] 테스트 커버리지 적용해보기

## 🤷‍♂️ 진행 방법 및 규칙

프로젝트는 개인별로 진행하되, PR을 통해 서로에 대한 코드리뷰를 진행합니다.

1. 이 저장소를 fork 합니다.
2. 생성된 원격 저장소에 본인의 Github_ID와 동일한 폴더를 생성합니다.
3. 생성된 폴더에 자신의 프로젝트를 업로드 합니다.
4. 생성된 이슈와 프로젝트 계획에 따라 프로젝트를 진행합니다.
5. 진행사항을 원본 저장소의 develop 브랜치로 Pull Request 합니다.
6. 생성된 PR에서 자유롭게 코드리뷰를 합니다.

### Git 전략


-   `main`: 완성된 프로젝트를 최종적으로 배포하는 브랜치입니다.
-   `develop`: 개발이 진행되는 브랜치로 개발이 완료되면 main 브랜치로 병합합니다.
-   `feature`: 기능을 개발하는 브랜치로 feature/{name} 형식으로 작성하고, develop 브랜치로 병합합니다.

### Commit 규칙

-   Header, Body, Footer 으로 구성하며, 각 요소를 2번의 개행으로 구분합니다.
-   Header에는 커밋을 요약할 수 있는 타입과 제목을 작성합니다.
-   Body에는 상세 내용을 작성합니다.
-   Footer에는 Issue와 같은 참조 정보들을 작성합니다. (없다면 생략 가능)
-   영문자의 첫 글자는 대문자를 사용합니다.
-   어떻게보다 무엇과 왜를 설명합니다.
-   1개의 행위마다 1개의 커밋을 작성합니다.

### Commit 예제

```
Test: 지원자 데이터에 대한 DTO 매핑 테스트

조회한 지원자 데이터를 ApplicantDTO에 매핑하는 테스트 코드 작성

Issue: #1234
```

| 타입     | 내용                  |
| -------- | --------------------- |
| Feat     | 기능 정의             |
| Fix      | 버그 수정             |
| Chore    | 빌드, 설정을 포함하는 수정 |
| Style    | 코드 스타일 혹은 포맷 |
| Refactor | 리팩토링              |
| Test     | 테스트 코드           |
| Perf     | 성능 개선             |

### PR 규칙

-   1개의 작업마다 1개의 PR을 생성합니다.
-   생성된 이슈와 PR은 1대1 관계입니다.
-   만들어둔 PR 템플릿을 기반으로 충실히 작성합니다.
