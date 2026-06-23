# HTML+CSS 26/06/22~

# 선택자종류
## 태그 선택자
* 태그명을 선택자로 사용하는 선택자
* `<h1></h1>` -> `h1 {속성:값;}`
## 클래스 선택자
* 반복되는 클래스명을 사용하는 선택자
* `<h1 class="title"></h1>` -> `.title {속성:값;}`
## 자식 선택자
* 특정 부모 안 자식을 사용하는 선택자
* `<h1><span></span></h1>` -> `h1 > span {속성:값;}`
## 형제 선택자 + or ~
* `<div><a>1</a> <em>2</em> <del>3</del></div>`
* `div > a + em {}` 해석) 부모div의 자식a의 인접형제 em 선택
* `div > a ~ del {}` 해석) 부모div의 자식a의 형제 del 선택
* `+`는 바로 옆에 잇는 형제태그만 인식한다.
* `~`은 바로 옆 형제 포함 그 뒤에 모든 형제태그들을 인식한다.
# 자주 쓰는 웹 글꼴 주소
## 노토산스 Noto Sans KR
* <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100..900&display=swap" rel="stylesheet">


## 프리텐다드 pretendard
* <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard-dynamic-subset.min.css" />

# px -> rem 변환
* px를 rem으로 변환하려면 원하는 px 값에 루트 글꼴 크기(16)를 나누면 됩니다
* 16px/16 = 1rem
* 24px/16 = 1.5rem


