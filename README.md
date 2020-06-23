# Andante Team Final Report
## 목차  
1. 프로젝트 개요  
2. 프로젝트 목표  
3. 개발 환경  
4. 애플리케이션 소개
5. 구현 동영상  
6. 사용기술
7. 개선방안  

## 1. 프로젝트 개요  
**프로젝트 주제 선정 이유**

성공 앱에 대한 분석을 하는 중에 배달의민족에 대해 조사를 하게 되었다.  
배달음식시장 규모가 20조원으로 증가했으며, 이 중 배달의민족이 1/4을 차지하며 업계 1위를 달성하였다.  
코로나19 영향으로 배달음식 수요가 증가함에 따라 매출은 전년보다 더 증가할 것으로 예측된다.  
고객들이 많이 사용하는 앱일수록 고객들의 니즈를 파악하여 앱을 유지보수하는 것이 중요하다고 생각했다.

![배민성장률](https://user-images.githubusercontent.com/62701551/85105330-4cd90500-b245-11ea-92c4-1050d5a1c57c.png)

## 2. 프로젝트 목표

배달의민족 앱을 사용하는 고객들의 불편한 점이나 개선되었으면 하는 점을 조사하게 되었고 우리 팀이 발견한 불편한 점은 리뷰에 관한 것이었다.

![배민](https://user-images.githubusercontent.com/62701551/85108303-6e88bb00-b24a-11ea-8ca1-b3781d0d47bf.png)

위 사진과 같이 현재 배달의 민족 리뷰창에는 카테고리가 최신순, 별점높은순, 별점낮은순으로 되어있다.  
일반적으로 고객들이 리뷰를 볼때 자신이 주문하고자 하는 메뉴에 관한 리뷰를 보고싶어한다.  
예를 들면, A치킨집에서 양념치킨이 먹고 싶어 양념 치킨에 대한 리뷰를 보고 싶은데 일일이 손으로 스크롤을 내려 양념치킨에 대한 리뷰를 찾아봐야하는 번거로움이 있다.  
우리는 이러한 문제점을 개선하고자 리뷰창에 메뉴별로 볼 수 있게끔 카테고리를 추가하고자 한다.  

![치킨 메뉴별](https://user-images.githubusercontent.com/62701551/85109519-6d588d80-b24c-11ea-8237-6e49b3268101.png)

추가적으로, 치킨 카테고리를 보면 각 브랜드 별로 브랜드를 대표하는 대표메뉴가 있다.  
교촌치킨 - 교촌 허니콤보, BHC - 뿌링클, BBQ - 황금올리브 등 브랜드마다 특색있는 메뉴가 있다.  
이러한 점을 이용하여 브랜드별 / 메뉴별 카테고리를 추가하여 고객들이 주문할때 좀 더 편리하게 주문할 수 있게 하고자 한다.  

## 3. 개발 환경

![phplogo](https://user-images.githubusercontent.com/62701551/85113128-c37bff80-b251-11ea-9bbf-78147e9a5830.png) 

phpMyAdmin  

![androidlogo](https://user-images.githubusercontent.com/62701551/85113140-c676f000-b251-11ea-8863-d20db586a409.png)  

androidstudio  

![자바](https://user-images.githubusercontent.com/62701551/85309928-4caf6280-b4ee-11ea-9580-e3d5099bea47.png)    

Java  

![brackets](https://user-images.githubusercontent.com/62701551/85322023-9f921580-b500-11ea-9988-45df4fc82bec.png)   

Brackets  

![filezilla](https://user-images.githubusercontent.com/62701551/85322029-a15bd900-b500-11ea-8d4d-c008d2b5614c.png)   

FileZilla   

## 4. 애플리케이션 소개  
이 애플리케이션은 배달의민족을 사용하면서 개선되었으면 하는 부분을 개선하였다.   
리뷰창을 세분화하여 고객이 원하는 음식의 리뷰를 꼼꼼하게 확인한 후 주문할 수 있다.  
음식 카테고리 별로 브랜드 / 메뉴별로 구분하여 음식 주문에 더 용이하다.

**4.1 로고 소개**  
오이시(Oishi)는 오늘 이거 시켜먹을까의 줄임말로 '맛있다'의 일본어인 오이시(おいしい)와 동음으로 중의적인 뜻을 가진다.     
고객들이 맛있는 음식을 주문하기를 바라는 마음을 담아 지은 로고이다.     
![oish_logo](https://user-images.githubusercontent.com/62701551/85263230-d25cef00-b4a9-11ea-8332-aa61aaa6c4c6.png)

**4.2 스플래쉬**  
이미지 클릭 ▼   
[![스플래쉬](https://img.youtube.com/vi/NvPZMBDKh7Y/0.jpg)](https://www.youtube.com/watch?v=NvPZMBDKh7Y)

**4.3 초기화면**   
![오이시11](https://user-images.githubusercontent.com/62701551/85307659-23410780-b4eb-11ea-84d0-8d95d6c8bcbb.png) 
![오이시22](https://user-images.githubusercontent.com/62701551/85307664-24723480-b4eb-11ea-8da5-065597a2e0f7.png)  

## 5. 구현 동영상

## 6. 사용기술

**Splash Activity**  

**데이터베이스**   
![image](https://user-images.githubusercontent.com/62701551/85317351-378c0100-b4f9-11ea-837a-3123902bb8e9.png)   

phpMyAdmin은 MySQL을 웹 상에서 관리할 목적으로 PHP로 작성한 오픈 소스 도구, 즉 MySQL Client 툴이다. 데이터베이스, 테이블, 필드, 열의 작성, 수정, 삭제, SQL 상태 실행, 사용자 및 사용 권한 관리 등의 다양한 작업을 웹 상에서 편리하게 수행할 수 있다.    



**회원가입 및 로그인**  

**Google Map API**  

**찜기능**

**전화기능**

**리뷰기능**

## 7. 개선방안   
결제 시스템, 가게 연동 부족    
