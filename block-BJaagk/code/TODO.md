1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

// function expression
let percentage=function(marks,total){
   return (marks * 100) / total;
}

// Arrow Function Expression 
let percentage=(marks,total)=>{
   return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// function Declaration.
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// function Expression.
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// function Expression.
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// Arrow Function Expression 
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// Arrow Function Expression 
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
A function definition can be stored in a variable as a function acts as a object, and a object can be saved in a variable thereby allowing a function defination to be saved as a function expression.

4. Why is a function call an expression in JavaScript?
a function call is an expression in javascript as the function call returns some value therefore will be resolved to something, therefore it's an expression.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid 
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
function definition is a set of instructions that have to be executed when a function call is invoked.
eg steps to brush your teeth is a function call. you upon remembering to brush your teeth and execute those steps are function call.

7. What is the similarities between function definition and function call?


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.
A higher order function is a function that receives a function as an argument or returns the function as output

10. Explain what is callback function. Why you can pass a function inside a function?
a function is basically an object. i.e it can be passed as an argument.
a callback is a function that is passed as an argument in another function.
