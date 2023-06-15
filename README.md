# react-modal
리액트로 만든 모달창
자식(하위)창에서 부모의 함수를 사용하려면
콜백함수처럼 props로 부모가 자식에게 함수를 내려줘야함

## 주요내용
- props
- useState로 상태관리
-  아래의 setModal={setModal}는 자식에게 props로 부모의 함수를 전달
   일종의 callback 함수와 같음
