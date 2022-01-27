## 2022 React Course

One hour, a day for 30 days.

## 27th January

### Notes for JSX:
1. JSX allows us to put HTML elements in DOM without using appendChild() or createElement() method.
2. As JSX is an expression, we can use it inside of if statements and for loops, assign it to variables, accept it as arguments, or return it from functions.
3. JSX prevents XSS (cross-site-scripting) attacks popularly known as injection attacks.


### Notes for Arrow Function:
1. function keyword NOT needed
2. let/const variableName = (argument) => {function body}
3. short hand: curly braces and return keyword NOT needed, return result directly after =>
4. brackets NOT needed in SINGLE parameter function's argument
5. do NOT bind "this" (avoid for methods) or "arguments". 
6. It can NOT be used as constructors or generators (I don't know what those mean yet...)

A good suggestion from developer Lars Schöning:
1. Use function in the global scope and for Object.prototype properties.
2. Use class for object constructors.
3. Use => everywhere else


