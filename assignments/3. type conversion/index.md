1. 🎖 What's the output of the code below
```js
typeof "Joe"; // Output: "string"
typeof 4; // Output: "number"
typeof NaN; // Output: "number"
typeof false; // Output: "boolean"
typeof function () {}; // Output: "function"
var phone = 8983700;
typeof phone; // Output: "number"
typeof null; // Output: "object"
```

2. 🎖 Output of the code below
```js
// Convert num into string
var num = 45;
String(num); // Output: "45"
String(321); // Output: "321"
String(300 + 23); // Output: "323"
String(false); // Output: "false"
String(true); // Output: "true"
Number("3.18"); // Output: 3.18
Number(" "); // Output: 0
Number(""); // Output: 0
Number("22 44"); // Output: NaN
Number(false); // Output: 0
Number(true); // Output: 1
```

3. 🎖 Output of the following

```js
var x = 10 + "1";
console.log(x);
// Output: 101
typeof x;
// Output: "string"
```