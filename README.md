 ![image](https://github.com/user-attachments/assets/bddeff83-4b2f-4718-8bf0-798ec9661b5c)

# All Live Young WMS README


<br>

## 팀명 소개

- All   +  Live   +  榮
- 의약품 WMS의 구축을 통해 모든 이들이 아프지 않고 젊고 꽃다운 인생을  살게 하고픈 목적을 가진 이름

## 프로젝트 소개 및 주제 선정 이유

- 이번에 참여하게된 프로젝트는 의약품 창고의 원활한 유통 관리를 위한 WMS을 구현한 프로젝트입니다.
- 2019년에 COVID-19가 유행하며 현재까지도 확진자 발생했습니다.
- 23년 5월 5일 WHO에서는 공중보건 비상사태를 해제하였고, 확진자 수는 지속적인 완화세를 보였습니다.
- 그러나 재 유행으로 인해 국내 및 해외 증상 관련 약품들이 부족한 현상 발생하였습니다.
- 따라서 의약품 재고 및 유통 관리 창고관리시스템(WMS)을 주제로 선정하게 되었습니다.

<br>

## 팀원 구성 및 소개

<div align="center">

| **AAA** | **BBB** | **CSM0837** | **CCC** | **DDD** |
| :------: |  :------: | :------: | :------: | :------: |
| 팀장 | 팀원 | 침원 | 팀원 | 팀원 |
| 재고 관리, 창고 관리 | 재무 관리, 대시보드, Security | 회원 관리, 고객센터 | 입고 관리 | 출고 관리 |


</div>

<br>

## 1. 개발 환경

- Front : HTML5, CSS3, JavaScript(ES6), Bootstrap
- Back-end : Java(17), Spring Boot(3.3.4), Mybatis(3.0.3), Spring Security, ThymeLeaf, JUnit5, MySQL(8.0.21)
- 형상관리 : Github
- 개발도구 : IntelliJ, Visual Studio, Mysql Workbench
- 협업도구 : Notion, Slack, Google Docs, Google Sheet, Zoom
<br>

## 2. 프레임워크

#### Mybatis(3.0.3)
- JPA와 달리 SQL 쿼리를 직접 작성할 수 있어 개발자들이 데이터베이스를 쉽게 다룰 수 있는 ORM(Object-Relational Mapping)입니다.
- 동적 쿼리 작성이 가능합니다. 여러 입고 요청 상품을 동적으로 입력 받는 데에 적합합니다.
- SQL 쿼리와 Java 코드를 분리하여 관리할 수 있기 때문에 유지보수 측면에서 좋은 프레임워크입니다.

#### Spring Boot(3.3.4)
- Spring Java 애플리케이션 개발을 편하게 할 수 있게 해주는 오픈소스 경량급 애플리케이션 프레임워크입니다.
- Spring Boot는 Spring의 설정을 간편하게 처리해주는 프레임워크입니다.
- 1차 프로젝트는 프레임워크의 사용없이 프로젝트를 구현했으나 2차 프로젝트에서는 스프링부트를 채택하여 구현해보기로 하였습니다.
  

## 3. 브랜치 전략 및 컨벤션

#### Git-Flow 
<img src="https://github.com/user-attachments/assets/20e204d6-6057-4af3-b2e6-27a78edf39a4" height=300px>

- Git-Flow 전략을 채택하였고 main, develop, feature 브랜치를 사용하였습니다.
    - main 브랜치는 배포 용도로 사용하였습니다. 이 때 hotfix & release 브랜치는 실제 서비스 제공을 하지 않아 활용하지 않았습니다.
    - develop 브랜치는 feature 브랜치들을 병합하는 브랜치로 활용하였습니다.
    - feature 브랜치는 각각 기능 별로 생성하여 분리 작업을 진행하였습니다.
<br>

#### 네이밍 컨벤션
- 변수 및 메서드명: camel Case
- 클래스명: Pascal Case
- 패키지 및 테이블 컬럼명: snake case

## 4. 프로젝트 구조
<img src="https://github.com/user-attachments/assets/aef15a58-8a6c-409f-a81f-340e7b9b47f9" height=200px>

- 설정 클래스를 담은 config
- 상수를 정의한 constant
- 도메인 객체를 정의한 domain
- 예외 처리를 담당하는 exception
- mapper 인터페이스를 선언한 mapper
- 비즈니스 로직을 처리하는 service
- 클라이언트의 요청을 처리하는 controller
- 필요한 데이터를 담아 보내주는 dto

<br>

## 5. 프로젝트 기간

### WBS

![image](https://github.com/user-attachments/assets/a862aec8-af41-4b32-a8c5-48a71c3870c8)

<br>

## 6. 회원관리 / 고객센터

#### 대시보드
<img width="808" alt="image" src="https://github.com/user-attachments/assets/447ddb0c-bbd0-46c9-a435-f9aad593e825">

#### 회원가입 화면(다음 주소 API 사용)
![image](https://github.com/user-attachments/assets/15802782-297e-4335-b2d5-4b45e77efad1)


####회원가입 성공 화면
<img width="718" alt="image" src="https://github.com/user-attachments/assets/b8a15813-c3bf-4038-8611-ee9560af4c23">

####로그인 화면
![image](https://github.com/user-attachments/assets/ec88944a-5008-4fbe-ad8b-05653703f7f7)

####회원 목록 조회(관리자 기능)
![image](https://github.com/user-attachments/assets/8f28ad80-9fc8-488b-a83e-edd2adecb07a)

####회원 상세 조회(관리자 기능)
![image](https://github.com/user-attachments/assets/cac21d39-28f2-497b-9060-8de55e7e5ef2)

####회원가입 승인 요청 목록 조회(관리자 기능)
![image](https://github.com/user-attachments/assets/55fa4f4d-0257-4f3c-9620-2e747c5d8fb1)

####회원가입 승인 요청 상세  조회(관리자 기능)
![image](https://github.com/user-attachments/assets/e50c2909-7952-4bf8-b8d2-de1224fd6096)

####회원가입 승인 탈퇴 목록 조회(관리자 기능)
![image](https://github.com/user-attachments/assets/2544cd7d-2a87-464c-803c-f5b752de78bd)

####회원가입 승인 탈퇴 상세 조회(관리자 기능)
![image](https://github.com/user-attachments/assets/b1dc254e-43e3-4a60-a403-ec3d291c0fe4)


####나의 정보 조회(마이페이지)
![image](https://github.com/user-attachments/assets/29da9949-6245-45bc-9a9b-2720aa64d152)

####나의 정보 수정(마이페이지)
![image](https://github.com/user-attachments/assets/109ba23c-49ea-4a7e-be69-3295ec966847)

####공지사항 목록
https://github.com/user-attachments/assets/0b7ed6b7-10e6-499a-ace7-55350dae5096

####공지사항 상세 조회
![image](https://github.com/user-attachments/assets/9b9b7191-8fc5-4797-bfb6-14f516209073)

####공지사항 작성
![image](https://github.com/user-attachments/assets/9fda2454-2df7-4e7b-a92c-5ef9c6148d65)








 

[상세 기능](https://velog.io/@ybinn99/2%EC%B0%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%9D%98%EC%95%BDWMS-%EC%9E%85%EA%B3%A0-%ED%8C%8C%ED%8A%B8-%EA%B8%B0%EB%8A%A5)
해당 링크에서 입고 상세 기능을 확인하실 수 있습니다.

<br>

## 7. . 개선 목표

- 스프링 시큐리디 보완
    - 기능구현을 우선으로 하다보니, 회원의 상태 권한 등 검증조건을 더 추가하여, 회원정보 유지, 접근권한 부여 및 상세 제어되는 부분을 개선할 예정입니다.
- 1:1 문의 기능 구현
    - 1:1 문의 기능에서 문의글과 그에 따른 답변에 대해 작성, 수정 삭제가 모두 이루어 져야 해서 기능 구현이 부족했습니다. 이 부분 구현하여 개선할 예정입니다.
<br>

## 8. 관련 링크
[ERD](https://www.erdcloud.com/d/E6iQPxSRmuLZqKYCT)


## 9. 프로젝트 후기 및 회고록
