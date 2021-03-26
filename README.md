# ExTestGit

## a. 프로젝트 명
### STS19_REST

<br>

---
## b. 프로젝트에 사용된 기술소개
### 1. 게시판 CRUD
> CRUD : Create(생성), Read(읽기), Update(갱신), Delete(삭제)

    게시판에서 글 목록을 조회할 수 있고 글을 작성, 조회, 수정, 삭제를 할 수 있다.

<br>

### 2. REST
> Representational State Transfer

    하나의 URI 는 → 하나의 고유한 리소스   를 갖도록 설계된 아키텍쳐.
    '특정 URI' 를 통해 사용자가 원하는 정보 제공받는 형식
    이와 같이 REST 방식으로 서비스제공이 가능한것을 RESTful 하다 라고 표현한다.

<br>

### 3. AJAX SPA게시판
    JSON의 형태로 출력되는 게시판이다.
    단일페이지로 구성되어 있으며 JavaScript를 사용해 비동기식으로 서버에 데이터를 요청한다.
    단순하게 WEB화면에서 무언가 부르거나 데이터를 조회하고 싶을 경우, 페이지 전체를 새로고침하지 않고 사용할 수 있다.
    기본적으로 웹 애플리케이션에 필요한 모든 정적 리소스를 최초에 한번 다운로드한다.
    그래서 웹페이지의 속도가 향상 된다.

<br>

---
## c. 프로젝트 셋업에 관한 절차 
### 1. UTF-8 인코딩
    window → Preference에서 workspace, jsp 등의 인코딩을 UTF-8로 맞춰주세요!!
> 왼쪽 상단 검색창에 encoding 을 입력하면 더 빠르게 변경 가능합니다!

<br>

### 2. Git Clone하기
    >>window → perspective → open perspective → git<<
    - 왼쪽 창 Git Repositories에서 Clone a Git repository 클릭!!
    - GitHub 주소 넣고 Authentication에 User와 Password 작성하세요
    - Next → 저장할 디렉토리 확인 후 Finish.

<br>

### 3. 프로젝트 Import해오기
    >>window → perspective → open perspective → spring<<
    - 왼쪽 창 Package Exploerer에서 오른쪽 마우스 클릭 후 Import 클릭!!
    - Maven → Existing Maven Projects → Next
    - Root Directory에서 Browes...를 눌러 2번에서 저장한 디렉토리 불러오기 → Finish.

<br>

### 4. DB와 서버 연결하기
>이 프로젝트는 Oracle과 Tomcat v9.0으로 진행되었습니다.
