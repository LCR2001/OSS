# The Spot 
## 주차 기능을 비롯한 데이트 취향 분석 알고리즘 기반의 앱 구현

1. 기존의 데이트 앱 분석
 * 데이트팝, 데이트립, 완벽한 하루, 오브코스, 대한민국 구석구석
   *[데이트팝](http://www.datepop.co.kr/view/)
   *[데이트립](http://www.daytripapp.com/)
   *[완벽한 하루](https://www.instagram.com/perfectday_official/?hl=ko)
   *[오브코스](http://ofcos.co.kr/)
   *[대한민국 구석구석](https://korean.visitkorea.or.kr/main/main.do#home)
2. 기존의 주차 관련 앱 분석
 * 카카오T 주차, T map 주차, 모두의 주차장, 아이파킹
   *[카카오T 주차](https://kakaotparking.com/)
   *[T map 주차](https://www.tmapparking.co.kr/)
   *[모두의 주차장](https://www.moduparking.com/)
   *[아이파킹](https://iparking.co.kr/web/arf/b2ccore/index/indexViewWug.do)
3. 추가할 기능
 * 기본 설정 값
   : 차량 여부. 데이트 취향(키워드 선택 - ex: 아늑한),지역
 * 선택 사항
   : 이동거리(최대 시간, 당일치기). 카테고리 분류(카페. 맛집. 놀거리. 이색 데이트)
 * 주차 관련
   : 데이트 장소 주변 주차공간 여부. 

## 기존 관련 앱 분석
<img width="412" alt="앱 분석 테이블" src="https://user-images.githubusercontent.com/91776093/143767997-4d46b976-41e0-4e16-aaa1-8cce18e7647f.png">

## Block Diagram
 * [The Spot Algorithm] <img width="280" alt="시스템 개요-finally" src="https://user-images.githubusercontent.com/91776093/143679995-edf6e9b7-a1db-4baa-a878-fd186f511d40.png">


## 앱 실행 화면(-이미지 첨부)

### 스플래쉬
 * [스플래쉬 구현 방법](https://hearit.tistory.com/21)
   <img width="165" alt="The Spot " src="https://user-images.githubusercontent.com/91776093/143680991-e0ccf4a1-7aea-4246-8bd6-83e1e0ac7415.png">

 
### 기본 설정 화면
 *차량 여부, 출발 지역, 원하는 데이트 지역, 데이트 취향(키워드 선택)
 
### 선택 사항 화면
 *이동거리(최대시간), 기간(당일치기, 1박2일 등), 카테고리 분류(카페, 맛집, 놀거리, 이색 데이트 등)
 
### 추천 장소 제시 화면
 *소요 시간도 함께 제시
 
### 주차 관련 정보 제시 화면
 * 기본 설정에서 차량 있음에 선택 시, 추천 장소 별 주차공간 관련 자료 함께 제시

### 네비게이션 자동 실행 화면
  * 추천 장소 선택 후 네비게이션 기능 선택 시, 자동으로 지도 관렵 앱 실행
 
