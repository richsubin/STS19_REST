# A. 프로젝트 명
### STS19_REST
@RestController 와 MyBatis 를 사용한 REST게시판

# B. 프로젝트에 사용된 기술소개
#### Spring
  - version 5.2.1
  - Spring MVC Project
  - @RestController : 데이터를 response
#### JAVA
  - version 1.8
  - Bean을 활용 (DAO, DTO)
#### MyBatis
#### DB
  - **Oracle**
  - ER Diagram 제작시 ERMaster 라이브러리 사용
#### Tomcat
  + Apache 9.0
<br><br>
# C. 프로젝트 셋업에 관한 절차
### 협업자, clone

#### 이클립스 환경
1. workspace, 그 외 인코딩 UTF-8로 세팅
2. server 세팅
3. DB는 Oracle 사용함

### clone 받기

1. 이클립스 Window > Perspective > Git 을 open 한다
2. Git Perspective 에서 **Clone a Git repository**
3. clone할 프로젝트의 주소를 입력하고 **사용자**의 깃허브 아이디와 비밀번호를 입력한다
4. clone 할 위치, *워크스페이스* 를 선택한다
5. **Spring Perspective** 로 돌아온다
  <br>- import > Maven > Existing Maven Project

#### push 전에 최신버전으로 pull 먼저 해올 것
