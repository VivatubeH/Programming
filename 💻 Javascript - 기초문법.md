![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 자바스크립트

<details>
<summary>❓자바스크립트란</summary>

>"정적인 웹 문서에 동작을 부여하는 프런트엔드(눈에 보이는 영역) 개발 언어"

</details>

<details>
<summary>❓자바스크립트 선언문</summary>

```javascript
// 자바스크립트 코드를 작성할 영역을 선언하는 것.
<script>
자바스크립트 코드
</script>
```

</details>

<details>
<summary>❓자바스크립트의 주석</summary>

```javascript
// 한 줄 주석

/*
  여러 줄 주석
*/
```

</details>

<details>
<summary>❓내부 스크립트를 외부로 분리하기</summary>

```javascript
<script src="JS 파일 경로"></script>
```

</details>

<details>
<summary>❓자바스크립트 코드 입력 시 주의사항(그냥 읽어보기)</summary>

>"대소문자 구분해서 작성하고, 코드는 줄마다 세미콜론을 쓰는 게 좋다, 문자형은 큰 따옴표와 작은따옴표 겹침 오류를 주의해야 하고, 코드 작성 시 중괄호 혹은 소괄호 짝이 맞아야 한다."

</details>

<details>
<summary>❓자바스크립트 var 변수</summary>

```javascript
// 1. var 변수의 범위
var tester = "hey hi"; // 함수 외부에서는 전역 범위
    
function newFunction() {
  var hello = "hello"; // 함수 내부에서는 함수 범위
}
console.log(hello); // error: hello is not defined

// 2. var 변수의 재사용성
var greeter = "hey hi";
var greeter = "say Hello instead"; // var 변수는 재선언이 가능하다.

// 3. 호이스팅 - 변수와 함수 선언이 맨 위로 이동함.
console.log (greeter); // greeter is undefined.
var greeter = "say hello" // 이렇게 쓰면 var greeter가 맨위로 이동해서
```

</details>

<details>
<summary>❓자바스크립트의 let 변수</summary>

```javascript
// 1. let은 블록 범위에서만 유효하다.

let greeting = "say Hi";
let times = 4;

if (times > 3) {
  let hello = "say Hello instead"; 
  console.log(hello);// "say Hello instead" -> let은 무조건 블록 범위
}
console.log(hello) // hello is not defined

// 2. let은 재선언이 불가능하다.
let greeting = "say Hi";
let greeting = "say Hello instead"; // error: Identifier 'greeting' has already been declared

// 3. 호이스팅 - 함수와 변수 선언이 맨 위로 이동함.
console.log (greeter); // 그러나, let 키워드는 초기화 되지 않아 Reference error가 발생.
let greeter = "say hello"; // let도 끌어올려진다.
```

</details>

<details>
<summary>❓자바스크립트의 const 변수</summary>

```javascript
// 1. const는 블록 범위에서만 유효하다.

// 2. const는 업데이트와 재선언은 불가능하다. ( 선언 시에 초기화 해야 함 )
const greeting = "say Hi";
greeting = "say Hello instead";// error: Assignment to constant variable.

const greeting = "say Hi";
const greeting = "say Hello instead";// error: Identifier 'greeting' has already been declared

// 3. const 객체는 업데이트 할 수 없지만, 속성은 업데이트 할 수 있다.
const greeting = {
  message: "say Hi",
  times: 4
}

greeting = {
  words: "Hello",
  number: "five"
} // error:  Assignment to constant variable.

greeting.message = "say Hello instead"; // 속성 업데이트는 가능하다.

// 4. const도 호이스팅 되지만, 초기화는 되지 않는다.
```

</details>
