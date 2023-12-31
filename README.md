# 개인프로젝트 : 2023.12.18 ~ 2023.12.22
**프로젝트 설명 : CRUD 공부를 위한 개인프로젝트**
## 책 목록
![image](https://github.com/Ggyuhwan/Book-MVC/assets/133470173/2a15da13-e177-4edb-9d56-88ba6b9bf725)

`클라이언트가 "/list" 경로로 요청을 보내면 도서 목록을 조회하여 모델에 추가하고, "book/list" 뷰를 반환하여 해당 도서 목록을 표시하도록 합니다.`

## 책 생성
![image](https://github.com/Ggyuhwan/Book-MVC/assets/133470173/b6ed63f7-f2a6-4fef-a57e-2edef37467d4)

`"/create"로 접근하면 도서 생성 화면이 표시되고, "/insertDo"로 도서 생성을 시도하면 입력한 정보로 도서를 생성하고 목록 화면으로 리다이렉트합니다.
`

`HTTP 요청에서 도서에 관련된 정보를 가져와서 이를 이용하여 BookVO 객체를 생성하는 과정입니다. 이렇게 생성된 BookVO 객체는 이후에 도서 생성 기능을 수행하는 bookService.insert(book); 메서드에 전달되어, 데이터베이스에 신규 도서 정보를 추가하는 데 사용됩니다.`

## 책 상세

![image](https://github.com/Ggyuhwan/Book-MVC/assets/133470173/496cc2d6-888f-47b6-b7bc-7e05ba1bde3c)

`클라이언트가 "/detail" 경로로 요청을 보내면 해당 도서의 상세 정보를 조회하고, 이를 "book/detail" 뷰에 전달하여 상세 정보를 표시합니다.  클라이언트가 요청한 도서의 상세 정보와 도서 ID를 모델에 담아 뷰로 전달하는 역할을 합니다.`

## 책 수정
![image](https://github.com/Ggyuhwan/Book-MVC/assets/133470173/0d8414ec-0436-4fe0-bb89-95e313ae653f)

` 클라이언트가 "/updateDo"로 POST 요청을 보내면, 전달된 도서 정보를 이용하여 해당 도서를 수정하고, 수정이 완료되면 도서 목록 화면으로 리다이렉트하는 역할을 합니다.`

## 책 삭제
![image](https://github.com/Ggyuhwan/Book-MVC/assets/133470173/496cc2d6-888f-47b6-b7bc-7e05ba1bde3c)

`클라이언트가 "/deleteDo"로 POST 요청을 보내면, 전달된 도서 정보를 이용하여 해당 도서를 삭제하고, 삭제가 완료되면 도서 목록 화면으로 리다이렉트하는 역할을 합니다.`

### 느낀점
`기초 개념을 더 잘 이해할 수 있어서 좋았습니다. 디버깅과 로그를 더 깊게 이해하면 오류를 찾고 해결하는 과정이 더 수월해질 것 같습니다. 지속적인 학습을 통해 개발 스킬을 향상시키고, 자료와 커뮤니티를 적극 활용하여 다양한 문제에 대한 해결책을 찾는 것이 도움이 될 것 같습니다.`


