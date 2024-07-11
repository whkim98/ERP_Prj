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
- [팀의 개발 문화](#culture)
  
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
    - 사원코드 클릭시 ajax 통신을 통한 수정폼 이동
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/b2ebafaf-0fe2-459b-983a-4f4ccd1321a8)

    - 휴가 등록시 잔여휴가와 휴가사용일을 계산 후 잔여휴가 표시
    - 주말 및 공휴일은 계산 자동 제외
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/d00be18f-88c1-4555-b8e1-902cfce686db)

    - 추가 근무 정산 기능
    - 등록시 내부 계산식을 통한 정산 금액 측정
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/4300f869-6f4d-4b5d-80a8-c0d27e119bbf)


<br>

+ 물류 기능
    - 통합 재고 관리
    - 수량 재조정 가능
    - 폐기처리 및 수정, 삭제
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/f5eaeb9d-dff7-47e5-b829-617bab50695f)




<br>

+ 외화 관리
    - 관세청 Open API 활용 환율 정보
    - 해당 API가 실행될 때마다 해당되는 국가의 환율로 계좌정보 UPDATE
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/d4a9fc91-925c-4dc8-9659-67a0e01925a6)

      
<br>

+ 전자세금계산서
    - 선택하는 폼마다 다른 뷰/데이터 제공
    ![image](https://github.com/whkim98/ERP_Prj/assets/86636344/fc168e78-2de8-4e27-9dc7-92f79c8385c3)

      

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

# 📃 발표자료 <a name = "BOARD"></a>

<details>
  <summary> 본문 확인 (👈 Click)</summary>
  <br />
  
  발표자료 : ![낭만닥터_발표자료.pdf](https://github.com/user-attachments/files/16098868/_.pdf)
</details>




