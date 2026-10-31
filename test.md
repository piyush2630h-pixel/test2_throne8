section - A 
Q1
semantic elements are the main structered elements of the html , whereas non-semantic are less priortized
semantic elements - main , nav
non-semantic elements - p tag , a tag

Q2
<section> tag - it divides the page into a section 
<article> tag - it is used to type a article
<div> tag - it divides the page into divisions 

Q3
<alt> tag in image is used for giving alternative response , if the image is not given or ther is any kind of error

Q4
get - it is used to read the given data
post - it is used for updating the given data

Q5
id - it is given to the parent , it provides uniqueness
class - it can be used to give multiple tags a class 

Q7
    <!-- <table>
        <th>students</th>
        <tr>name
            <td>piyush</td>
            <td>ayush</td>
            <td>raj</td>
        </tr>
        <tr>email
            <td>piy@123gmail.com</td>
            <td>ayu@123gmail.com</td>
            <td>raj@123gmail.com</td>
        </tr>
        <tr>age
            <td>20</td>
            <td>22</td>
            <td>21</td>
        </tr>
    </table> -->

Q8
inline - it get all the data in a single line
block - creates a block of data
inline-block - works as both inine and block

Q9
<nav> - used for nav bar of page
<main> - used for defining main page
<aside>
<footer> - used for the footer of page

Q10

Section - C 

Q21
test() - 20
console.log(a) - 10

Q22
1 - object
2 - array
3 - object
4 - falsey

Q23
x - 11

Q24
1 - 25
2 - 25

Q25
1
2
4
4
5

Section - D

Q26
let a = 10
let b = 20

1 - console.log(a-b)
2 - console.log(a*b)

Q27
function calculate(a,b){
    return a+b;
}

console.log(calculate(10,20));

1- function calculate(a,b){
    return a*b;
}

console.log(calculate(10,20));

2- function calculate(a,b){
    if(a>b){
        return a;
    }else{
        return b;
    }
}

console.log(calculate(10,20));

3- function calculate(a,b){
    let sqr_a = a*a
    let sqr_b = b*b
    return sqr_a+sqr_b
}

console.log(calculate(10,20));

Q28
for(let i = 1 ; i <=10 ; i++>){
    console.log(i);
}

1 - for(let i = 1 ; i <=10 ; i++>){
    if(i%2==0){
        console.log(i);
    }
}

2 - for(let i = 10 ; i >=1 ; i-->){
    console.log(i);
}

3- let sum = 0;

for(let i = 1 ; i <=10 ; i++>){
    sum+=i;
}
console.log(sum);

Q29
const student = {
    name:"amit",
    age : 21,
    marks : 75
};

1 - student.city = "bhopal";
2 - student.marks = 90;
3 - const student = {
    name:"amit",
    age : 21,
    marks : 75
    get Details(){
        return name , marks
    }
};
console.log(student.Details);

Q30
let marks = 75;
if(marks>=40){
    console.log("pass");
}else{
    console.log("fail");
}

A,B,C - let marks = 75;
if(marks>=90){
    console.log("A");
}else if(marks>=75){
    console.log("B");
}else if(marks>=40){
    console.log("C");
}else{
    console.log("fail");
}

Section - E
Q31
let num = 0;
if (num<0) {
    console.log("-ve -",num);
}else if (num===0) {
    console.log("zero - ",num);
}else{
    console.log("+ve - ",num);
}

Q32
let num = 0;
if (num%2===0) {
    console.log("even",num);
}else{
    console.log("odd",num);
}

Q33
let a = 12;
let b = 22;
let c = 42;

if (a>b && a>c) {
    console.log("greatest - ",a);
}else if(b>a && b>c){
    console.log("greatest - ",b);
}else{
    console.log("greatest - ",c);
}

Q34
function sum(a,b) {
    return a+b; 
}
console.log(sum(10,20));

Q36
let num = 7;
for (let i = 1; i <= 10; i++) {
    console.log(num*i);
}

Q37
let sum = 0;
for (let i = 1; i <= 100; i++) {
    sum+=i;
}
console.log(sum);

Q38
const numbers = [10,20,30,40,50]
for (const element of numbers) {
    console.log(element);
}

Q39
const employee = {
    name : "rahul",
    age : 25,
    salary : 30000,
    city : "bhopal"
}
for (const key in employee) {
    console.log(key);
}

Q41
for (let i = 1; i <= 100; i++) {
    if (i%3===0 && i%5===0) {
        console.log("divisible by 5 and 3" , i);
    }else{
        console.log("not divisible by 3 and 5" , i);
    }
}

Q43
let num = 5;
let res = 1;
for (let i = 2; i <= num; i++) {
    res*=i;
}
console.log(res);

Q45
let arr = [10,20,30,40,50,60]
let largest = 0
let sec_largest = 0
for (let i = 0; i < arr.length; i++) {
    if (largest<arr[i]) {
        largest = arr[i]
        sec_largest = largest
}
}
console.log(largest);
console.log(sec_largest);

Q46
let input = "javascript"
let vowels = 0
let consonents = 0
for (let i = 0; i < input.length; i++) {
    if (i=="a" || i=="e" || i=="i" || i=="o" || i=="u") {
        vowels+=1
    }else{
        consonents+=1
    }
}
console.log("vowels -",vowels);
console.log("consonents -",consonents);

Q4
