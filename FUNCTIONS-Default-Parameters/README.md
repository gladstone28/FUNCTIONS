Lesson link:

https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-functions/lessons/functions/exercises/default-parameters

### FUNCTIONS

**Default Parameters**

One of the features added in ES6 is the ability to use default parameters. Default parameters allow parameters to have a predetermined value in case there is no argument passed into the function or if the argument is undefined when called.

Take a look at the code snippet below that uses a default parameter:

```
function greeting (name = 'stranger') {
  console.log(`Hello, ${name}!`)
}

greeting('Nick') // Output: Hello, Nick!
greeting() // Output: Hello, stranger!

```
- In the example above, we used the = operator to assign the parameter name a default value of 'stranger'. This is useful to have in case we ever want to include a non-personalized default greeting!

- When the code calls greeting('Nick') the value of the argument is passed in and, 'Nick', will override the default parameter of 'stranger' to log 'Hello, Nick!' to the console.

- When there isn’t an argument passed into greeting(), the default value of 'stranger' is used, and 'Hello, stranger!' is logged to the console.

By using a default parameter, we account for situations when an argument isn’t passed into a function that is expecting an argument.

Let’s practice creating functions that use default parameters.

### Instructions
Checkpoint 1 Passed

1. The function makeShoppingList() creates a shopping list based on the items that are passed to the function as arguments.

Imagine that you always purchase milk, bread, and eggs every time you go shopping for groceries. To make creating a grocery list easier, let’s assign default values to the parameters in makeShoppingList().

Change the parameters of makeShoppingList() into default parameters :

- Assign ‘milk’ as the default value of item1.
- Assign ‘bread’ as the default value of item2.
- Assign ‘eggs’ as the default value of item3.

Use the = operator to assign a default value to a parameter:
```
function functionName(parameter = 'Default Value', parameter2 = 100, parameter3  = true) {
 // Function body here
}

```
