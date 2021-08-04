1. What does thread of execution means in JavaScript?
```
Javascript engine execute code line by line and this process is also called thread of execution.
```

2. Where the JavaScript code gets executed?
```
Javascript engine create one global execution context and in this context javascript code executed by javascript engine.
```

3. What does context means in Global Execution Context?
```
// Ans: Context is the environment in which we are executing the code.

```
4. When do you create a global execution context.
```
Javascript engine create global execution context,when program is load.It created only one time.
```

5. Execution context consists of what all things?
```
Context contains specific section that store data. It is also called memory.
```
6. What are the different types of execution context?
```
//Two types
1.Global Execution Context
2.Function Execution Context
```
7. When global and function execution context gets created?
```
Global execution created only one,when our program is loaded in javascript engine.
Function execution created,whenever any function is executed in program.
```

8. Function execution gets created during function execution or while declaring a function.
//Function execution gets created during function execution and also deleted after returning value.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



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

![](./img/image-name.jpg)



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

![](./img/image-name.jpg)