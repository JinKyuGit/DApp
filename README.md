# DApp
truffle을 통한 dapp 예제 테스트.

1. npm install -g truffle
2. truffle unbox pet-shop
3. ganache 설치
4. contract/ 하위에 계약서 파일 작성 (solidity)
5. migrations/ 하위에 deploy js 파일 작성
6. truffle compile
7. truffle migrate => ganache에 반영되는지 확인
8. src/app.js 작성, truffle-config.js 수정.
9. 크롬 플러그인 metamask 설치 및 로컬 ganache와 연동
10. npm run dev를 통해 서버 시작 및 테스트
11. 정상 테스트 : adopt 버튼 클릭시 metamask 지갑 팝업 생성 및 트랜잭션 정상 기록 확인.
