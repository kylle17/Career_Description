# 경력 기술서                                        
######                                                       pro.천수영



-----------------------------------------------------------------------
</br>     



### 사업계획 시스템 (2021.05 - 2021.09 개발)

  * 내용 : 사업 계획 및 실적분석
  * 고객사 : KD Fine chem
  * 환경 : 
     - 프론트엔드 : JS(ES6) , JSP 
     - 백엔드 : Java JDK 1.8 , Spring , Oracle 10g , MyBatis
     - 기타 : Eclipse , Gradle , Tomcat8  
  * 담당 :
     - 추정수지 분석 메뉴
     - 각종 비용 등록 , 조회 메뉴 ( Poi Excel 업로드 )
     - 경영실적 분석 프로그램 ( 일종의 손익계산서 )
  * 개선 : 
     - 문제 : 똑같은 SELECT절을 반복해서 서브쿼리로 사용하여 중복이 발생했다. 
     - 해결 : 이부분을 단계별로 WITH문을 구성해서 재사용했다.</br> 
     - github : :heavy_check_mark: <a href="https://github.com/kylle17/Refactoring/tree/master/0004.%20%5B%20%20%EC%BF%BC%EB%A6%AC%EB%AC%B8%20%EB%A6%AC%ED%8C%A9%ED%84%B0%EB%A7%81%20%20%5D%5B%20Oracle%20%5D" target="_blank"> 
       쿼리문 리팩터링 ( Oracle )</a>
</br></br>
     - 문제 : 개발시에 UI 테스트가 빈번하게 발생하는데 사용자 입력값을 일일이 기입하는데 시간이 소요되는 문제.
     - 해결 : 테스트용 버튼을 생성하고 사용자입력 값들을 디폴트값으로 지정해서 버튼클릭만으로 기능을 테스트 할 수 있게 구현.
  
      
 



     
</br></br>   
      
-----------------------------------------------------------------------
</br>     

### 성적서 관리 시스템 (2021.02 - 2021.05 개발)

  * 내용 : 유류제품 성적서 관리 및 공정분석
  * 고객사 : KD Fine chem
  * 환경 : 
      - 프론트엔드 : JS(ES6) , JSP 
      - 백엔드 : Java JDK 1.8 , Spring , Oracle 10g , MyBatis
      - 기타 : Eclipse , Gradle , Tomcat8  
  * 담당 :  
       - 성적서 관리 메뉴
       - 스캔리스트 관리 메뉴
  * 개선 : 
       - 문제 : 엑셀 확장자별로 사용하는 클래스가 달라서 확장자 별로 로직이 하나씩 생기는 문제가 발생.
       - 해결 : 다형성을 활용하여 해결.   
       - github : :heavy_check_mark: <a href="https://github.com/kylle17/Refactoring/tree/master/0003.%20%5B%20Excelupload%20%EB%8B%A4%ED%98%95%EC%84%B1%20%EC%A0%81%EC%9A%A9%20%5D%5B%20Java%20%5D" target="_blank"> 
        Excel Upload 로직에 다형성 적용  ( Java )</a>


</br></br>      

    
 -----------------------------------------------------------------------
</br>     
     
### 인사관리 시스템 (2020.06 - 현재 유지보수)

   * 내용 : 인사 , 급여 , 퇴직 , 연말정산 업무 및 세무신고
   * 고객사 : (주)천일정기화물자동차 계열사  
   * 환경 : 
      - 프론트엔드 : Javascript , jQuery , JSP 
      - 백엔드 : Java JDK 1.8 , DB2
      - 기타 : Eclipse , Gradle , Resin 3.1
   * 담당 :  
        - 시스템 전체 유지보수
        - 연말정산 (2020년 귀속분) 로직 수정작업
        - 원천징수이행상환신고서 작성
   * 개선 : 
       - 문제 : 로직의 가독성이 떨어짐.
       - 해결 : 여러가지 리팩터링 기술을 적용하여 가독성을 향상시킴.
       - github : :heavy_check_mark: <a  href="https://github.com/kylle17/Refactoring/tree/master/0001.%20%5B%20%20%ED%83%AD%20%EA%B8%B0%EB%8A%A5%20%EB%A6%AC%ED%8C%A9%ED%84%B0%EB%A7%81%20%20%5D%5B%20JqxTabs%20%2C%20Javascript%20%5D" target="_blank"> 
       탭 기능 로직 리팩터링 ( JqxTabs , Javascript ) </a>

 
 
</br> </br>  
      
-----------------------------------------------------------------------
</br>     
     
### 인사관리 시스템 (2020.06 - 현재 유지보수)

   * 내용 : 인사 , 급여 , 퇴직 , 연말정산 업무 및 세무신고
   * 고객사 : 부관훼리
   * 환경 : Delphi , Oracle 10g 
   * 담당 :  
        - 시스템 전체 유지보수
        - 연말정산 공제신고서 PDF업로드 기능 개발 (국세청 API 활용)
        - 연말정산 (2020년 귀속분) 연말정산 로직 수정작업 
   * 개선 : 
       - 문제 : 엑셀 다운로드 기능을 한 로직으로 구현해서 코드 파악과 수정에 많은 시간이 걸림.
       - 해결 : 엑셀 다운로드 기능을 클래스로 분리하고 로직을 유사한 기능끼리 묶어서 여러개의 함수로 나눔.  
       - github : :heavy_check_mark: <a  href="https://github.com/kylle17/Refactoring/tree/master/0002.%20%5B%20Excel%20Download%20%5D%5B%20Delphi%20%5D" target="_blank"> 
                Excel Download 로직 ( Delphi )</a>



</br> </br>   
   
-----------------------------------------------------------------------


