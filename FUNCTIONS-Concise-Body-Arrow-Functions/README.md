[lesson link](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-functions/lessons/functions/exercises/concise-body-arrow)

### FUNCTIONS

**Concise Body Arrow Functions**

JavaScript also provides several ways to refactor arrow function syntax. The most condensed form of the function is known as concise body. We’ll explore a few of these techniques below:

1. Functions that take only a single parameter do not need that parameter to be enclosed in parentheses. However, if a function takes zero or multiple parameters, parentheses are required.
![](./parameters.svg)

showcasing how arrow functions parameters differ for different amounts of parameters

2. A function body composed of a single-line block does not need curly braces. Without the curly braces, whatever that line evaluates will be automatically returned. The contents of the block should immediately follow the arrow => and the return keyword can be removed. This is referred to as implicit return.

comparing single line and multiline arrow functions

![](./return.svg)

So if we have a function:
```
const squareNum = (num) => {
  return num * num;
};
```

We can refactor the function to:
```
const squareNum = num => num * num;
```
Notice the following changes:

1. The parentheses around num have been removed, since it has a single parameter.
2. The curly braces { } have been removed since the function consists of a single-line block.
3. The return keyword has been removed since the function consists of a single-line block.

