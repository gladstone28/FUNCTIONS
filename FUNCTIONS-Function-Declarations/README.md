[Lesson link](ttps://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-functions/lessons/functions/exercises/function-declaration)

### FUNCTIONS

**Function Declarations**

In JavaScript, there are many ways to create a function. One way to create a function is by using a function declaration. Just like how a variable declaration binds a value to a variable name, a function declaration binds a function to a name, or an identifier. Take a look at the anatomy of a function declaration below:

![](./declaration.svg)

A function declaration consists of:

- The function keyword.
- The name of the function, or its identifier, followed by parentheses.
- A function body, or the block of statements required to perform a specific task, enclosed in the function’s curly brackets, { }.
A function declaration is a function that is bound to an identifier, or name. In the next exercise we’ll go over how to run the code inside the function body.

We should also be aware of the hoisting feature in JavaScript which allows access to function declarations before they’re defined.

Take a look at example of hoisting:

```
greetWorld(); // Output: Hello, World!

function greetWorld() {
  console.log('Hello, World!');
}

```
Notice how hoisting allowed greetWorld() to be called before the greetWorld() function was defined! Since hoisting isn’t considered good practice, we simply want you to be aware of this feature.

If you want to read more about hoisting, check out MDN documentation on hoisting.

### Instructions

Checkpoint 1 Passed
1. Let’s create a function that prints a reminder to the console. Using a function declaration, create a function called getReminder().

Hint

Syntax for a function declaration:
```
function functionName() {}
```
Checkpoint 2 Passed
2. In the function body of getReminder(), log the following reminder to the console: 'Water the plants.'

Hint

To write to the console:
```
console.log('Insert Message Here');
```
Include your code between the curly braces:
```
function functionName() {
 //  Code body between curly braces
}
```
Checkpoint 3 Passed
3. Let’s create another function that prints a useful Spanish travel phrase to the console.

Using a function declaration, create a function called greetInSpanish().

Hint

Syntax for a function declaration:
```
function functionName() {}
```
Checkpoint 4 Passed
4. Add code to the function body of greetInSpanish():

Hint

In the function body console.log() the following Spanish phrase to the console: 'Buenas tardes.'
To write to the console:
```
console.log('Insert Message Here');
```
Include your code between the curly braces:
```
function functionName() {
 //  Code body between curly braces
}
```
