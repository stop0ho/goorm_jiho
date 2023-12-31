# HTML, CSS를 이용해서 넷플릭스 사이트 만들기

## 스크린샷

<img width="1684" alt="image" src="https://github.com/stop0ho/goorm_jiho/assets/68852637/acd51ff0-ee5b-42e5-9e1f-83b35aecaba3">

🔽 hover 하면 확대되는 기능
<img width="1630" alt="image" src="https://github.com/stop0ho/goorm_jiho/assets/68852637/1050f130-c8d1-4a4e-918a-0bfd8d7ae9ac">

## 배운 점

### ✔️ 상단바 고정

- `fixed-position`으로 상단바 고정 가능. 이렇게 하면 `<header>` 엘리먼트가 부모인 `<body>` 엘리먼트로부터 완전히 독립되면서 `<body>` 엘리먼트에서 점유하고 있던 `<header>` 엘리먼트의 공간이 사라지게 됨.-> 메인 영역의 윗부분이 헤더 영역의 뒤로 들어가서 일부 컨텐츠 안 보이는 문제 -> `<body>` 엘리먼트의 상단에 메뉴바 높이 만큼 패딩을 주면서 해결 가능!!

---

### ✔️ 스크롤바, 확대했을 때 잘리는지 안 잘리는지

- `overflow` 지정

---

- `auto` : 자동(내용이 DIV 영역보다 많을 때 스크롤바 표시)
- `scroll` : 항상 표시
- `hidden` : 항상 숨김

---

- `::-webkit-scrollbar` : 스크롤바 전체
- `::-webkit-scrollbar-thumb` : 스크롤 막대
- `::-webkit-scrollbar-track` : 스크롤 막대 외부

---

## 보충할 점

- [x] 사진 위에 커서 갖다 대면 다른 것들은 가만히 있고 본인만 커져야 하는데 다른 애들까지 찌부되는 것
- [x] 전체화면으로 볼 때 사진들이 지나치게 커지는 것 어떻게 조정할 수 있을지?
