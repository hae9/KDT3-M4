# 4차 과제 : 스마트 스토어 만들기

배포:https://kdt3-m4-of-team4.netlify.app/
클론 사이트: https://smartstore.naver.com/freshmentor
멤버: 강해경, 김혜인, 김지원, 홍혜원, 황이삭

## 프로젝트 목표

1. 리액트 라이브러리를 학습하고 익숙해지는 것
2. 다양한 리액트 라이브러리 경험
3. 디자인보다 기능 구현에 초점 맞춘 작업
4. 팀프로젝트를 통한 협업을 경험
   - 깃허브를 이용한 협업
   - 코드 컨벤션과 규격화
   - 문서화 등

## 사용

1. `React`

- `framer-motion` : 애니메이션 효과 구현
- `react-hook-form` : 각종 form의 state관리, 유효성검사
- `react-icons` : 아이콘 컴포넌트
- `react-query` : 서버에 데이터 요청, 캐싱으로 최적화
- `react-router-dom` : 라우팅 기능
- `recoil` : 전역 state 관리

2. `post CSS` : 디자인
3. `npm` : 패키지 매니저
4. `prettier` : formatter
5. `firebase` : 장바구니 기능 위한 서버구현

## 목표 기능구현

1. 상품 정보 객체 만들기
2. GNB
   1. 전체상품
   2. 베스트
   3. 농산물
   4. 수산물
3. 검색
   1. 낮은 가격순, 높은 가격순
4. 카테고리
   1. 장바구니
   2. 구매하기
   3. 상세정보
5. 제품리스트
6. 로그인, 회원가입, 마이페이지
7. 장바구니
   1. 전체삭제
   2. 상품당 삭제
   3. 주문하기
8. 구매하기
   1. 배송지 선택
   2. 주문자 정보
   3. 결제수단
      - 계좌결제
9. 관리자 페이지

## 이슈 발생과 해결

- 리액트 컴포넌트 간의 겹침문제 https://github.com/fastcampus-team4/KDT3-M4/issues/17
- git이 대소문자 구별하지 못하라 때 https://github.com/fastcampus-team4/KDT3-M4/issues/30
- 슬라이드 framer-motion 애니메이션 적용 안된 문제 https://github.com/fastcampus-team4/KDT3-M4/issues/65
- Link 버튼 누를때 의도치 않은 쿼리 fetch로 로딩되는 문제https://github.com/fastcampus-team4/KDT3-M4/issues/66

## 앞으로 도전해볼 과제

- [ ] typescript 템플릿을 적용하여 마이그레이션
- [ ] 리팩토링을 통해 코드 퀄리티 높이기
- [ ] 에러 및 예외처리 코드 추가
- [ ] 디자인 퀄리티 높이기 위한 작업
- [ ] 반응형 디자인 적용하기
- [ ] 애니메이션 효과 적용하기
- [ ] 백엔드를 자체적으로 구현하여 api 대체하기
- [ ] 서버사이드 랜더링
- [ ] 상세정보 섹션 개선
- [ ] 웹사이트에 더 많은 기능 추가하기
  - [ ] 알림 기능
  - [ ] 문의 기능
  - [ ] 네이버나 카톡을 통한 로그인 기능
  - [ ] 쿠폰/포인트 및 할인 기능
  - [ ] 리뷰 및 평점시스템
  - [ ] Q&A 페이지
  - [ ] 주간 판매 랭킹
  - [ ] 성능 최적화
  - [ ] 사용성 개선

## 1차 프로젝트 회고

### 강해경

### 김혜인

### 김지원

### 홍혜원

### 황이삭

- 코드 컨벤션 정하기 어려웠다.
  - 모두가 사용할 코드 형식이 무엇인지 정하는 게 힘들었고, 작업 효율성과 엄밀함 사이에서 밸런스 잡는 것이 까다로웠다.
- 문서화의 어려움
  - 문서화 하는 것이 시간이 너무 많이 걸린다.
  - 이미지도 넣고 싶기도 하고, 더 자세하게 적고 싶을 때도 있었지만 시간적 압박과 문서가 쓸데없이 길어지는 문제도 같이 생겼다.
  - 플랫폼을 정하기 어려웠다. issues 게시판, 노션을 이용했는데 문서가 너무 파편화 되었다.
  - 코딩하느라 잠시 놓으면 뭘 문서화 할지 모르게 돼버린다. 그렇다고 이 둘을 병행하니 작업 효율이 너무 안나왔다.
  - 작성해도 잘 안읽는 거 같다 (좀 더 읽을만한 내용으로 개선해야 할 듯)
- 리액트로 컴포넌트 별로 작업을 나눠서 맡으니까 충돌도 별로 없고 협업하기 좋았던 것 같다.
- 인력의 힘인 것인지, 리액트의 힘인 것인지? 예상한 것보다 사이트 구현속도가 많이 빨라서 놀라웠다. 오히려 속도를 늦춰서 좀더 리액트를 학습하기를 요청할 정도였다.
