# 💝프로젝트명 : One more bag [쇼핑몰 클론코딩]

#### 프로젝트 설명 : https://onemorebag.kr/product/list.html?cate_no=45 웹사이트 클론코딩
##### 프로젝트 기간: 22/9/9-15
<img width="1757" alt="스크린샷 2022-09-15 오후 1 13 38" src="https://user-images.githubusercontent.com/104494969/190312656-94c2cfd5-2dcb-470f-8b94-2a12e3f3ed42.png">

#####  서버 배포: http://hyerimawsbucket.s3-website.ap-northeast-2.amazonaws.com/
##### FE Github : origin[https://github.com/jamie7dev/W7_One_more_bag.git]
##### FE Github organization - origin2[https://github.com/codingshoppingmall8/FE]
##### BE Github : [https://github.com/codingshoppingmall8/BE]
##### 시연영상 : [https://www.youtube.com/watch?v=cNfL2WA3fxA]

## 👨‍👦‍👦Team Members
**[FE] Hye-rim-Lee, Chae-won-Yoon** <br>
**[BE] Sun-Hong-Lee, Dong-Ha-Shin, Ha-Young-Kim**

## ⚒Tech Stack
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"/>
<img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
<img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>
<img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white"/>
<img src="https://img.shields.io/badge/kakaotalk-ffcd00.svg?style=for-the-badge&logo=kakaotalk&logoColor=000000"/>
<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC.svg?style=for-the-badge&logo=Visual Studio Code&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon Web Service-232F3E?style=for-the-badge&logo=Amazon%20AWS&logoColor=white"/>

## 💾ERD
![image](https://user-images.githubusercontent.com/67679972/190326599-51dfb9a8-8e60-45f8-85ea-711b7c2f26cc.png)
<br>

## 📃api명세서
링크 : https://nonchalant-sturgeon-21a.notion.site/8-d8cd94d7525843618ebc766da876d5d0
|기능|메소드|URL|
|------|---|---|
|이메일중복체크|GET|api/member/signup|
|회원가입|POST|api/member/signup|
|로그인|POST|api/member/login|
|카카오 로그인|GET|api/member/kakao|
|메인페이지 가져오기|GET|api/post?page=|
|메인페이지 정렬|GET|api/sort_post?page= &sort_method=|
|카테고리별로 가져오기|GET|api/post_category?page=&cate_no=|
|카테고리별로 정렬|GET|api/post_category?page=&cate_n&sort_method=|
|상세페이지 가져오기|GET|api/post/{id}|
|마이페이지 가져오기|GET|api/member/mypage|
|마이페이지 수정|POST|api/member/mypage|
|장바구니 담기|POST|api/member/cart/{id}|
|장바구니 조회|GET|api/member/cart|
|장바구니 삭제|DELETE|api/member/cart|
|장바구니 전체삭제|DELETE|api/member/cart/deleteAll|
|게시글 등록|GET|api/member/cart|
|게시글 삭제|DELETE|api/member/cart{id}|
<br>


## 📖기능 구현 List

1. **회원가입**
    - **Email 중복 검사**
    - **Email 유효성 검사**
    - **PW 및 PW Confirm 유효성 검사**
    - **휴대전화 유효성 검사**
    
2. **로그인**
    - **Email, PW 입력시 공백 유효성 검사**
    - **Email, PW 일치 검사**
    - **Access Token과 Refresh Token을 Cookie에 저장하고 interceptor 사용
       모든 페이지에서 로그인 유지**
    - **소셜 로그인 구현(카카오) Token을 localStorage에 저장**   
3. **마이페이지**
    - **회원 정보 수정 (이름, 주소, 휴대전화)**
    
4. **메인 페이지**
   - **상품 카테고리별 정렬**
    - **Pagination**
    - **신상품/상품명/낮은가격/높은가격/조회수 정렬**
    - **css(스크롤시 헤더 고정, grid, 반응형 웹페이지)**
    
5. **장바구니**
    - **장바구니에 상품 추가, 개별 삭제**
    - **checkbox 전체 선택, 해제, 선택 삭제**
    - **장바구니 비우기 (목록 전체 삭제)**


-----------------
 
      
## Back) 😡TroubleShooting  

- 
    
-
## Front) 😡TroubleShooting 

- 
   
- 
     


## 😥아쉬운 점 
1.
    
