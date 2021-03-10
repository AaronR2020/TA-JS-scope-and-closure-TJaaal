Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // username is not defined
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // username is not defined
```
username is in a seperate block. thus console.log cannot access username. // username is not defined

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // username is not defined
```
username is in a seperate block. thus console.log cannot access username

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // username is not defined
```
irrespective if the username is let or var, username is in a seperate block. thus console.log cannot access username

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.
```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // John
```
username value is John. it wont be Arya as it is in a seprate block.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // John
```
username value is John. it wont be Arya as it is in a seprate block.

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // John
```
username will be john and not arya as arya belongs to a seprate function execution context, which is deleted when executed.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // will execute properly
}
console.log(i, 'Second'); // i will be undefined as by defaut i is a var.
```

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // will execute properly
}
console.log(i, 'Second'); // i will be undefined as by defaut i is a var.
```
