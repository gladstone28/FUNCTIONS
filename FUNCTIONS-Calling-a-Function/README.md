

FUNCTIONS
Calling a Function
5 min
As we saw in previous exercises, a function declaration binds a function to an identifier.

However, a function declaration does not ask the code inside the function body to run, it just declares the existence of the function. The code inside a function body runs, or executes, only when the function is called.

To call a function in your code, you type the function name followed by parentheses.

![](./name.svg)

This function call executes the function body, or all of the statements between the curly braces in the function declaration.

![](./function-execution.svg)

We can call the same function as many times as needed.

Let’s practice calling functions in our code.

### Instructions
Checkpoint 1 Passed

1. Imagine that you manage an online store. When a customer places an order, you send them a thank you note. Let’s create a function to complete this task:

- Define a function called sayThanks() as a function declaration.
- In the function body of sayThanks(), add code such that the function writes the following thank you message to the console when called: 'Thank you for your purchase! We appreciate your business.'
**Hint**

Syntax for declaring a function:
```
function functionName(){
   // Function body
}
```
To write messages to the console:
```
console.log('Enter your message here.');
```
Checkpoint 2 Passed

2. Call **sayThanks()** to view the thank you message in the console.

Syntax for calling a function:
```
functionName();
```
Checkpoint 3 Passed

3. Functions can be called as many times as you need them.

Imagine that three customers placed an order and you wanted to send each of them a thank you message. Update your code to call **sayThanks()** three times.

Hint

The syntax for calling a function once:
```
functionName();
```
So we could call that same function three times with the following code:
```
functionName();
functionName();
functionName();
```
