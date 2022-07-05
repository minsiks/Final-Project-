# 22.06.29 Fianl-Project 브레인 스토밍

## Day 01

<aside>
🔑 Final 프로젝트 전 브레인 스토밍
- 구상 및 기획
- 아이디어 회의

강사님 가이드

- 제목이나 내용에서 사용한 기능과 환경을 게시 (ex. 클라우드환경/스프링부트/…API)
</aside>

## 1. 아이디어 회의

---

### 1) 봉사활동 모집/ 참여 사이트

- 구인구직 서비스 플랫폼을 응용한 봉사활동 모집/참여 통합 및 다양한 이벤트 배치
- 실제 봉사활동 모집공고들을 나열시키고 정부의 공식적인 홈페이지와 다른 세련된 UI를 제공
- 지역별 / 지도 상 구분 지어 동적 이미지화시켜 보여준다
- 구현 가능 기술 : 지도 API, 챗봇, 모집공고 분류, 애니메이션 효과 등
- 내용 레퍼런스

[1365 자원봉사포털](https://www.1365.go.kr/vols/main.do)

- 서비스 플랫폼 레퍼런스 : [채용 정보 | 원티드 (wanted.co.kr)](https://www.wanted.co.kr/jobsfeed?utm_source=google&utm_medium=sa&utm_campaign=kr_recruit_web_sa_signup_brand&utm_term=%EC%9B%90%ED%8B%B0%EB%93%9C&utm_content=brand&gclid=CjwKCAjwzeqVBhAoEiwAOrEmzZjWhTHcERvqyBc4i691o911fb-xXQAAxdN2e5bGa_R5eGfRQl_uoRoChaIQAvD_BwE)

[채용 정보 | 원티드](https://www.wanted.co.kr/jobsfeed?utm_source=google&utm_medium=sa&utm_campaign=kr_recruit_web_sa_signup_brand&utm_term=%EC%9B%90%ED%8B%B0%EB%93%9C&utm_content=brand&gclid=CjwKCAjwzeqVBhAoEiwAOrEmzZjWhTHcERvqyBc4i691o911fb-xXQAAxdN2e5bGa_R5eGfRQl_uoRoChaIQAvD_BwE)

- UI 레퍼런스 :[캠핑톡 | 쉽고 편리한 캠핑장 예약, 캠핑톡 (campingtalk.me)](https://www.campingtalk.me/main?gclid=CjwKCAjwzeqVBhAoEiwAOrEmzdmMtH86wSDmtSmqnxVr8Wc_PygpHxp04VILO-st_lzzEh2WmYCGiRoCWwYQAvD_BwE)

[쉽고 편리한 캠핑장 예약, 캠핑톡](https://www.campingtalk.me/main?gclid=CjwKCAjwzeqVBhAoEiwAOrEmzdmMtH86wSDmtSmqnxVr8Wc_PygpHxp04VILO-st_lzzEh2WmYCGiRoCWwYQAvD_BwE)

---

### 2) 악기 중고거래 쇼핑몰

- 직접 쇼핑몰에서 거래와 직접 거래 모두 가능
- 악기거래 품목과 판매자의 위치를 고려하여 지도상으로 표시
- 악기와 관련된 이벤트나 커뮤니티 창 구성
- 지금까지 했던 포맷과 유사
- 구현 가능 기술 : 지도 API, 챗봇, 결제 API 등
- 내용 레퍼런스 : [중고악기 장터 프리미엄 | 뮬 (mule.co.kr)](https://www.mule.co.kr/bbs/market)

[중고악기 장터 프리미엄 | 뮬](https://www.mule.co.kr/bbs/market)

- 서비스 플랫폼 레퍼런스 : [당신 근처의 당근마켓 (daangn.com)](https://www.daangn.com/)

[당신 근처의 당근마켓](https://www.daangn.com/)

---

### 3) 연습실 대관 서비스 플랫폼

- 댄스 연습실 대관 플랫폼밖에 없는 것에 착안
- 악기 및 댄스 연습실 대관을 직접 할 수 있고 그 외 촬영 스튜디오 까지 대관 가능
- 각 항목마다 색을 달리해서 지도에도 표기
- 구현 가능 기술 : 지도 API, 챗봇, 결제 API 등
- 내용 및 서비스 플랫폼 레퍼런스 : [스페이스클라우드 | No.1 생활 공간대여 플랫폼 (spacecloud.kr)](https://www.spacecloud.kr/theme/1048)

[커버댄스는 여기에서! 춤추기 좋은 연습실 - 스페이스클라우드](https://www.spacecloud.kr/theme/1048)

- 지도 api 활용 레퍼런스 : [스페이스클라우드 | No.1 생활 공간대여 플랫폼 (spacecloud.kr)](https://www.spacecloud.kr/theme/1048)

[커버댄스는 여기에서! 춤추기 좋은 연습실 - 스페이스클라우드](https://www.spacecloud.kr/theme/1048)

---

### 4) 숙박 시설 예약 시스템

[에어비앤비: 휴가용 임대 숙소, 통나무집, 비치 하우스, 독특한 숙소 및 체험](https://www.airbnb.co.kr/)

---

### 5) 음악편집 /믹싱/ 마스터링 / 작곡의뢰 사이트

- 크몽이라는 비슷한 류의 사이트가 존재하지만 카테고리가 광범위하여 좀 더 디테일하게 분류 가능
- 믹싱/ 마스터링은 알음알음 하거나 직접 의뢰를 맡겨야 하는 불편 존재
- 구현 가능 기술 : 카테고리 분류, 결제 API, 챗봇 등
- 내용 및 서비스 플랫폼 레퍼런스 : [7,866개 리뷰로 증명된 45,997개 음악·사운드 서비스를 5,000원에서 부터 만나보세요! | 프리랜서마켓 No.1 크몽 (kmong.com)](https://kmong.com/category/718?utm_source=google&utm_medium=cpc&utm_campaign=7&gclid=CjwKCAjwzeqVBhAoEiwAOrEmzY0Txbw8R5zYpkkWJoJfFHYiuy26Pq4qgQaUVqyGDQMgfVWJCfbM8BoCq9cQAvD_BwE)

[](https://kmong.com/category/718?utm_source=google&utm_medium=cpc&utm_campaign=7&gclid=CjwKCAjwzeqVBhAoEiwAOrEmzY0Txbw8R5zYpkkWJoJfFHYiuy26Pq4qgQaUVqyGDQMgfVWJCfbM8BoCq9cQAvD_BwE)

### 6) 사설 환전소 가격비교 사이트

- 각지의 환전소의 가격을 비교 하여 실시간으로 환률을 받아와 적용시켜 가격 비교를 진행
    - ex) 종로환전소 1$당 1367원 / 명동 1$당 1292원
- 구현 가능 기술  : 실시간 서버로 환율 받아서 적용(?), 지도 API, 반응형 웹 등
- 프로젝트 레퍼런스 : [[가슴속 3천원] 붕어빵에 누구보다 진심이었던 한국인의 사이드 프로젝트 | by Depromeet(디프만) | Depromeet | Medium](https://medium.com/depromeet/%EA%B0%80%EC%8A%B4%EC%86%8D-3%EC%B2%9C%EC%9B%90-%EB%B6%95%EC%96%B4%EB%B9%B5%EC%97%90-%EB%88%84%EA%B5%AC%EB%B3%B4%EB%8B%A4-%EC%A7%84%EC%8B%AC%EC%9D%B4%EC%97%88%EB%8D%98-%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%9D%B8%EC%9D%98-%EC%82%AC%EC%9D%B4%EB%93%9C-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-2a3f714026b3)

[[가슴속 3천원] 붕어빵에 누구보다 진심이었던 대한민국인의 사이드 프로젝트](https://medium.com/depromeet/%EA%B0%80%EC%8A%B4%EC%86%8D-3%EC%B2%9C%EC%9B%90-%EB%B6%95%EC%96%B4%EB%B9%B5%EC%97%90-%EB%88%84%EA%B5%AC%EB%B3%B4%EB%8B%A4-%EC%A7%84%EC%8B%AC%EC%9D%B4%EC%97%88%EB%8D%98-%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD%EC%9D%B8%EC%9D%98-%EC%82%AC%EC%9D%B4%EB%93%9C-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-2a3f714026b3)

### 7) 부동산 중개

- 카카오 맵 or 국토교통부 + 네이버 챗봇 사용+ 네이버 글자인식 어쩌구 사용
- 아파트 매매 공공 데이터

[[파이썬] 부동산 API로 아파트 매매 실거래가 구하기](https://eslife.tistory.com/1100)

- 국토교통부 api

[오픈API](https://www.vworld.kr/dev/v4api.do)

### 8) 관광안내 사이트

- 공공api + 카카오맵 + 네이버 api(트렌드 검색, 블로그)
- 관광지 빅데이

[한국관광공사_관광빅데이터정보서비스](https://www.data.go.kr/data/15081754/openapi.do)

- 예제)

[](https://wonderful.kr/bbs/content.php?co_id=all_county_tour)

- 예제)

[Trip To Korea|Korea Travel|tripCheckiner](https://www.tripcheckiner.com/)

### 9) 화장품 판매 사이트

- 네이버 ai 얼굴인식을 활용
- 사진으로 나이 추측 -->스킨로션같은거 추천
- 사진으로 유명인 닮은 꼴 & 인종 --> 유명인 유형으로 해당하는 얼굴에 맞는 메이크업이랑 톤 그런거 추천?

### 10) 중고거래

- 중고거래 사이트(and 커뮤니티, dm) = 카카오 맵

### 11) 영화 추천 사이트

[영화진흥위원회 오픈API](http://www.kobis.or.kr/kobisopenapi/homepg/apiservice/searchServiceInfo.do)

- 현재 상영중인 영화 순위 -->
- 영화들 정보와 그에 비슷한 영화 추천