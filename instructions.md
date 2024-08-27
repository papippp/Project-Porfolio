# Instructions  

  Time to create some input functions and store its value to a variable. Here is an example for reference:

  ```javascript
  const name = prompt('What is your name?');
  
  // this is to just print the name value
  console.log(name);

  // this prints out a template literal
  console.log(`My name is ${name}.`); 
  ```

  FYI: template literal refers to the `` `My name is ${name}` ``

  If you type in `"Haris"` in the console, it should look like this:
  ```
  Haris
  My name is Haris.
  ```

  ## Steps

  1. Create a variable `age` and assign it an `input` function with the statement `"What is your age?"`.
  2. Console log the `age` variable.
  3. Create another console log with the template literal:  `My age is ${age}.`
<details>
<summary>Answer</summary>

```javascript
const age = prompt('What is your age?');
console.log(age);
console.log(`My age is ${age}.`);
```
</details>

  ## Practice

   1. Create a variable `birthday` and assign it an `input` function with the statement `"When is your birthday?"`.
  2. Console log the `birthday` variable.
  3. Create another console log with the template literal:  `My birthday is on ${birthday}.`
<details>
<summary>Answer</summary>

```javascript

const birthday = prompt('When is your birthday?');
console.log(birthday);
console.log(`My birthday is on ${birthday}.`);
```
</details>