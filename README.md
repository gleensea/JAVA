## MAKER
<ul>
  <li>Name : Lee Young Tack</li>
</ul>

## SUPPORT PROGRAM
<ul>
  <li><span>EclipseIDE</span><br></li>
  <li><span>Xampp - Apache, MySQL</span><br></li> 
  <li><span>window capture tool</span><br><br></li>
</ul>


## SUPPORT SITE
<ul>
  <li><span>https://shacoding.com/2022/03/15/java-%EB%8F%84%EC%84%9C-%EA%B4%80%EB%A6%AC-%EC%95%B1/</span> - 도서관리 프로그램 원본 출처</li> 
  <li><span>https://angelplayer.tistory.com/222</span> - github 설정</li>
  <li><span>https://okky.kr/articles/470566</span> - 각종 무료,유료 chart 솔루션 정리</li> 
</ul>

# JAVA
기존의 프로그램은 메인 사용자 구분없이 도서 추가, 전체조회, 검색 기능으로 구현되어 있었으며, 이를 수정하여 
로그인 기능, 회원가입, 관리자 or 사용자 개별 텝으로 분리함

로그인시 id를 확인하여 관리자인지 사용자인지 구별하고, 그에 맞게 각 텝이 전시됨.
관리자와 사용자의 폼은 같은 폼을 수정하여 사용하였고, 관리자의 경우 도서 추가, 도서 전체 조회, 개별 조회가 가능하며,
사용자의 경우 도서 전체조회와 개별조회만 가능함.

회원가입은 ID와 PW 만으로 회원가입이 되게끔 작성하였으며 ID를 PK로 잡음으로 중복아이디가 나올수 없도록 함.

프로그램 실행시 로그인 화면이 먼저 전시가 되고, 해당 창에서 로그인 및 회원가입, 프로그램 종료 등의 기능이 있으며,
ID에 맞게 관리자, 사용자로 구분되어 로그인 됨. 

-- 출처 --<br>
도서 관리 프로그램  https://shacoding.com/2022/03/15/java-%EB%8F%84%EC%84%9C-%EA%B4%80%EB%A6%AC-%EC%95%B1
