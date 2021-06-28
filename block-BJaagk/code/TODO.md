1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let marks = function percentage(marks, total) {
  return (marks * 100) / total;
}

let marks = function(marks, total) {
  return (marks * 100) / total;
}

let marks = (marks, total) => {
  return (marks * 100) / total;
}

let marks = (marks, total) => (marks * 100) / total;
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
//FUNCTION DECLARATION
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
//Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
//Function Expression

```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
//Function Expression

```

```js
let percentage = (marks, total) => (marks * 100) / total;
//Function Expression

```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
let fullName = function(firstName,lastName){return `${firstName} ${lastName}`}
4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // 5
five = add; // ƒ add(a, b) {
//   return a + b;
// }
five = five(10, 11); // 21
five = function () {
  return 'Hello';
}; // ƒ () {
//   return 'Hello';
// }

```

6. What is the difference between function definition and function call? Explain with an example.
function defination is when you define a function
and function call is calling a function followed by parenthesis.
7. What is the similarities between function definition and function call?

function defination is an expression(function is an object)
function call is an expression(function call return a value)

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
A function that returns a function is called a Higher-Order Function.
[1, 2, 3, 4].map(function(n){
    return n * 2
}) // [ 2, 4, 6, 8 ]
10. Explain what is callback function. Why you can pass a function inside a function?
A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

