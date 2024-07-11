# <img src="https://github.com/whkim98/ERP_Project/assets/86636344/4e1233be-7b50-4619-bc70-f13dd75c71bd" width="30"/>
<b>물류, 인사, 재무 등 다양한 기능을 한 번에!</b> 쉽고 간편하게 전사적 자원 관리를 도와줍니다.<br/>
다양한 기능으로 더욱 효율적으로 업무 능력을 높여줍니다!<br/><br/>

## 주요기능
* 인사(근태, 정산, 휴가 등) 관리
* 거래처 물자 및 물류 관리
* 재무제표 등록, 수정
<br/><br/>

## 프로젝트 일정 및 규모
* 기간 : 2023.06.27 ~ 2023.09.17
* 인원 : 4명
<br/>

## 팀원
이름|담당 기능|Github
---|---|---
김우형|물류, 거래처, 인사|[whkim98](https://github.com/whkim98)
장소라|재무제표, 디자인 총괄|[SoraJang1](https://github.com/SoraJang1)
신동현|영업, 생산, 구매|[MichealnotJackson](https://github.com/MichealnotJackson)
정준홍|기획, 회계, 디자인 서브|[JNjeong](https://github.com/JNjeong)
<br/>

## 주요 ERD
<img src="https://github.com/whkim98/ERP_Project/assets/86636344/70098314-61ab-4887-9dc3-951ac0c362fa" width="800">
<br/>

## 개발환경
### FrontEnd
<div>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
</div>

### BackEnd
<div>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"> 
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring boot&logoColor=white">
  <img src="https://img.shields.io/badge/mybatis-000000?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black">
</div>

### Tools
<div>
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
  <img src="https://img.shields.io/badge/intellij idea-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
  <img src="https://img.shields.io/badge/vscode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
</div>

  <br>

---

 <br>

# 📝 [목차](#index) <a name = "index"></a>

- [개요](#outline)
- [프로젝트 구성](#Configuration)
- [다이어그램](#Diagram)
- [협업 방식 - Loop](#Loop)
- [팀의 개발 문화](#culture)
- [결과물](#outputs)
- [API 명세서](#API)
- [발표자료](#BOARD)
  
<br>

# 🎉 개요 <a name = "outline"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br />

<h3>기업 자원 관리 ERP 통합 시스템 !!!</h3>

물류, 인사, 재무 등 다양한 기능을 한 번에! 쉽고 간편하게 전사적 자원 관리를 도와줍니다. 다양한 기능으로 더욱 효율적으로 업무 능력을 높여줍니다!


</details>

<br>

# ✨ 프로젝트 구성 <a name = "Configuration"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br />

+ 인사 기능
    - 사용자 정보 CRUD 데이터 관리, 검색
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/b2ebafaf-0fe2-459b-983a-4f4ccd1321a8)


<br>

+ 예약
    - 병원 검색을 통해 예약 페이지 접속
    - 예약과 동시에 로그인한 이메일 주소로 알림 메일 전송
    - 직원 페이지에서 수락 버튼 클릭시 화상진료 입장 가능

<br>

+ 화상 진료
    - 이메일로 전송된 방이름 입력 후 화상 진료 시작
    - 의사는 처방전 입력 페이지로 이동
    - 채팅 및 카메라 ON/OFF, 마이크 MUTE/UNMUTE
    - 방나가기 버튼 클릭시 화상진료 버튼이 결제 버튼으로 바뀜
      
<br>

+ 결제
    - 의사가 처방전 입력시 결제하러가기 버튼 활성화
    - 카드, 휴대폰, 가상계좌 등의 방법으로 결제 가능
    - 결제시 리뷰쓰러가기 및 처방전 열람 버튼 활성화
      
<br>

+ 챗봇
    - 예약하기, 병원검색 가능
 
<br>

+ 익명게시판
    - 익명으로 작성
    - 작성시 닉네임, 비밀번호, 내용 입력 가능
    - 파일첨부 가능
    - 비밀번호 암호화
 
<br>

+ 직원페이지
    - 의사, 간호사, 행정, 매니저 권한 부여
    - 매니저는 속한 병원의 직원에게 권한 변경 및 병원 정보 수정 가능
    - 캘린더에서 일정 보기
      
<br>
</details>

<br>

# 📈 다이어그램  <a name = "Diagram"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br/>

<h3>ER다이어그램</h3>
<div align="center">
 <img src="https://github.com/6BitCampers/Nangman_Doctor/assets/86636344/01b725d9-fad3-465b-a031-52b6709f58f4" width="450">
</div>

</details>

<br>

# 🙌🏻 협업 방식 - Loop <a name = "Loop"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br />


<div align="center">
 <img src="https://github.com/6BitCampers/Nangman_Doctor/assets/86636344/a8fd24c8-ba38-46d2-b0f9-00545a62d61f" width="350">
</div>

<div align="center">
 <img src="https://github.com/6BitCampers/Nangman_Doctor/assets/86636344/8c72b9fd-22f1-44f0-8213-5981b997c713" width="350">
</div>

<div align="center">
 <img src="https://github.com/6BitCampers/Nangman_Doctor/assets/86636344/f8001790-86d6-45b9-8e90-57dcdf614f3c" width="350">
</div>

저희 팀은 협업 방식으로 Notion, Trello, Google Sheets를 사용했습니다.  

아이디어를 공유하고 해당 아이디어 대해 자신의 생각과 추가적인 아이디어를 작성하여 아이디어 보완을 했습니다.

프로젝트 선정 후 목표 우선순위 진행률과 구현할 기능을 선정하고  역할 분담을 하고 각자 맡은 기능들에 대해 백로그를 작성하면서 팀원들과 진행사항을 공유했습니다.

</details>

<br>


# 🎡 팀의 개발 문화 <a name = "culture"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br />


## Github 규칙
<h3>1. 개발 환경 및 협업 방법:</h3>
각 개발자는 본인이 현재 작업중인 폴더 외의 코드는 확인만 가능하고 직접 수정하지 않습니다.

불가피하게 수정이 필요한 경우, 담당 개발자와 필수적으로 협의합니다.

코드 변경이 필요한 부분을 찾았을 때, 해당 부분의 담당자에게 알려주고 직접 수정하지 않습니다.

<br>

<h3>2. 커밋 규칙:</h3>
1일 1회 Main 브랜치에 Merge를 진행합니다.

기능이 완료되지 않은 오류 코드의 경우 제외 후 커밋/푸쉬 합니다.

<h3>3.브랜치 전략:</h3>
Main 브랜치에서는 직접적으로 개발하지 않고, 기능 개발은 각 개발자의 이름으로 만들어진 브랜치에서 작업합니다.

개발이 완료되면 각 개발자의 브랜치에서 Main 브랜치로 pull request를 생성하여 코드 리뷰를 받고 Git 담당자에게 승인을 받은 후에만 Main 브랜치로 Merge합니다.

Main 브랜치로 merge된 이후에는 변경된 기능을 확인하고 오류 발생시 각 담당 개발자에게 전달합니다.

</details>

<br>

# 🔎 결과물  <a name = "outputs"></a>

<details>
   <summary> 본문 확인 (👈 Click)</summary>
<br />

배포주소: http://deploysemi.midichi.kro.kr/


</details>

<br>

# 📃 API 명세서 <a name = "API"></a>

<details>
  <summary> 본문 확인 (👈 Click)</summary>
  <br />

  스웨거 주소: http://deploysemi.midichi.kro.kr/swagger-ui
</details>

<br>


# 📃 발표자료 <a name = "BOARD"></a>

<details>
  <summary> 본문 확인 (👈 Click)</summary>
  <br />
  
  발표자료 : ![낭만닥터_발표자료.pdf](https://github.com/user-attachments/files/16098868/_.pdf)
</details>




