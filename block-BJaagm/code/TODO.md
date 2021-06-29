1. What does thread of execution means in JavaScript?
J.S engine takes the code and execute line by line known as thread of execution and at last gives the output.
2. Where the JavaScript code gets executed?
At J-S Engine
3. What does context means in Global Execution Context?
Context means the enviornment in which you are executing the codes.
4. When do you create a global execution context.
It create whenever you running any piece of codes.
5. Execution context consists of what all things?
It consists memory and otherhand operation and manipulation.
6. What are the different types of execution context?
Two types - Global execution context and function execution context.
7. When global and function execution context gets created?
Global execution context will created once whenever code is running first time. And function execution context will created whenever you are executing any function.
8. Function execution gets created during function execution or while declaring a function.
It created while function is executed.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./assets/1.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./assets/2.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./assets/3.jpg)
