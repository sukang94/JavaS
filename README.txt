// 자바스크립트 문법은 낙타모양 : 스페이스는 대문자로 Ex) Day of Week 아닌 dayOfWeek로 작성하기

Variables 변수
// let 변할수 있는 변수 = var

let a = 221;
let b = a - 5;
let a = 4 
console.log( b , a) = 216 4

자바스크립트는 코드를 위에서 아래로 실행한다.

// const 상수 = 안정적 변할수가 없는 변수 되도록이면 const로 쓰기

const a = 221
let b a - 5;
let a = 4
console.log ( b , a ) = error
  
// 데이터 타입

String = text // 텍스트
boolen = true / false // 참과 거짓
Number = 1,2,3,4,5 // 숫자
float = 1.3455 // 소숫점

// Array = 데이터를 저장하는 곳, 리스트 처럼 작성 [] 브라켓

const dayOfWeek = [ "Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"];
console.log(dayOfWeek); = [ 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun' ];
console.log(dayOfWeek[2]); = Wed
/ 컴퓨터는 0 부터 시작한다 그래서 0을 치면 Mon로 시작

// 오브젝트 = {} 컬리 브라켓

const Sukang = {
    name:"sukang",
    age:27,
    gender:"male",
    isHandsome: false,
}
console.log(sukang); = { name:sukang, age:27, gender:male, isHandsome: false }
console.log(sukang.age) = 27


const Sukang = {
    name:"sukang",
    age:27,
    gender:"male",
    isHandsome: false
}

sukang.age = 26

console.log(sukang.age = 26 나옴 오브젝트명은 바꿀수가 없으나 오브젝트 안에 있는 것은 바꿀수가 있다.

const Sukang = {
    name:"sukang",
    age:27,
    gender:"male",
    isHandsome: false,
    favMovie:[ "배트맨", "어벤져스", "아이언맨" ]
    favFoot:[{name: "chkin", price: 20000}, { name: "Ramen", price: 1000 }]
}
console.log(sukang.favFoot[0].price) = 20000

// function 함수!!

function sukang() {
    console.log('Hello');
}

sukang(argument);
console.log("Hi") = Hello
                    Hi
/ sukang() () >> 안에 있는것이 인자라고 부른다 "argument"

function sukang(입력) {
    console.log("Hello", 입력);
}
    sukang(입력); = Hello 입력

function sukang(name, age) {
    console.log(`Hello ${name} you are ${age})
}
    sukang(pori, 5) = Hello proi you are 5

// return 잔돈을 주면 잔돈을 반환 시킴 (컴퓨터는 계속해서 실행만 시켜주기 때문에 멈추는 것이 필요.)

function sukang(name, age) {
   console.log(`Hello ${name} you are ${age})
}
   const TEST = sukang(pori, 5) = Hello proi you are 5, undefined

   function sukang(name, age) {
   return console.log(`Hello ${name} you are ${age})
}
   const TEST = sukang(pori, 5) = Hello proi you are 5