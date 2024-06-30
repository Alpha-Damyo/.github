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

[![Video Label](https://github.com/Alpha-Damyo/.github/assets/53148103/e882f67a-e259-4696-8469-ddc1d30386fa)](https://youtu.be/0Q3AQMtWyWU)

추후 영상 자체 업로드

<br>

## 4. 프로젝트 기능

#### 1️⃣ 흡연구역 안내 지도
지도 위에 흡연구역들이 초록색 핀으로 표시되어있으며 각 핀을 터치하면 흡연구역 정보 카드가 나오게 됩니다. 카드를 터치하면 흡연구역 상세화면이 나오고 흡연구역에 대한 정보들을 확인할 수 있습니다.


|지도 화면|흡연구역 상세정보 화면|흡연구역 사진|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/668b2dac-a90a-4675-9106-e189f059a96c">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/b690e9ae-4484-4c12-b631-f6bdf7db9862">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/8328f928-6815-4604-80a2-c92bedaf6875">|
<br>

원하는 태그를 설정하여 검색할 수 있는 필터 검색 기능, 이름을 검색할 수 있는 검색어 검색 기능, 흡연구역 즐겨찾기 기능을 지원합니다.

|필터 검색 화면|검색어 검색 화면|즐겨찾기 화면|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/89417b74-2c4b-4131-9b28-468fc71de5b3">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/388acec9-e192-4551-b380-278eceba9bd1">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/e07da089-7983-4831-b7b2-77c1718907ac">|
<br>

담요에 없는 흡연구역이 있을 경우 이를 제보할 수 있습니다.

|제보할 위치의 지도 화면|흡연구역 정보 입력화면|제보가 반영된 지도 화면|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/b4fcc53c-e3fb-499b-8731-f46176dad842">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/45965d2b-26a8-4535-9708-493e72244667">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/fe769996-8584-4f99-b215-1b1e1978976e">|
<br>

방문한 흡연구역에 대한 리뷰를 작성할 수 있습니다.
|리뷰를 작성하기 전 흡연구역 상세정보 화면|리뷰 작성 화면|리뷰를 작성한 후 흡연구역 상세정보 화면|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/b690e9ae-4484-4c12-b631-f6bdf7db9862">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/f43f69ac-04bb-4dec-8445-bdc1d45348d2">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/8b8a3924-3fea-497f-88c4-d55eca7e9857">|

#### 2️⃣ 흡연데이터 통계
사용자가 가장 많이 방문한 흡연구역과 전체 사용자들이 가장 많이 방문한 흡연구역을 확인할 수 있습니다. 특별 기간 동안 흡연량을 확인할 수 있습니다.
|가장 많이 방문한 흡연구역|특별 기간 흡연 통계| |
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/9a4c0ab2-80d3-4fe2-848d-7e764546d974">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/8bee90bd-a486-4b75-ac70-f5e1f38a2d78">|<img width="388">|
<br>

시간별 평균 흡연량, 기간별 흡연량, 평균 흡연량을 확인할 수 있습니다.
|시간별 평균 흡량|기간별 흡연량|평균 흡연량|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/68f8b6fa-137b-4120-8b1b-077c3ee888a7">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/b123581a-cf99-4d78-8529-1aefa037ae21">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/5b3473ea-4348-4b2a-9f71-df5e62db1e12">|
<br>

#### 3️⃣ 챌린지 및 콘테스트

챌린지 및 콘테스트를 진행할 수 있습니다. 사진찍기 챌린지를 통해 마음에 드는 흡연구역 사진에 좋아요를 누를 수 있으며 랭킹에서 순위를 확인할 수 있습니다.
|사진찍기 챌린지 화|사진 확대 화면|랭킹 화면|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/61a23959-f082-4db0-873f-4b886663c648">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/606e2a82-6324-4ec6-87de-1dd0d6e61a26">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/8dceda3c-519a-446c-ba36-372b0fb22803">|
<br>

#### 4️⃣ 마이페이지 및 소셜로그인
마이페이지에서 로그인, 푸쉬알림 설정 등을 진행할 수 있습니다. 로그인은 구글, 카카오, 네이버 3가지의 소셜 로그인을 지원합니다.
|로그인 전 마이페이지|로그인 페이지|로그인 후 마이페이지|
|---|---|---|
|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/046cc20a-e6ae-42c6-afbd-aaa9f8b723b7">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/e02c7869-7b57-4abc-a640-049f03602b3b">|<img width="388" src="https://github.com/Alpha-Damyo/.github/assets/55120784/ea342aab-d2f9-427c-802c-43a950b37645">|
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

## 8. 기타
