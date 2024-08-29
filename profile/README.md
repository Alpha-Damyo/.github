# 🚬 2024-1 알파 프로젝트 담요 ( 담배는 요기서 )

## 기술문서
<table>
  <tr align="center">
    <td>
      프론트
    </td>
    <td>
      백
    </td>
  </tr>
  <tr align="center">
      <td>
          <a href="https://github.com/Alpha-Damyo/FE">FRONT.md</a>
      </td>
      <td>
          <a href="">BACK.md</a>
      </td>
  </tr>
</table>

<br>

## 1. 프로젝트 소개

해당 프로젝트는 흡연자들을 위해 근처 흡연구역 안내와 건강한 흡연문화를 위한 다양한 기능을 제공하는 서비스입니다.

<br>

## 2. Abstract

This project is a service that provides smokers with information on nearby smoking areas and offers various features to promote a healthy smoking culture.

<br>

## 3. 소개 영상
영상은 Youtube에서 고화질로 보실 수 있습니다.
[Youtube 링크](https://www.youtube.com/watch?v=5wS-LDVArWY)

https://github.com/user-attachments/assets/0f18cca6-4657-4e88-b150-28b5bf04fbbc

<br>

## 4. 프로젝트 기능

#### 1️⃣ 흡연구역 안내 지도
지도 위에 흡연구역들이 초록색 핀으로 표시되어있으며 각 핀을 터치하면 흡연구역 정보 카드가 나오게 됩니다. 카드를 터치하면 흡연구역 상세화면이 나오고 흡연구역에 대한 정보들을 확인할 수 있습니다.


|지도 화면|흡연구역 상세정보 화면|흡연구역 사진|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/4e82a5aa-5f2f-4e95-acc1-33e6e87c7ee1">|<img width="388" src="https://github.com/user-attachments/assets/f9d606eb-3524-4f0e-9e8e-d94521272bd1">|<img width="388" src="https://github.com/user-attachments/assets/a30b1c9d-1622-4552-bb0a-116dc9a4edc9">|
<br>

원하는 태그를 설정하여 검색할 수 있는 태그 검색 기능, 이름을 검색할 수 있는 검색어 검색 기능을 지원합니다.

|태그 검색 화면|검색어 검색 화면|즐겨찾기 화면|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/25877b47-a309-47b1-8394-934c5dd95e34">|<img width="388" src="https://github.com/user-attachments/assets/c0f4f1f6-96ef-4709-ab85-076fc2275465">|<img width="388" src="https://github.com/user-attachments/assets/f7c052b2-6971-45ef-8331-573237e1f590">|
<br>

담요에 없는 흡연구역이 있을 경우 이를 제보할 수 있습니다.

|제보할 위치의 지도 화면|흡연구역 정보 입력화면|제보가 반영된 지도 화면|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/62488bf5-9bc8-4cfa-8e27-95c3250dfc17">|<img width="388" src="https://github.com/user-attachments/assets/ecc0fb96-3bc7-48f3-ad3f-5cad64971a04">|<img width="388" src="https://github.com/user-attachments/assets/79beef64-df54-4ebd-8716-936e3e7bf47f">|
<br>

방문한 흡연구역에 대한 리뷰 작성, 정보 수정 제안, 흡연 완료를 진행할 수 있습니다.
|리뷰 작성 화면|정보 수정 제안 화면|흡연 완료 화면|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/58d9cdf8-d243-4b44-9687-99655072f773">|<img width="388" src="https://github.com/user-attachments/assets/8b4f511e-9b8e-483b-8945-c8979e8cbe85">|<img width="388" src="https://github.com/user-attachments/assets/8e3367a5-4ac6-41d0-b28c-1fa3cc170481">|

방문한 흡연구역을 즐겨찾기에 추가하고 관리할 수 있습니다.
|즐겨찾기 추가 화면|즐겨찾기 관리 화면||
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/bc5e194f-7d39-40eb-9279-23f7524e1590">|<img width="388" src="https://github.com/user-attachments/assets/36d7485e-a98e-47d7-a9ed-b504af9df773">|<img width="388">|

#### 2️⃣ 흡연데이터 통계
사용자가 가장 많이 방문한 흡연구역과 전체 사용자들이 가장 많이 방문한 흡연구역을 확인할 수 있습니다. 시간별 평균 흡연량, 기간별 평균 흡연량을 확인할 수 있습니다.
|가장 많이 방문한 흡연구역|시간별 평균 흡연량|기간별 평균 흡연량|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/403fe2ce-2841-434e-b769-45e3cd613bb7">|<img width="388" src="https://github.com/user-attachments/assets/1d2fb9a6-9d9c-4419-83b3-c32984bc4fba">|<img width="388" src="https://github.com/user-attachments/assets/93c8f174-e0f7-4d84-af79-83a953a8b1db">|
<br>

#### 3️⃣ 마이페이지 및 소셜로그인
마이페이지에서 로그인, 흡연데이터 초기화, 기여도 확인 등을 진행할 수 있습니다. 로그인은 구글, 네이버 2가지의 소셜 로그인을 지원합니다.
|로그인 페이지|로그인 후 마이페이지|기여도 페이지|
|---|---|---|
|<img width="388" src="https://github.com/user-attachments/assets/6a9c22f5-d936-48a8-81c6-bb5b564356ef">|<img width="388" src="https://github.com/user-attachments/assets/1b7f3fe9-97d6-45c8-aa88-682dfbf75512">|<img width="388" src="https://github.com/user-attachments/assets/e96fcd06-7cf7-4f9d-867e-32484361f9f5">|
<br>

## 5. 팀원 소개

<table>
    <tr align="center">
        <td style="min-width: 150px;">
            <a href="https://github.com/kevinmj12">
              <img src="https://avatars.githubusercontent.com/kevinmj12" width="100">
              <br />
              <b>김민제</b>
            </a> 
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="https://github.com/choichangyeon">
              <img src="https://avatars.githubusercontent.com/choichangyeon" width="100">
              <br />
              <b>최창연</b>
            </a>
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="https://github.com/ZombieBread123">
              <img src="https://avatars.githubusercontent.com/ZombieBread123" width="100">
              <br />
              <b>이현준</b>
            </a> 
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="https://github.com/BlueBerrySoda">
              <img src="https://avatars.githubusercontent.com/BlueBerrySoda" width="100">
              <br />
              <b>채원찬</b>
            </a> 
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="https://github.com/wjdwlghks">
              <img src="https://avatars.githubusercontent.com/wjdwlghks" width="100">
              <br />
              <b>정지환</b>
            </a> 
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="https://github.com/guahama">
              <img src="https://avatars.githubusercontent.com/guahama" width="100">
              <br />
              <b>최영락</b>
            </a> 
            <br/>
        </td>
        <td style="min-width: 150px;">
            <a href="">
              <img src="https://github.com/Alpha-Damyo/.github/assets/53148103/e882f67a-e259-4696-8469-ddc1d30386fa" width="100">
              <br />
              <b>최하영</b>
            </a> 
            <br/>
        </td>
    </tr>
    <tr align="center">
        <td>
            Frontend
        </td>
        <td>
            Frontend
        </td>
        <td>
            Frontend
        </td>
        <td>
            Backend
        </td>
        <td>
            Backend
        </td>
        <td>
            Backend
        </td>
        <td>
            Design
        </td>
    </tr>
</table>

<br>

## 6. 기술스택

### 🛠 Frontend

| 역할                 | 종류                                                                                                                                                                                                                                                |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Framework            | <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/> |
| Database             | <img alt="RED" src ="https://img.shields.io/badge/SQLite-003B57.svg?&style=for-the-badge&logo=SQLite&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Firebase-FFCA28.svg?&style=for-the-badge&logo=Firebase&logoColor=white"/> |
| Programming Language | <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>  |
| Device               | <img src="https://img.shields.io/badge/Android-4A853?style=for-the-badge&logo=Android&logoColor=white"/> <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=iOS&logoColor=white"/> |

<br />

### 💾 Backend

| 역할                 | 종류 |
| -------------------- | ------ |
| Framework            | <img alt="RED" src ="https://img.shields.io/badge/SPRING Boot-6DB33F.svg?&style=for-the-badge&logo=SpringBoot&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Spring Security-6DB33F.svg?&style=for-the-badge&logo=springsecurity&logoColor=white"/> |
| Database             | <img alt="RED" src ="https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Redis-DC382D.svg?&style=for-the-badge&logo=Redis&logoColor=white"/> |
| Programming Language | <img alt="RED" src ="https://img.shields.io/badge/JAVA-E29027.svg?&style=for-the-badge&logo=openjdk&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=python&logoColor=white"/> |
| Test                 | <img alt="RED" src ="https://img.shields.io/badge/JUnit5-25A162.svg?&style=for-the-badge&logo=JUnit5&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/apachejmeter-D22128.svg?&style=for-the-badge&logo=apachejmeter&logoColor=white"/> |
| Deploy               | <img alt="RED" src ="https://img.shields.io/badge/Docker-2496ED.svg?&style=for-the-badge&logo=docker&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Amazon EC2-FF9900.svg?&style=for-the-badge&logo=AmazonEC2&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Amazon Rds-527FFF.svg?&style=for-the-badge&logo=AmazonRds&logoColor=white"/> <img alt="RED" src ="https://img.shields.io/badge/Amazon S3-569A31.svg?&style=for-the-badge&logo=AmazonS3&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> |
| CI/CD                | <img alt="RED" src ="https://img.shields.io/badge/Github Actions-2088FF.svg?&style=for-the-badge&logo=githubactions&logoColor=white"/>  |
| ETC                  |  |

<br />

### 🎨 Design

| 역할                 | 종류     |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tool            | <img alt="RED" src ="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/> |

<br>

### 🔨 Tools

| 역할            | 종류 |
| --------------- | ------ |
| Version Control | <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> |
| Cooperation     | <img alt="RED" src ="https://img.shields.io/badge/Notion-000000.svg?&style=for-the-badge&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <img alt="RED" src ="https://img.shields.io/badge/Swagger-85EA2D.svg?&style=for-the-badge&logo=swagger&logoColor=white"/>  |
| Test            | <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/> |

<br>

## 7. 시스템 구조

### 💻 서비스 아키택처

<br>
<img src="https://github.com/user-attachments/assets/76042df6-b1c2-4fb2-a4a5-aa3a2dcb8346">

## 8. 기타
