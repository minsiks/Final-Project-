# 22.07.14~26 Fianl-Project 개인 개발

### 사용자 페이지 구현 - 영화 상세 페이지(통계차트), 영화리스트 페이지, Contact Us 페이지, 이벤트 페이지(CLOVA Face Recognition (CFR))

## Day 11~23

<aside>
🔑 Final 프로젝트 개발
—사용자 페이지 구현 —
- Movie List Page
1. 영화 데이터 추가하기(완료)
2. 예약 스케쥴 (완료)
3. 정렬 (완료)
4. 리뷰 별점 데이터 연동해서 퍼센트로 채워 나타내기(완료)
5. 페이징(완료)
- Movie detail Page
6. 슬라이드 (테마 연동 해결)
7. 팝업창 (테마 연동 해결)
8. 차트 구현하기 (완료)
9. 리뷰 폼 서브밋 보내 데이터 보내기(완료)
10. 구글맵 토글 (완료)
- Contact Page
11. 메일 보내기 (완료)
12. GoogleMap 연동 (완료)
- CFR Page
13. Naver CLOVA 연동(완료)
- Naver Cloud 서버에 연동
14. Putty로 CentOS 전송 후 이미지등 경로 재설정 (완료)
- 추가적인 Page 기능 추가
15. Movie List에 Modal 추가하기 (완료)
*07.26 사용자 페이지 완료

</aside>

## 1. 영화 데이터 추가하기

- 라쇼몽
- 벤허
- 서울의 지붕 밑
- 시계 태엽 오렌지

## 3. 영화 리스트 정렬

- 리뷰 많은순
- 개봉 오래된 순

## 8. 차트 구현하기

- 필요한 컬럼 갯수 정하기
    - 나이(연령) 별
    - 성별 별

## Contact Page

### 11. Form으로 메일 보내기

web app URL : [https://script.google.com/macros/s/AKfycbzgoGkp4W2fwgmuyMIVzKUHhMJGeepA6um90CzH7SG6r_XmSco/exec](https://script.google.com/macros/s/AKfycbzgoGkp4W2fwgmuyMIVzKUHhMJGeepA6um90CzH7SG6r_XmSco/exec)

[정적 HTML form태그에서 메일보내기 : Google Apps Mail](https://kutar37.tistory.com/entry/%EC%A0%95%EC%A0%81-HTML-form%ED%83%9C%EA%B7%B8%EC%97%90%EC%84%9C-%EB%A9%94%EC%9D%BC%EB%B3%B4%EB%82%B4%EA%B8%B0-Google-Apps-Mail)

### 12. Google Map 연동

API 키

`AIzaSyAj21huT8tlqepSfcIIbLjXaYFfRQdrWgA`

`AIzaSyDkH81Gt6K6fLLYMDQMb-ODm-PntGGrqK4`

`AIzaSyAVcOlUeG5vMxZi4i7fI-F0ELlSICjLxaA`

- 애니메이션 효과
- 클릭 이벤트 설정

### 13. CLOVA CFR

[Naver CLOVA Face Recognition(CFR)을 활용한 웹앱 만들어보기](https://equus3144.medium.com/naver-clova-face-recognition-cfr-%EC%9D%84-%ED%99%9C%EC%9A%A9%ED%95%9C-%EC%9B%B9%EC%95%B1-%EB%A7%8C%EB%93%A4%EC%96%B4%EB%B3%B4%EA%B8%B0-cc29ef51a189)

[네이버 클라우드 플랫폼 (NAVER Cloud Platform) : 네이버 블로그](https://blog.naver.com/n_cloudplatform/222247274814)

- 이미지 프리뷰 띄우기

[[HTML5] HTML5 에 이미지 preview 띄우기](https://soomti.tistory.com/7)

### 15. Movie List에 Modal로 띄우기

- 각 영화 항목의 리뷰 리스트 모달로 띄우기
- 각 영화 항목의 동영상 모달로 띄우기
- 각 영화 항목의 이미지 모달로 띄우기 (**Bootstrap Carousel Plugin 사용)**