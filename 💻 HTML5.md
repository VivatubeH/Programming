![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

<details>
<summary>❓HTML이란?</summary>

>"HyperText Markup Language, 웹에서 자유롭게 오갈 수 있는 웹 문서를 만드는 언어."

</details>

<details>
<summary>❓HTML을 배워야 하는 이유</summary>

>"HTML5라는 문서 표준을 이해하고 웹 사이트의 구조를 이해하는 것이 반응형 웹 디자인 및 코드 수정, 협업의 필수 역량이다."

</details>

<details>
<summary>❓태그란?</summary>

>"마크업(어디가 이미지이고 어디가 텍스트인지 등을 표시)할 때 약속된 표기법, <와 >을 이용해 구분하며 소문자를 쓰는 게 권장된 원칙이다."

</details>

<details>
<summary>❓HTML 문서의 기본 구조</summary>

```html
<!doctype html>
<html lang="ko">
<head>
</head>
<body>
</body>
</html>
// 1. !doctype html -> 현재 문서가 HTML5 언어로 작성된 웹 문서임을 표시
// 2. html ~ /html -> 웹 문서의 시작과 끝을 나타낸다. 웹 브라우저가 html 태그를 만날 시 /html까지 소스를 HTML 문법에 맞춰 브라우저에 표시
// 3. head ~ /head -> 웹 브라우저가 웹 문서를 해석하기 위해 필요한 부가 정보들, 문서 제목 말고는 웹 브라우저 화면에는 표시 X
// 4. body ~ /body -> 실제로 웹 브라우저 화면에 나타날 내용, 대부분의 HTML 태그가 속하는 부분
```
</details>

<details>
<summary>❓head 태그의 내부 태그들</summary>

```html
<title> 문서 제목 <title>
<meta charset="UTF-8"> // meta 태그는 문자 세트를 비롯한 웹 문서와 관련된 정보를 말한다. (meta 데이터; 데이터에 대한 데이터)
// 웹 브라우저에게 어떤 문자 세트를 사용할 지 알려준다. 
```

</details>

<details>
<summary>❓HTML 엔티티(entity)</summary>

>"HTML 예약된 html 문법이 아닌 텍스트 그 자체로 사용하기 위해 별도로 만든 문자셋, 문법은 &엔티티이름; 또는 &엔티티숫자;"

</details>
