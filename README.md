# shoeshop
react 를 사용해 온라인 신발 쇼핑몰 입니다

기능 
1. 상품 목록
  상품데이터 컴포넌트화시켜 출하는방법<br>
  .map 함수를 이용해 원하는 만큼의 상품을 반복 출력시키는 방법<br>
   서버에서 axios 를 이용해 추가 상품을 출력<br>
2. 상품/details
   상품 클릭시 해당하는 데이터를 자세히 보여주는 페이지 입니다<br>
   해당 페이지마다 내용을 등록할 수  있으며 이는 한 상품당 한개의 데이터를 가지고있습니다<br>
3. 장바구니 (Cart)
   상품/details 페이지에서 주문하기 버튼 클릭시 cart 에 추가됩니다
   장바구니 페이지에서 상품조회, 상품 수량을 변경할 수 있습니다
4. 최근 본 상품 목록
   최근 본 상품을 localstorge 에 최대 3개 저장됩니다
   가장 최근에 본 상품을 가장 우측에 진열합니다
   localstorge 가 비어있다면 "배열이 없음" 문구가 출력됩니다
   
