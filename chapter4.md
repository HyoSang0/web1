# Java Script
* html의 body 태그 안의 제일 아래에서 script 태그를 통해 작성 가능

## 기본 문법
* 세미콜론(;)은 써도되고 안써도 됨.
* 출력할 때 백틱을 사용하면 c에서 출력할 때 보다 더 편하게 할 수 있음

### 변수, 타입, 주석
* let으로 선언하면 다양한 타입으로 쓸 수 있다.
* 문자열과 숫자도 연산자로 더할 수 있지만 결과는 문자열로 나온다.

```js
let a = "값" //변수 선언 및 초기화
let b = 100  //숫자, 문자, bool값 넣을 수 있음
let c = true
console.log(a)

console.log(`결과는 ${b}`)
```

### 배열과 객체
* 객체는 키와 벨류의 한 쌍? 이건 딕셔너리 아님?  

```js
let arr = [1, 2, 3, "문자", true, false0]
console.log(arr) // 배열 안의 요소를 전부 출력
arr.push("넣고 싶은 거") 

//객체는 키와 벨류의 한 쌍? 이건 딕셔너리 아님?
let obj = {"key":"value"}

let dic = [
    {"A":"Apple"},
    {"B":"Banana"},
    {"C":"Cloud"}
]
```

## 조건문, 반복문
* 조건문, 반복문 구조는 c와 동일
* &&와 ||도 똑같이 씀
```js
for(let i = 0; i < arr.length; i++){
    if(){
        
    }
    else if(){

    }
    else{

    }
}
```

## 함수
* 선언할 때 function을 붙이기
* 값을 받거나 반환할 때 자료형이 필요없음
```js
function hello(num1, num2){
    return num1 + num2;
}
let num = hello(1, 2);
```

### 유용한 함수
```js
let str2 = str.split(" ") // 문자열을 구분자로 나눠 배열에 넣어줌
let str3 = str2.join(" ") // 배열을 문자열로 합쳐줌
str3.indexOf("한") // 문자열에서 목표를 찾아 인덱스를 반환함. 없으면 -1을 반환
```
