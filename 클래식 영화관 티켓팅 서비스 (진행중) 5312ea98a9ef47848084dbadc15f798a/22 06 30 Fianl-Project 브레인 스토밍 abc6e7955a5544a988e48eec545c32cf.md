# 22.06.30 Fianl-Project 브레인 스토밍

## Day 02

<aside>
🔑 Final 프로젝트 전 브레인 스토밍
1.아이디어 회의

2.아이디어 중간 결정 /2안 3안

강사님 가이드

- 제목이나 내용에서 사용한 기능과 환경을 게시 (ex. 클라우드환경/스프링부트/…API)
</aside>

## 1. 아이디어 회의

### 1) 지역 축제 및 콘서트 티켓팅 사이트

- 공공 API활용해서 전국 문화축제데이터 사용할 수 있음
    - 전국 문화축제데이터 공공 API의 데이터가 부실하다면 날씨 공공 API로 대체 가능
- 콘서트 티켓팅을 통해 좌석 선택 및 예약 결제API 기능 구현 가능
- 장바구니 유무 생각 (타 티켓 예매 사이트 장바구니 X)
- 맵 API를 적극 활용해 각 지역의 축제를 표시
- 공공 API 예시

[전국문화축제표준데이터](https://www.data.go.kr/data/15013104/openapi.do)

- 내용 레퍼런스 : [W공연티켓 (wemakeprice.com)](https://ticket.wemakeprice.com/category/10002)

[W공연티켓](https://ticket.wemakeprice.com/category/10002)

- 화면 레퍼런스 (티켓팅 자리 선정, 결제 단계 레퍼런스는 X)

[YES24 티켓 - 콘서트](http://ticket.yes24.com/New/Genre/GenreMain.aspx?genre=15456&Gcode=009_202_001)

### 2) 운동예약어플

- 운동 예약
- 운동 시간마다 인원 수 제한
- 수강권 구매
- 인원 수 초과시 대기 걸어놓기 또는 창 띄우기
- 운동 수강 후 강의평 작성 후 포인트 적립
- 하루에 3번 예약은 불가능

[스튜디오메이트](https://studiomate.kr/)

## 2. 아이디어 중간 결정 / 1안, 2안, 3안

---

### 1안) ai플랫폼과 스트링부트를 활용한 티켓팅 서비스

[크롤링을 활용한 Spring 영화 예매 사이트 구현하기(CGV CLONE)](https://loy124.tistory.com/193)

- 영화 티켓팅을 통해 좌석 선택 및 예약 결제API 기능 구현 가능
- 맵 API를 적극 활용해 각 지역의 축제를 표시
- 달력 API 활용
- 티켓 출력 오시는길 첨부
- QR코드 API도 생각 (ex. 네이버 QR코드 [https://qr.naver.com/](https://qr.naver.com/))
- 메인화면에서 팝업창 띄우기
- 좌석 예매 시스템

[Javascript Project 3 . 영화관 좌석 예약](https://haileykim2014.tistory.com/182)

- 공공 API 예시

[전국문화축제표준데이터](https://www.data.go.kr/data/15013104/openapi.do)

- 내용 레퍼런스 : [W공연티켓 (wemakeprice.com)](https://ticket.wemakeprice.com/category/10002)

[W공연티켓](https://ticket.wemakeprice.com/category/10002)

- 화면 레퍼런스 (티켓팅 자리 선정, 결제 단계 레퍼런스는 X)

[YES24 티켓 - 콘서트](http://ticket.yes24.com/New/Genre/GenreMain.aspx?genre=15456&Gcode=009_202_001)

### 추후 수정 내용

- 공공 API를 활용하여 전국 축제에 적용하기는 데이터의 속성들이나 지역축제 특성상 어려운 부분이 있을것 같아 제함
- 공공 API를 활용하고 싶으면 날씨나 티켓예매하면 오시는길을 이용한 API를 사용
- 프로젝트 주제 : 지역 축제 및 콘서트 티켓 예매
- 주요 특징 : 좌석 예매 시스템 (어려울것이라 예상)
- 예)

### 질문 사항

1. 티켓 예매 기능 어떻게 만들어야 하는지?
2. 거의 동시에 동일콘서트 동일 좌석을 선택하여 결제단으로 넘어갔을때 처리 설정 및 방법
3. 장바구니 유무 생각 (타 티켓 예매 사이트 장바구니 X)

### 추가 개서

### 개선 필요 사항

1. 제목에 스트링 부트를 활용한 티켓팅 서비스와 같은 기능 정리
2. AI플랫폼을 활용하는 방안 제시

---

### 2안) 부동산 중개

- 부동산 중개 사이트 (판매 중개 위주, 부수적으로 공공 API를 활용한 정보 노출)
- 지도로 데이터
- 카카오맵 or 국토교통부 + 네이버 챗봇 사용 + 네이버 글자 인식 사용
- 판매자가 직접 매물을 올리며 올린 정보들을 구매자리스트에 나열 시킨다.
- 프로젝트 레퍼런스

[](https://wonderful.kr/bbs/content.php?co_id=all_county_tour)

- 아파트 매매 공공 데이터

[[파이썬] 부동산 API로 아파트 매매 실거래가 구하기](https://eslife.tistory.com/1100)

- 국토 교통부 공공 API

[오픈API](https://www.vworld.kr/dev/v4api.do)

- 내용 및 UI 레퍼런스 : [방찾기 - 좋은 집 구하는 기술, 직방 (zigbang.com)](https://www.zigbang.com/home/oneroom/map?mkt_source=google_sa_search_pc&keyword=%EC%A7%81%EB%B0%A9&gclid=CjwKCAjwk_WVBhBZEiwAUHQCmZpf237WBw6eI5Po7SVEVfw0CQwq0-th8rdN_esr7lKEXbrNS1Ps-xoCIy8QAvD_BwE)

[](https://www.zigbang.com/home/oneroom/map?mkt_source=google_sa_search_pc&keyword=%EC%A7%81%EB%B0%A9&gclid=CjwKCAjwk_WVBhBZEiwAUHQCmZpf237WBw6eI5Po7SVEVfw0CQwq0-th8rdN_esr7lKEXbrNS1Ps-xoCIy8QAvD_BwE)

### 질문 사항

1. 기간내 완벽하게 구현 가능 할지
2. 데이터들을 수집하는데에 어려움이 있지는 않은지 (임의로?, 실제로?)

---

### 3안) 세미프로젝트 아이디어 모아서 더 완성도있는 프로젝트 구현

- 검색기능 추가
- 성인 인증 확인하거나 주민번호 확인
- 네이버, 카카오 로그인 API
- 회원가입 유효성 검사
- 각조의 장점
    - 나이키조  = 회원가입 비밀번호 스크립트, 결제, 우편, 통합검색, 리뷰, 필터
    - 북4조 = 19세 필터후 추가
    - 티슬라 = 숫자넘기는 애니메이션, 쿠키 사용, 보안
- 구현하고 싶은 기능
    - 쿠폰
        - DB table / 쿠폰번호, 사용 기간, 쿠폰 타입
    - 적립금