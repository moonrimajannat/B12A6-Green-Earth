#B12A6-Green-Earth
#### 1) What is the difference between var, let, and const?
Answerr:In JavaScript, the main differences between var, let, and const are scope, reassignment, and redeclaration.
var is function-scoped, and it allows both reassignment and redeclaration.
let is block-scoped, it allows reassignment but does not allow redeclaration within the same scope.
const is block-scoped, and once a variable is assigned, it cannot be reassigned or redeclared.

#### 2) What is the difference between map(), forEach(), and filter()?
Answer: In JavaScript, map(), forEach(), and filter() are array methods, but they are used for different purposes:
forEach() → Loops through an array, runs a function for each item, but returns nothing.
map()→ Loops and creates a **new array** with transformed elements.
filter() → Loops and creates a **new array** with only elements that pass a condition.
#### 3) What are arrow functions in ES6?
Answer: Arrow functions in (ES6) are a shorter way to write functions using the `=>` syntax. They allow implicit return for single-line expressions and make code cleaner. Unlike regular functions, arrow functions don’t have their own `this` or `arguments` — they inherit from the surrounding scope. They are mainly used for callbacks, array methods, and cases where you want to keep `this` consistent.
#### 4) How does destructuring assignment work in ES6?
Answer: Destructuring assignment work in ES6 is a syntax that allows you to unpack values ​​from arrays or properties from objects into distinct variables. This provides a concise and readable way to extract data, simplifying assignments that might otherwise require multiple lines of code.It significantly enhances code clarity and efficiency in JavaScript, particularly when working with complex data structures or function arguments.
#### 5) Explain template literals in ES6. How are they different from string concatenation?
Answer: Template literals in (ES6) are strings written with backticks (`` ` ``) that allow easier string handling. They support **interpolation** (`${}`) to embed variables or expressions directly inside strings. Unlike normal concatenation, they make code cleaner and more readable. They also allow **multi-line strings** without using `\n` or `+`.
