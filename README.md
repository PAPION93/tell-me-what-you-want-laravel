# 최적의 음식점 찾기

> 현재위치와 음식종류 그리고 +a 로 최적의 음식점을 찾아보자  
> 2020-01-06 첫 작성, 최대 일주일간 아이디어만 내볼 것  
> 2020-01-11 추가작성  
> 2020-01-13 시작예정

# 시작 전

## 1. 계기

-   나는 퇴근하고 그분과 함께 무엇을 먹으면 좋을지 생각이 나지 않는다.
-   미리 생각안하고 계획없다고 혼이 난다.
-   그래도 난 업무시간엔 생각할 수 없다! 개발을 열심히!
-   지금도 혼나고 먼길 돌아와 공부할겸 한번 만들어본다.
-   간단하게

## 2. 사용기술

-   Front-end : React
-   Back-end : Laravel
-   도커라이징
-   네이버 클라우드 플랫폼 Maps

## 2.5 추가 생각

-   모두 새로 접하는 기술이기 때문에 Study Log 작성하기
-   꾸준하게 + 데드라인 잡기
    -   벌써 오랜만에 들어옴. 그래서 꾸준함을 위해 날짜나 시간을 정할 필요가 있음.
    -   주중 2번, 주말은 들여다볼 것
    -   1차 데드라인 : 4/30

## 3. 기능

-   가. 현위치 또는 위치검색으로 시작
-   나. 원하는 음식 종류 필터링 또는 선정
-   다. 음식점 선택
    -   블로그 서칭
    -   길찾기 안내
-   라. 추천 음식점
    -   날씨와 거리를 고려
-   마. 회원일 경우 데이터 저장

-   부가 기능
    -   음식점 평가 기능
    -   일일 검색 순위

---

# 시작

> 2020-04-19 laravel, react 맛보고 와서 진짜 시작

### 개발환경 세팅

0. `docker-compose up -d --build`
1. `cd /var/www/html`
2. `laravel new .`
3. `composer update`
4. `cp .env.example .env`
5. `php artisan key:generate`
6. localhost 접속 확인

### React 세팅

7. `composer require laravel/ui`
8. `php artisan ui react`
9. `npm install`
10. `npm i react-router-dom`
11. `npm run dev`
12. Example Component 출력 확인

13. prop-types 유효성검사  
`npm i prop-types` 
14. axios API 요청  
`npm i axios`  
15. router  
`npm install react-router-dom` 

### Material UI

`npm install @material-ui/core`  
`npm install @material-ui/icons`