#Documentation
 1. Documentation for  web languages - https://devdocs.io/javascript
 2. w3cshool
 
 practice javascript function : 
 
function sammple(){}
undefined
function callbackNDemo(fn){}
undefined
function callbackDemo(fn){
fn();
}
undefined
callbackDemo(() => {console.log("im amrita")})
im amrita
undefined
callbackDemo(() => (1)
Uncaught SyntaxError: missing ) after argument list
callbackDemo(1)
VM1084:2 Uncaught TypeError: fn is not a function
    at callbackDemo (<anonymous>:2:2)
    at <anonymous>:1:1
callbackDemo @ VM1084:2
(anonymous) @ VM1191:1
let str = 1;
undefined
let str ="Hello";
undefined
let num = 100;
undefined
let lam = () => {console.log('Hello World')}
undefined
function demo(p1){
  console.log(p1);
}
undefined
demo(1);
VM1509:2 1
undefined
demo(() => {})
VM1509:2 () => {}
undefined
demo(lam)
VM1509:2 () => {console.log('Hello World')}
undefined
function xyz(p1){}
undefined
function xyz(p1){
console.log(typeof p1);
}
undefined
xyz(str);
VM1731:2 string
undefined
function pqr(p1){
console.log(p1,typeof p1);
}
undefined
let fn = () => {console.log('amrita tiwari rahul')}
undefined
fn();
VM1959:1 amrita tiwari rahul
undefined
function givemeAnyName(p1){
console.log(p1,typeof p1);
}
undefined
function givemeAnyName(p1){
 p1();
console.log(p1,typeof p1);
}
undefined
givemeAnyName( () => {console.log('hello miss')});
VM2162:1 hello miss
VM2034:3 () => {console.log('hello miss')} "function"
undefined
givemeAnyName( () => {console.log('hello miss');});
VM2167:1 hello miss
VM2034:3 () => {console.log('hello miss');} "function"
undefined
givemeAnyName( () => {console.log('hello miss Amrita');});
VM2178:1 hello miss Amrita
VM2034:3 () => {console.log('hello miss Amrita');} "function"
undefined
function givemeAnyName(p1){
p1();
}
undefined
givemeAnyName( () => {console.log('hello miss Amrita');});
VM2248:1 hello miss Amrita
undefined
givemeAnyName(lam);
VM1377:1 Hello World
undefined
