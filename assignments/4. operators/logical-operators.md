# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //output: true
true  && false; //output: false
false && true; //output: false
false && false; //output: false
"foo" && "bar"; //output: "bar"
"bar" && "foo"; //output: "foo"
"foo" && ""; //output: "" 
""    && "foo"; //output: "" 
" "   && "John" && "" && false; //output: false
false && "Hey" && undefined; //output: ""  
"undefined" && false && 42; //output: false
```

* [ ] Logical OR operation
```js
true  || true; //output: true
true  || false; //output: true
false || true; //output: true
false || false; //output: false
"foo" || "bar"; //output: "foo"
"bar" || "foo"; //output: "bar"
"foo" || ""; //output: "foo"
""    || "foo"; //output: "foo"
" "   || "John" || "" || false //output: " "
false || "Hey" || undefined //output: "Hey"
"undefined" || false || 42 //output: "undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"
```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
// Your code goes here
(isGuestOneVeg && isGuestTwoVeg) && alert("Only offer up vegan dishes");
(isGuestOneVeg || isGuestTwoVeg) && alert("Make sure to offer up some vegan options.");
alert("Offer up anything on the menu")
```


3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
// Your code goes here
(temperature < 32) && alert('It is freezing outside');
(temperature > 110) && alert('It is hot outside');
(temperature >= 32 && temperature < 110) && alert('Go for it. It is pretty nice out');
```

4. 🎖 Output of this
```js
alert( alert(1) || 2 || alert(3) );
// First the alert(1) is invoked and outputs 1 but also returns undefined, which is falsey. //Hence the circuit does not break on aleart(1) and 2 is also output and the circuit breaks.
//So, the final output is 1 followed by 2.
```