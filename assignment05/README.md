# Javascript JAssignment - 05 (Condition)
---

## 1. Check if a number is positive or negative.

```js
let num = 5;
if (num > 0) {
    console.log("Positive");
} else if (num < 0) {
    console.log("Negative");
} else {
    console.log("Zero");
}
```
  output  =  Positive

## 2. Check if a number is even or odd.

```js
let num = 4;
if (num % 2 === 0) {
    console.log("Even");
} else {
    console.log("Odd");
}
```
  output  =  Even
  
## 3. Check if a person is eligible to vote.

```js
let age = 20;
if (age >= 18) {
    console.log("Eligible");
} else {
    console.log("Not eligible");
}
```
  output  =  Eligible

## 4. Find the largest of two numbers.

```js
let a = 10, b = 20;
if (a > b) {
    console.log("Largest is", a);
} else {
    console.log("Largest is", b);
}
```
  output  =  Largest is 20

## 5. Find the largest of three numbers.

```js
let a = 10, b = 42, c = 15;
if (a > b && a > c) {
    console.log("Largest is", a);
} else if (b > c) {
    console.log("Largest is", b);
} else {
    console.log("Largest is", c);
}
```
  output  =  Largest is 42

## 6. Check if a character is a vowel or consonant.

```js
let char = 'a';
if ('aeiouAEIOU'.includes(char)) {
    console.log("Vowel");
} else {
    console.log("Consonant");
}
```
  output  =  vowel
  
## 7. Grade the student based on marks.

```js
let marks = 85;
if (marks >= 90 && marks <= 100) {
    console.log("Grade A");
} else if (marks >= 80) {
    console.log("Grade B");
} else if (marks >= 70) {
    console.log("Grade C");
} else {
    console.log("Fail");
}
```
  output  =  Grade B

## 8. Check if a number is divisible by both 3 and 5.

```js
let num = 15;
if (num % 3 === 0 && num % 5 === 0) {
    console.log("Divisible by both 3 and 5");
} else {
    console.log("Not divisible by both");
}
```
  output  =  Divisible by both 3 and 5

## 9. Check if a number is in a range (10 to 50).

```js
let num = 25;
if (num >= 10 && num <= 50) {
    console.log("In range");
} else {
    console.log("Out of range");
}
```
  output  =  In range

## 10. Check if a year is a leap year.

```js
let year = 2024;
if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
    console.log("Leap year");
} else {
    console.log("Not a leap year");
}
```
  output  =  Leap year

## 11. Display day name based on day number.

```js
let day = 3;
switch(day) {
    case 1: console.log("Monday"); break;
    case 2: console.log("Tuesday"); break;
    case 3: console.log("Wednesday"); break;
    case 4: console.log("Thursday"); break;
    case 5: console.log("Friday"); break;
    case 6: console.log("Saturday"); break;
    case 7: console.log("Sunday"); break;
    default: console.log("Invalid day");
}
```
  output  =  Wednesday

## 12. Basic Calculator.

```js
let num1 = 10, num2 = 5, operator = '+';
switch(operator) {
    case '+': console.log(num1 + num2); break;
    case '-': console.log(num1 - num2); break;
    case '*': console.log(num1 * num2); break;
    case '/': console.log(num1 / num2); break;
    default: console.log("Invalid operator");
}
```
  output  =  15

## 13. Check if a number is zero, positive, or negative.

```js
let num = 0;
if (num > 0) {
    console.log("Positive");
} else if (num < 0) {
    console.log("Negative");
} else {
    console.log("Zero");
}
```
  output  =  Zero

## 14. Check if a student passed or failed.    

```js
let marks = 35;
if (marks >= 40) {
    console.log("Pass");
} else {
    console.log("Fail");
}
```
  output  =  Fail

## 15. Check if a person has a fever.

```js
let temp = 99;
if (temp > 98.6) {
    console.log("Has fever");
} else {
    console.log("Normal temperature");
}
```
  output  =  Has fever

## 16. Check if someone has normal temperature.

```js
let temp = 98.1;
if (temp >= 98 && temp <= 98.9) {
    console.log("Normal temperature");
} else {
    console.log("Not normal");
}
```
  output  =  Normal temperature

## 17. Attendance check.

```js
let totalClasses = 100;
let attended = 80;
let percentage = (attended / totalClasses) * 100;
if (percentage >= 75) {
    console.log("Can write the exam");
} else {
    console.log("Cannot write the exam");
}
```
  output  =  Can write the exam

## 18. Output check.

```js
if(5 > 4) { console.log("First if"); }
if(10 >= 6) { console.log("Second if"); }
```
  output  =  First if
             Second if

## 19. Output check.

```js
if(true) { console.log("1"); }
if(false) { console.log("2"); }
if(true) { console.log("3"); }
```
  Output  =  1
             3

## 20. Chained if / else-if statement.

```js
let val = 12;
if (val < 5) {
    console.log("Tiny");
} else if (val < 10) {
    console.log("Small");
} else if (val < 15) {
    console.log("Medium");
} else if (val < 20) {
    console.log("Large");
} else {
    console.log("Huge");
}
```
  output  =  Medium

## 21. Role-based access using switch.

```js
let role = "subAdmin";
switch(role) {
    case "admin": console.log("Full access"); break;
    case "subAdmin": console.log("Create and delete courses"); break;
    case "testPrep": console.log("Create and delete tests"); break;
    case "user": console.log("Consume content"); break;
    default: console.log("No access");
}
```
  output  =  Create and delete courses

## 22. Guess the output.

```js
let a = 5, b = 10;
if (a > b && b > 0) { console.log("X"); } 
else { console.log("Y"); }
```
  output  =  Output: Y

## 23. Guess the output.

```js
let day = 3;
switch(day) {
    case 1: console.log("Mon"); break;
    case 2: console.log("Tue"); break;
    case 3: console.log("Wed"); break;
    default: console.log("Invalid");
}
```
  Output  =  Wed

## 24. Simple ATM withdrawal checker.

```js
let balance = 5000;
let withdraw = 1200;
if (balance >= withdraw && withdraw % 100 === 0) {
    console.log("Transaction successful");
} else {
    console.log("Cannot withdraw");
}
```
  output  =  Transaction successful


---

Author
AMRITHA MOHANAN
















