# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var numA = 2;
undefined
var numB = 3;
undefined
var numC = numA + numB;
undefined
console.log(numC);
VM196:1 5
undefined
var numD = numA * numB;
undefined
console.log(numD);
VM257:1 6
undefined
var numA = 1;
undefined
var numB = 2;
undefined
var boolC = numA < numB;
undefined
console.log(bollD);
VM363:1 Uncaught ReferenceError: bollD is not defined
    at <anonymous>:1:13
(anonymous) @ VM363:1
var boolD = numA < numB;
undefined
console.log(bollD);
VM372:1 Uncaught ReferenceError: bollD is not defined
    at <anonymous>:1:13
(anonymous) @ VM372:1
console.log(boolD);
VM389:1 true
undefined
var boolC = numA == numB;
undefined
console.log(boolC);
VM412:1 false
undefined
var numA = 1;
undefined
var numB = "1";
undefined
console.log(numA == numB);
VM505:1 true
undefined
console.log(numA === numB);
VM522:1 false
undefined
var strA = "吾輩は";
undefined
var strB = "猫である。";
undefined
var strC = strA + strB;
undefined
console.log(strC);
VM649:1 吾輩は猫である。
undefined
console.log(strA === strB);
VM754:1 false
undefined
var numA = 1;
undefined
if(numA===1){
    console.log("numAは1です");
}
VM851:2 numAは1です
undefined
if(numA===2){
    console.log("numAは2です");
}
undefined
var numA = 3;
undefined
if(numA===1){
    console.log("numAは1です");
}
undefined
else if(numA===2){
    console.log("numAは2です");
}
VM1054:1 Uncaught SyntaxError: Unexpected token else
else if(numA===2){
    console.log("numAは2です");
}
VM1065:1 Uncaught SyntaxError: Unexpected token else
if(numA===2){
    console.log("numAは2です");
}
undefined
if(numA===3){
    console.log("numAは3です");
}
VM1092:2 numAは3です
undefined
var numA = 3;
undefined
if(numA%2==0){
    console.log("numAは偶数です");
    if(numA>=2){
        console.log("numAは2以上です");
    } else {
console.log("numAは2未満です");
    }
}
else{
    console.log("numAは奇数です");
    if(numA>=3){
console.log("numAは3以上です");
    }else{
        console.log("numAは3未満です");
    }
}

VM1515:10 numAは奇数です
VM1515:12 numAは3以上です
undefined
for(var i = 0; i < 5; i++){
    console.log(i);
}
VM1587:2 0
VM1587:2 1
VM1587:2 2
VM1587:2 3
VM1587:2 4
undefined
var i = 5;
undefined
while(i<20){
    console.log(i);
    i = i + 3;
}
VM1681:2 5
VM1681:2 8
VM1681:2 11
VM1681:2 14
VM1681:2 17
20
var i = 5;
undefined
do{
    console.log(i);
    i = i + 3;
}while(i<20);
VM1765:2 5
VM1765:2 8
VM1765:2 11
VM1765:2 14
VM1765:2 17
20
var j = 30;
undefined
do{
    	console.log(j);
    j = j + 10;
}while(j<20);
VM1847:2 30
40
for(var i = 1; i < 10; i ++){
if(i>3){
break;
}
    console.log(i);
}
VM1962:5 1
VM1962:5 2
VM1962:5 3
undefined
for(var i = 1; i < 10; i++){
    if(i%2==0){
continue;
    }
    console.log(i);
}

VM2072:5 1
VM2072:5 3
VM2072:5 5
VM2072:5 7
VM2072:5 9
undefined
function addValue(a,b){
    var c = a + b;
    return c;
}
undefined
var d = addValue(1, 2);
undefined
console.log(d);
VM2202:1 3
undefined
var e = addValue(4, 5);
undefined
console.log(e);
VM2257:1 9
undefined
function hello(){
    console.log("hello");
}
undefined
hello()
VM2307:2 hello
undefined
var param = "xxx";
undefined
function func1(){
    console.log(param);
}
function func2(){
    console.log(param);
}

undefined
func1();
VM2490:2 xxx
undefined
func2();
VM2490:5 xxx
undefined
console.log(param);
VM2550:1 xxx
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
