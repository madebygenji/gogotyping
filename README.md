# gogotyping

## 기획
타자연습과 영단어 공부를 동시에 수행하는 애플리케이션을 기획하였습니다.  
장고 DRF를 사용하여 DB에 집어넣은 영단어를 URL로 조회하여  
동적으로 화면에 뿌려주면 타자로 입력하여 점수를 획득합니다.  
아래와 같은 기능이 포함됩니다.  
- 영단어의 작성, 읽기, 수정, 삭제
- 회원가입, 로그인 및 인증
- 네이버 아이디로 소셜로그인
- 카테고리별(1:N) 단어 출력

## 사용한 기술들(DB, 라이브러리 등등)
- Django Rest Framework
- Django allauth(로그인, 회원가입, 네이버 아이디로 로그인)
- axios(동적으로 영단어 뿌려주기)

## 프로젝트 구성
<img width="203" alt="스크린샷 2021-11-08 오전 9 35 03" src="https://user-images.githubusercontent.com/72113538/140694602-674ffac2-fa25-403b-88b3-e3d4d3db5f66.png">

## ER다이어그램(DB구성)
<img width="911" alt="스크린샷 2021-11-08 오후 3 31 04" src="https://user-images.githubusercontent.com/72113538/140694591-91d6e14e-b8bc-4d5f-a8b7-c8d80ed36005.png">

## 느낀점
장고 DRF의 사용법을 알게 되었습니다.  
소셜로그인 기능을 구현하는 방법을 알게되었습니다.  
