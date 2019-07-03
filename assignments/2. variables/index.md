1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
**1. Solution:**
`name` in the above code is a *variable*. *variable* is a named memory location in our system. In the above code, our variable `name` stores a string which has a value of  "Mark".

2. Find the error if any
```js
  var product cost = 3.45;
```
**2. Solution:**
A variable's name cannot contain space in its name. Hence, above code has a *syntax error*.


3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" // Right
  'Hello World" // Wrong
  "Hello World' // Wrong
  'Hello World' // Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; // VALID
var 1girl; // INVALID
var woman3; // VALID
var -girl; // INVALID
var blackDog; // VALID
var 42; // INVALID
var $42; // VALID
var userName; // VALID
var x, y, z; // VALID
var x = 5, y = 6, z = 7; // VALID
var x = 5 + 10 + 2; // VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
let subtractedAmount = (amount - 80);
// Define a new variable and store the value that is 200 more then the value of amount.
let addedAmount = (amount + 200);
// Define a new variable and store the value that is 4 times the value of amount.
let multipliedAmount = (amount * 4);
// Define a new variable and store the reminder when the value of amount is  divided by 21.
let remainderAmount = (amount % 21);
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
var res = (johnAge > markAge);
// if 'res' is thruthy then below alert will be displayed
(res) && alert("John is older");
// Check who is younger
res = (johnAge < markAge);
(johnAge < markAge) || alert("Marks is younger");
// Check if their age is equal
(johnAge === markAge) && alert("John and Mark are of same age");
// Create a new variable and assign the age of john to new variable.
let copyJohnAge = johnAge;
// Check if john is equal to or greater then mark.
(johnAge >= markAge) && alert("John's age is either greater than or equal to Mark's age");
// Check if john is less then or equal to mark.
(johnAge <= markAge) && alert("John's age is either lesser than or equal to Mark's age");
// Calculate the average age of john and mark and assign to a new variable.
let averageAge = (johnAge + markAge) / 2;
```