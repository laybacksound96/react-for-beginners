# react-for-beginners

리액트를 연습해보자 (2023)

## 학습 기록

    기존의 자바스크립트의 방식 -
        1. html 생성
        2. 자바스크립트에서 가져오기
            2-1. 버튼 변수를 선언
            2-2. html 버튼 요소를 잡음
            2-3. 이벤트 리스너를 설치
        3. Event를 감지
        4. 데이터를 업데이트
        5. HTML에 업데이트된 데이터를 반영

    React 방식 -
        1. Import React
        2.

---

    React의 규칙 -
        1. HTML을 페이지에 직접 작성하지 않는다. 대신 JavaScript code로 대신해서 만든다.
        2. React.createElement("[태그]" , {id : "아이디"...(properties)} , "[content]") 으로 element를 생성한다.
           생성하고자 하는 HTML 태그와 같아야 한다.
        3. ReactDOM.render([렌더링 할 객체], [표시할 요소가 정의된 객체]); 로 렌더링한다.

    React의 특장점 -
        React는 유저에게 보여주고 싶은 것들을 코드에서 생성해서 보여준다.
