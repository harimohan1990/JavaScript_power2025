# JavaScript
 **Beginner to Advanced JavaScript**

---

### 🟢 **Beginner Topics**
1. Introduction to JavaScript  
2. Variables (`var`, `let`, `const`)  
3. Data Types (Primitive & Reference)  
4. Operators (Arithmetic, Comparison, Logical)  
5. Conditional Statements (`if`, `else`, `switch`)  
6. Loops (`for`, `while`, `do...while`, `for...in`, `for...of`)  
7. Functions (Declaration, Expression, Arrow, IIFE)  
8. Arrays (Basics, Methods, Looping)  
9. Objects (Properties, Methods, `this`, Destructuring)

---

### 🟡 **Intermediate Topics**
10. DOM Manipulation (Selectors, Content, Styles)  
11. Events (Types, Bubbling, Delegation)  
12. ES6+ Features (Destructuring, Spread/Rest, Template Strings)  
13. Advanced Array Methods (`map`, `filter`, `reduce`, etc.)  
14. Advanced Object Concepts (Nested, Cloning, Methods)  
15. Closures  
16. Higher-Order Functions  
17. Recursion  
18. JavaScript Modules (`import/export`)

---

### 🔵 **Advanced Topics**
19. Asynchronous JavaScript (`setTimeout`, Promises, `async/await`)  
20. Fetch API and Working with REST APIs  
21. Error Handling (`try/catch`, Custom Errors)  
22. LocalStorage, SessionStorage, and Cookies  
23. ES2020+ Features (Optional Chaining, Nullish Coalescing, etc.)  
24. JavaScript Tooling (NPM, Babel, Webpack/Vite)  

---

### 🧠 **Expert Topics**
25. Object-Oriented JavaScript (Classes, Inheritance, `super`)  
26. Functional Programming Concepts  
27. Memory Management & Performance Optimization  
28. Debouncing & Throttling  
29. Design Patterns in JavaScript  
30. JavaScript Testing (Jest, TDD)  


JavaScript is a versatile and widely used programming language primarily designed for web development. It's known for its ability to bring websites to life by enabling dynamic and interactive content. Here's a quick overview to help you get started:

### Key Features of JavaScript
1. **Client-Side Language:** It runs directly in the user's browser, making webpages interactive.
2. **Lightweight:** It's relatively easy to learn and implement compared to other programming languages.
3. **Platform-Independent:** JavaScript code runs on any device with a compatible web browser.
4. **Event-Driven:** It responds to user actions like clicks, hovers, or keypresses.

### Why Learn JavaScript?
- It's one of the core technologies for web development (alongside HTML and CSS).
- You can create engaging websites, build mobile apps, and even develop server-side applications with tools like Node.js.

### Basic Syntax
Here’s an example of a simple JavaScript code snippet to show an alert:

```javascript
alert("Hello, world!");
```
JavaScript has a range of advanced features that enable developers to create sophisticated and high-performing applications. Here’s an overview of some of them:

### 1. **Asynchronous Programming**
   - JavaScript uses **Promises**, **async/await**, and **callback functions** to manage asynchronous tasks.
   - This allows you to perform operations like fetching data from an API without blocking the rest of your code.

### 2. **Closures**
   - A closure is a function that retains access to its lexical scope even when executed outside that scope. It's useful for data privacy and encapsulation.

```javascript
function outerFunction() {
    let privateVar = "I am private";
    return function innerFunction() {
        console.log(privateVar);
    };
}
const closureExample = outerFunction();
closureExample(); // Outputs: I am private
```

### 3. **Modules**
   - JavaScript ES6 introduced modules, enabling developers to organize code into reusable chunks. 
   - You can use `import` and `export` keywords for modular programming.

### 4. **Object-Oriented Programming (OOP)**
   - JavaScript supports OOP with concepts like classes, inheritance, and prototypes.
   - You can define classes and create objects to model real-world entities.

```javascript
class Animal {
    constructor(name) {
        this.name = name;
    }
    speak() {
        console.log(`${this.name} makes a noise.`);
    }
}
const dog = new Animal("Dog");
dog.speak(); // Outputs: Dog makes a noise.
```

### 5. **Event Loop**
   - JavaScript employs an event loop to handle asynchronous operations, enabling non-blocking input/output operations.

### 6. **Higher-Order Functions**
   - Functions that take other functions as arguments or return functions. Examples include `map()`, `filter()`, and `reduce()`.

### 7. **Dynamic Typing**
   - Variables are not bound to specific types, allowing flexibility in writing complex logic.

### 8. **Web APIs Integration**
   - Advanced JavaScript can interact with Web APIs such as **Geolocation**, **Canvas**, **WebSockets**, and **WebRTC**.

### 9. **Error Handling**
   - Robust error handling using `try`, `catch`, and `finally`, making code more resilient.

```javascript
try {
    let result = riskyOperation();
} catch (error) {
    console.error("An error occurred:", error);
} finally {
    console.log("Operation completed.");
}
```

### 10. **Frameworks and Libraries**
   - JavaScript works seamlessly with advanced frameworks like React, Angular, and Vue, empowering developers to build complex applications.

The history of JavaScript is a fascinating journey in the evolution of web technologies. Here's an overview of its origins and development:

### **1. Birth of JavaScript (1995)**
- JavaScript was created by Brendan Eich while he was working at Netscape Communications.
- Initially, it was developed in just 10 days and was named **Mocha**, later renamed **LiveScript**, and finally **JavaScript**.
- It was introduced as a scripting language for Netscape Navigator 2.0 to make webpages dynamic and interactive.

### **2. Early Adoption and Rivalry**
- In 1996, Microsoft developed its own version of JavaScript, called **JScript**, for Internet Explorer 3.0, starting the infamous "browser wars."
- This competition led to inconsistencies in JavaScript implementations across browsers.

### **3. Standardization (1997)**
- To address these inconsistencies, JavaScript was standardized by **ECMA International** as **ECMAScript (ES)** in 1997.
- ECMAScript 1 was the first official specification, laying the foundation for future versions.

### **4. Rise of Ajax (2000s)**
- The introduction of **Ajax (Asynchronous JavaScript and XML)** around 2005 revolutionized web development.
- It enabled dynamic, asynchronous updates to web pages without reloading them, paving the way for modern web applications.

### **5. The Modern JavaScript Era (ES6 and Beyond)**
- In 2015, ECMAScript 6 (ES6), also known as ECMAScript 2015, was released. It introduced major features like:
  - `let` and `const` for block-scoped variables.
  - Arrow functions, classes, and template literals.
  - Modules for better code organization.
- Subsequent versions added more features, such as `async/await`, optional chaining, and the nullish coalescing operator.

### **6. Node.js and Server-Side JavaScript (2009)**
- Ryan Dahl introduced **Node.js**, which enabled JavaScript to run on servers.
- This transformed JavaScript into a full-stack language, capable of handling both client-side and server-side development.

### **7. The JavaScript Ecosystem Today**
- JavaScript now powers modern frameworks like **React**, **Angular**, and **Vue**, which are the backbone of interactive web applications.
- It has extended its reach to mobile development (React Native), desktop applications (Electron), and even game development.

Thanks for sharing that! Here's a **clean and structured version** of the JavaScript / ECMAScript history and browser support timeline, great for study notes or teaching slides:

---

## 📜 JavaScript / ECMAScript History

### 🧑‍💻 **Origin**
- **1995** – JavaScript invented by **Brendan Eich** at Netscape.
- Originally created for **Netscape Navigator 2**.
- Became an **ECMA standard** in 1997 (ECMA-262).
- Mozilla continued development; last version before ES5 was **JavaScript 1.8.5**.
- Microsoft introduced **IE 4** with support for ECMAScript 1.

---

## 📅 ECMAScript Timeline & Browser Support

| Year | ECMA Version | Milestone |
|------|--------------|-----------|
| 1995 | —            | JavaScript invented |
| 1996 | —            | Netscape 2 released with JavaScript 1.0 |
| 1997 | ES1          | ECMAScript 1 released<br>IE 4 supported ES1 |
| 1998 | ES2          | ECMAScript 2 released<br>Netscape 4.2 with JS 1.3<br>IE 5 supported ES2 |
| 1999 | ES3          | ECMAScript 3 released |
| 2000 | ES3          | IE 5.5 supported ES3<br>Netscape 6.2 and Firefox 1 with JS 1.5 |
| 2008 | —            | ECMAScript 4 abandoned |
| 2009 | ES5          | ECMAScript 5 released |
| 2011 | ES5          | IE 9 supported ES5 (no `"use strict"`)<br>Firefox 4 with JS 1.8.5 |
| 2012 | ES5          | Full ES5 support: Safari 6, IE 10, Chrome 23 |
| 2013 | ES5          | Full ES5 support: Firefox 21, Opera 15 |
| 2014 | ES5          | Full ES5 support in all browsers |
| 2015 | ES6 (ES2015) | ECMAScript 6 released |
| 2016 | ES6          | Full ES6 support: Chrome 51, Opera 38, Safari 10 |
| 2017 | ES6          | Full ES6 support: Firefox 54, Edge 15 |
| 2018 | ES6          | Full ES6 support across all modern browsers |

---

## 🔖 Notes
- 🛑 **ES4 was abandoned** due to complexity and lack of consensus.
- ⚠️ **IE9 did not support** ES5’s `"use strict"` directive.
- ✅ **ES5** became the baseline for full modern JavaScript support by **2014**.
- ✅ **ES6** became widely supported by **2018**.

---

### Variables in JavaScript

A **variable** in JavaScript is a container for storing data values. It allows you to label data with a descriptive name, making it easier to manipulate and use throughout your program.

### Declaring Variables
In JavaScript, you can declare variables using three keywords:
1. **`var`** (function-scoped, older way)
2. **`let`** (block-scoped, introduced in ES6)
3. **`const`** (block-scoped, for constants that don't change)

Here’s an example of declaring variables:

```javascript
var x = 5; // Declares a variable using var
let y = 10; // Declares a variable using let
const z = 15; // Declares a constant
```

---

### Rules for Variables in JavaScript
To ensure proper usage and avoid errors, follow these basic rules when naming and declaring variables:

1. **Variable Names Must Start With:**
   - A letter (`a-z`, `A-Z`)
   - A dollar sign (`$`)
   - An underscore (`_`)
   Example: 
   ```javascript
   let name = "Alice";
   let _age = 30;
   let $salary = 5000;
   ```

2. **Subsequent Characters Can Include:**
   - Letters, digits, underscores, or dollar signs. However, the name cannot contain spaces.
   Example:
   ```javascript
   let userName123 = "John";
   ```

3. **Case Sensitivity:**
   - Variable names are case-sensitive, meaning `myVar` and `myvar` are treated as two different variables.

4. **Reserved Words:**
   - Variable names cannot be JavaScript reserved words such as `if`, `else`, `while`, `return`, or `function`.

5. **Descriptive Names:**
   - Use meaningful names for better code readability.
   Example:
   ```javascript
   let totalScore = 100;
   ```

6. **Cannot Start With a Digit:**
   - Variable names cannot begin with numbers. For example, `1name` is invalid, but `name1` is valid.

7. **Avoid Using Hyphens or Special Characters:**
   - JavaScript does not allow hyphens (`-`) or other special characters in variable names except for `$` and `_`.

8. **Reassignment Rules:**
   - Variables declared with `let` can be reassigned values.
   - Variables declared with `const` cannot be reassigned.
   Example:
   ```javascript
   let x = 10;
   x = 20; // Valid with let

   const y = 30;
   y = 40; // Error: Assignment to constant variable
   ```

### 💬 JavaScript Comments

Comments in JavaScript are used to make the code more readable and to explain what the code is doing. Comments are **ignored by the JavaScript engine**, so they don’t affect how the program runs.

---

### ✅ **Types of Comments**

#### 1. **Single-line Comment**
Use `//` to write comments on a single line.

```javascript
// This is a single-line comment
let x = 10; // This comment is after a statement
```

---

#### 2. **Multi-line Comment**
Use `/* */` to write comments that span multiple lines.

```javascript
/*
This is a multi-line comment.
You can write across several lines.
Useful for documentation or disabling blocks of code.
*/
let y = 20;
```

---

### 💡 Best Practices
- Use comments to explain *why*, not *what* the code is doing (the *what* should be clear from good naming).
- Avoid over-commenting; it can clutter the code.
- Use comments to mark **TODOs** or **FIXMEs**:

```javascript
// TODO: Optimize this function later
// FIXME: Handle null values here
```

---

---

## 🔢 JavaScript Data Types – Complete Guide

JavaScript values are categorized into two major types:

---

## 🟢 1. **Primitive Data Types**

> Primitives are **immutable**, stored by **value**, and directly located in the **stack**.

### 🔹 A. `String`
- Represents text
- Enclosed in `'`, `"`, or backticks `` ` ``
- Immutable: operations return a new string

```javascript
let name = "Alice";
let greeting = `Hello, ${name}`; // Template literal
```

**Common Methods**: `.length`, `.toUpperCase()`, `.includes()`, `.slice()`

---

### 🔹 B. `Number`
- Represents both **integers** and **floats**
- Based on IEEE-754 double-precision floating point

```javascript
let age = 25;
let pi = 3.1415;
```

**Special values**:
- `Infinity`, `-Infinity`, `NaN` (Not a Number)

**Common Methods**: `Math.round()`, `parseInt()`, `Number.isNaN()`

---

### 🔹 C. `Boolean`
- Represents `true` or `false`

```javascript
let isLoggedIn = true;
```

Often used in conditions:
```javascript
if (isLoggedIn) { ... }
```

---

### 🔹 D. `Undefined`
- A variable that has been declared but not assigned

```javascript
let x;
console.log(x); // undefined
```

---

### 🔹 E. `Null`
- Represents **intentional absence** of value

```javascript
let user = null;
```

> typeof `null` is `"object"` (quirk in JavaScript)

---

### 🔹 F. `BigInt` (ES2020)
- For integers larger than `Number.MAX_SAFE_INTEGER`

```javascript
let big = 1234567890123456789012345678901234567890n;
```

> Cannot mix `BigInt` and `Number` types directly.

---

### 🔹 G. `Symbol` (ES6)
- Used for **unique identifiers**, especially in objects

```javascript
let id = Symbol("userID");
let user = {
  [id]: 123
};
```

> Symbols are not enumerable in loops like `for...in`.

---

## 🟠 2. **Reference Data Types**

> Reference types are **mutable**, stored by **reference**, and located in the **heap**.

---

### 🔸 A. `Object`
- Collection of key-value pairs
- Keys are strings or symbols

```javascript
let person = {
  name: "John",
  age: 30,
  greet: function() {
    console.log("Hello!");
  }
};
```

**Access**: `person.name` or `person["name"]`

---

### 🔸 B. `Array`
- Ordered list of values (indexed from 0)
- Technically an object with numeric keys

```javascript
let colors = ["red", "green", "blue"];
```

**Common Methods**: `.push()`, `.pop()`, `.map()`, `.filter()`, `.reduce()`

---

### 🔸 C. `Function`
- Callable objects
- Can be assigned to variables, passed, and returned

```javascript
function greet(name) {
  return `Hello, ${name}`;
}
```

> Functions are **first-class citizens** in JavaScript.

---

### 🔸 D. `Date`
- For working with dates and times

```javascript
let now = new Date();
```

**Common Methods**: `.getFullYear()`, `.toISOString()`

---

### 🔸 E. `RegExp`
- Regular expressions for pattern matching

```javascript
let pattern = /[a-z]+/i;
pattern.test("Hello"); // true
```

---

### 🔸 F. `Map`
- Key-value store where **keys can be any type**

```javascript
let map = new Map();
map.set("name", "Alice");
map.set(42, "The answer");
```

---

### 🔸 G. `Set`
- Collection of **unique values**

```javascript
let set = new Set([1, 2, 3, 3]); // Set {1, 2, 3}
```

---

### 🔸 H. `WeakMap` / `WeakSet`
- Like `Map` / `Set` but with **weak references**
- Used for memory-efficient object keys

---

## 📌 Type Detection with `typeof`

```javascript
typeof "hello"    // "string"
typeof 123        // "number"
typeof null       // "object" (bug)
typeof []         // "object"
typeof {}         // "object"
typeof function(){} // "function"
```

Use `Array.isArray()` to check arrays:
```javascript
Array.isArray([]); // true
```

Use `instanceof` or `constructor.name` for deeper type checks.

---

## 🧠 Summary Table

| Type      | Category   | `typeof` Result |
|-----------|------------|-----------------|
| `"Hello"` | Primitive  | `"string"`      |
| `42`      | Primitive  | `"number"`      |
| `true`    | Primitive  | `"boolean"`     |
| `undefined` | Primitive | `"undefined"` |
| `null`    | Primitive  | `"object"` (quirk) |
| `123n`    | Primitive  | `"bigint"`      |
| `Symbol()`| Primitive  | `"symbol"`      |
| `{}`      | Reference  | `"object"`      |
| `[]`      | Reference  | `"object"`      |
| `function() {}` | Reference | `"function"` |

---

### Operators in JavaScript

JavaScript provides various operators to perform operations on variables and values. These operators can be classified into several categories based on their usage. Here's a deep dive into **all types of operators** with examples:

---

### **1. Arithmetic Operators**
These operators are used to perform mathematical operations:

| Operator | Description        | Example              | Result |
|----------|--------------------|----------------------|--------|
| `+`      | Addition           | `5 + 3`             | `8`    |
| `-`      | Subtraction        | `10 - 4`            | `6`    |
| `*`      | Multiplication     | `7 * 2`             | `14`   |
| `/`      | Division           | `15 / 5`            | `3`    |
| `%`      | Modulus (remainder)| `10 % 3`            | `1`    |
| `++`     | Increment          | `let x = 5; x++;`   | `6`    |
| `--`     | Decrement          | `let y = 10; y--;`  | `9`    |

---

### **2. Assignment Operators**
Used to assign values to variables:

| Operator | Description                       | Example            |
|----------|-----------------------------------|--------------------|
| `=`      | Assignment                       | `let a = 10;`      |
| `+=`     | Addition assignment              | `a += 5; // a = 15`|
| `-=`     | Subtraction assignment           | `a -= 3; // a = 7` |
| `*=`     | Multiplication assignment        | `a *= 2; // a = 20`|
| `/=`     | Division assignment              | `a /= 4; // a = 5` |
| `%=`     | Modulus assignment               | `a %= 6; // a = 4` |

---

### **3. Comparison Operators**
These operators compare two values and return a Boolean (`true` or `false`):

| Operator   | Description                  | Example                  | Result |
|------------|------------------------------|--------------------------|--------|
| `==`       | Equal to                     | `5 == "5"`              | `true` |
| `===`      | Strict equal to (type+value) | `5 === "5"`             | `false`|
| `!=`       | Not equal to                 | `5 != 8`                | `true` |
| `!==`      | Strict not equal to          | `5 !== "5"`             | `true` |
| `>`        | Greater than                 | `8 > 5`                 | `true` |
| `<`        | Less than                    | `3 < 7`                 | `true` |
| `>=`       | Greater than or equal to     | `5 >= 5`                | `true` |
| `<=`       | Less than or equal to        | `4 <= 6`                | `true` |

---

### **4. Logical Operators**
These are used to combine multiple conditions:

| Operator | Description           | Example                              | Result |
|----------|-----------------------|--------------------------------------|--------|
| `&&`     | Logical AND           | `(5 > 3 && 8 > 6)`                  | `true` |
| `||`     | Logical OR            | `(5 > 3 || 8 < 6)`                  | `true` |
| `!`      | Logical NOT           | `!(5 > 3)`                          | `false`|

---

### **5. Bitwise Operators**
Operate at the binary level:

| Operator | Description           | Example                    | Result      |
|----------|-----------------------|----------------------------|-------------|
| `&`      | AND                   | `5 & 1`                    | `1`         |
| `|`      | OR                    | `5 | 1`                    | `5`         |
| `^`      | XOR                   | `5 ^ 1`                    | `4`         |
| `~`      | NOT                   | `~5`                       | `-6`        |
| `<<`     | Left shift            | `5 << 1`                   | `10`        |
| `>>`     | Right shift           | `5 >> 1`                   | `2`         |

---

### **6. Ternary Operator**
A shorthand for `if-else`:

```javascript
let age = 20;
let canVote = age >= 18 ? "Yes" : "No";
console.log(canVote); // Outputs: Yes
```

---

### **7. Type Operators**
These operators help determine the type of a variable or perform type conversions:

| Operator        | Description                          | Example               | Result          |
|------------------|--------------------------------------|-----------------------|-----------------|
| `typeof`        | Returns the type of a variable       | `typeof "hello"`      | `"string"`      |
| `instanceof`    | Checks if an object is an instance   | `[] instanceof Array` | `true`          |

---

### **8. Special Operators**
#### Spread/Rest Operator (`...`)
Used to expand or merge arrays/objects:
```javascript
let numbers = [1, 2, 3];
let expanded = [...numbers, 4, 5];
console.log(expanded); // Outputs: [1, 2, 3, 4, 5]
```

#### `in` Operator
Checks if a property exists in an object:
```javascript
let obj = {name: "Alice", age: 30};
console.log("name" in obj); // Outputs: true
```

#### `delete` Operator
Deletes a property:
```javascript
delete obj.age;
console.log(obj); // Outputs: {name: "Alice"}
```

---

### **Advanced Examples**
**Short-Circuit Evaluation:**
Logical operators can short-circuit evaluations:
```javascript
let result = true || false; // Stops at true, result = true
```

**Optional Chaining (`?.`):**
Access nested properties safely:
```javascript
let user = {name: "John"};
console.log(user.address?.city); // Outputs: undefined (without error)
```

---

### Operators in JavaScript

JavaScript provides various operators to perform operations on variables and values. These operators can be classified into several categories based on their usage. Here's a deep dive into **all types of operators** with examples:

---

### **1. Arithmetic Operators**
These operators are used to perform mathematical operations:

| Operator | Description        | Example              | Result |
|----------|--------------------|----------------------|--------|
| `+`      | Addition           | `5 + 3`             | `8`    |
| `-`      | Subtraction        | `10 - 4`            | `6`    |
| `*`      | Multiplication     | `7 * 2`             | `14`   |
| `/`      | Division           | `15 / 5`            | `3`    |
| `%`      | Modulus (remainder)| `10 % 3`            | `1`    |
| `++`     | Increment          | `let x = 5; x++;`   | `6`    |
| `--`     | Decrement          | `let y = 10; y--;`  | `9`    |

---

### **2. Assignment Operators**
Used to assign values to variables:

| Operator | Description                       | Example            |
|----------|-----------------------------------|--------------------|
| `=`      | Assignment                       | `let a = 10;`      |
| `+=`     | Addition assignment              | `a += 5; // a = 15`|
| `-=`     | Subtraction assignment           | `a -= 3; // a = 7` |
| `*=`     | Multiplication assignment        | `a *= 2; // a = 20`|
| `/=`     | Division assignment              | `a /= 4; // a = 5` |
| `%=`     | Modulus assignment               | `a %= 6; // a = 4` |

---

### **3. Comparison Operators**
These operators compare two values and return a Boolean (`true` or `false`):

| Operator   | Description                  | Example                  | Result |
|------------|------------------------------|--------------------------|--------|
| `==`       | Equal to                     | `5 == "5"`              | `true` |
| `===`      | Strict equal to (type+value) | `5 === "5"`             | `false`|
| `!=`       | Not equal to                 | `5 != 8`                | `true` |
| `!==`      | Strict not equal to          | `5 !== "5"`             | `true` |
| `>`        | Greater than                 | `8 > 5`                 | `true` |
| `<`        | Less than                    | `3 < 7`                 | `true` |
| `>=`       | Greater than or equal to     | `5 >= 5`                | `true` |
| `<=`       | Less than or equal to        | `4 <= 6`                | `true` |

---

### **4. Logical Operators**
These are used to combine multiple conditions:

| Operator | Description           | Example                              | Result |
|----------|-----------------------|--------------------------------------|--------|
| `&&`     | Logical AND           | `(5 > 3 && 8 > 6)`                  | `true` |
| `||`     | Logical OR            | `(5 > 3 || 8 < 6)`                  | `true` |
| `!`      | Logical NOT           | `!(5 > 3)`                          | `false`|

---

### **5. Bitwise Operators**
Operate at the binary level:

| Operator | Description           | Example                    | Result      |
|----------|-----------------------|----------------------------|-------------|
| `&`      | AND                   | `5 & 1`                    | `1`         |
| `|`      | OR                    | `5 | 1`                    | `5`         |
| `^`      | XOR                   | `5 ^ 1`                    | `4`         |
| `~`      | NOT                   | `~5`                       | `-6`        |
| `<<`     | Left shift            | `5 << 1`                   | `10`        |
| `>>`     | Right shift           | `5 >> 1`                   | `2`         |

---

### **6. Ternary Operator**
A shorthand for `if-else`:

```javascript
let age = 20;
let canVote = age >= 18 ? "Yes" : "No";
console.log(canVote); // Outputs: Yes
```

---

### **7. Type Operators**
These operators help determine the type of a variable or perform type conversions:

| Operator        | Description                          | Example               | Result          |
|------------------|--------------------------------------|-----------------------|-----------------|
| `typeof`        | Returns the type of a variable       | `typeof "hello"`      | `"string"`      |
| `instanceof`    | Checks if an object is an instance   | `[] instanceof Array` | `true`          |

---

### **8. Special Operators**
#### Spread/Rest Operator (`...`)
Used to expand or merge arrays/objects:
```javascript
let numbers = [1, 2, 3];
let expanded = [...numbers, 4, 5];
console.log(expanded); // Outputs: [1, 2, 3, 4, 5]
```

#### `in` Operator
Checks if a property exists in an object:
```javascript
let obj = {name: "Alice", age: 30};
console.log("name" in obj); // Outputs: true
```

#### `delete` Operator
Deletes a property:
```javascript
delete obj.age;
console.log(obj); // Outputs: {name: "Alice"}
```

---

### **Advanced Examples**
**Short-Circuit Evaluation:**
Logical operators can short-circuit evaluations:
```javascript
let result = true || false; // Stops at true, result = true
```

**Optional Chaining (`?.`):**
Access nested properties safely:
```javascript
let user = {name: "John"};
console.log(user.address?.city); // Outputs: undefined (without error)
```

---

Operators in JavaScript
JavaScript provides various operators to perform operations on variables and values. These operators can be classified into several categories based on their usage. Here's a deep dive into all types of operators with examples:

1. Arithmetic Operators
These operators are used to perform mathematical operations:

Operator	Description	Example	Result
+	Addition	5 + 3	8
-	Subtraction	10 - 4	6
*	Multiplication	7 * 2	14
/	Division	15 / 5	3
%	Modulus (remainder)	10 % 3	1
++	Increment	let x = 5; x++;	6
--	Decrement	let y = 10; y--;	9
2. Assignment Operators
Used to assign values to variables:

Operator	Description	Example
=	Assignment	let a = 10;
+=	Addition assignment	a += 5; // a = 15
-=	Subtraction assignment	a -= 3; // a = 7
*=	Multiplication assignment	a *= 2; // a = 20
/=	Division assignment	a /= 4; // a = 5
%=	Modulus assignment	a %= 6; // a = 4
3. Comparison Operators
These operators compare two values and return a Boolean (true or false):

Operator	Description	Example	Result
==	Equal to	5 == "5"	true
===	Strict equal to (type+value)	5 === "5"	false
!=	Not equal to	5 != 8	true
!==	Strict not equal to	5 !== "5"	true
>	Greater than	8 > 5	true
<	Less than	3 < 7	true
>=	Greater than or equal to	5 >= 5	true
<=	Less than or equal to	4 <= 6	true
4. Logical Operators
These are used to combine multiple conditions:

Operator	Description	Example	Result
&&	Logical AND	(5 > 3 && 8 > 6)	true
`		`	Logical OR	`(5 > 3		8 < 6)`	true
!	Logical NOT	!(5 > 3)	false
5. Bitwise Operators
Operate at the binary level:

Operator	Description	Example	Result
&	AND	5 & 1	1
`	`	OR	`5	1`	5
^	XOR	5 ^ 1	4
~	NOT	~5	-6
<<	Left shift	5 << 1	10
>>	Right shift	5 >> 1	2
6. Ternary Operator
A shorthand for if-else:

javascript
let age = 20;
let canVote = age >= 18 ? "Yes" : "No";
console.log(canVote); // Outputs: Yes
7. Type Operators
These operators help determine the type of a variable or perform type conversions:




### Operators in JavaScript

JavaScript provides various operators to perform operations on variables and values. These operators can be classified into several categories based on their usage. Here's a deep dive into **all types of operators** with examples:

---

### **1. Arithmetic Operators**
These operators are used to perform mathematical operations:

| Operator | Description        | Example              | Result |
|----------|--------------------|----------------------|--------|
| `+`      | Addition           | `5 + 3`             | `8`    |
| `-`      | Subtraction        | `10 - 4`            | `6`    |
| `*`      | Multiplication     | `7 * 2`             | `14`   |
| `/`      | Division           | `15 / 5`            | `3`    |
| `%`      | Modulus (remainder)| `10 % 3`            | `1`    |
| `++`     | Increment          | `let x = 5; x++;`   | `6`    |
| `--`     | Decrement          | `let y = 10; y--;`  | `9`    |

---

### **2. Assignment Operators**
Used to assign values to variables:

| Operator | Description                       | Example            |
|----------|-----------------------------------|--------------------|
| `=`      | Assignment                       | `let a = 10;`      |
| `+=`     | Addition assignment              | `a += 5; // a = 15`|
| `-=`     | Subtraction assignment           | `a -= 3; // a = 7` |
| `*=`     | Multiplication assignment        | `a *= 2; // a = 20`|
| `/=`     | Division assignment              | `a /= 4; // a = 5` |
| `%=`     | Modulus assignment               | `a %= 6; // a = 4` |

---

### **3. Comparison Operators**
These operators compare two values and return a Boolean (`true` or `false`):

| Operator   | Description                  | Example                  | Result |
|------------|------------------------------|--------------------------|--------|
| `==`       | Equal to                     | `5 == "5"`              | `true` |
| `===`      | Strict equal to (type+value) | `5 === "5"`             | `false`|
| `!=`       | Not equal to                 | `5 != 8`                | `true` |
| `!==`      | Strict not equal to          | `5 !== "5"`             | `true` |
| `>`        | Greater than                 | `8 > 5`                 | `true` |
| `<`        | Less than                    | `3 < 7`                 | `true` |
| `>=`       | Greater than or equal to     | `5 >= 5`                | `true` |
| `<=`       | Less than or equal to        | `4 <= 6`                | `true` |

---

### **4. Logical Operators**
These are used to combine multiple conditions:

| Operator | Description           | Example                              | Result |
|----------|-----------------------|--------------------------------------|--------|
| `&&`     | Logical AND           | `(5 > 3 && 8 > 6)`                  | `true` |
| `||`     | Logical OR            | `(5 > 3 || 8 < 6)`                  | `true` |
| `!`      | Logical NOT           | `!(5 > 3)`                          | `false`|

---

### **5. Bitwise Operators**
Operate at the binary level:

| Operator | Description           | Example                    | Result      |
|----------|-----------------------|----------------------------|-------------|
| `&`      | AND                   | `5 & 1`                    | `1`         |
| `|`      | OR                    | `5 | 1`                    | `5`         |
| `^`      | XOR                   | `5 ^ 1`                    | `4`         |
| `~`      | NOT                   | `~5`                       | `-6`        |
| `<<`     | Left shift            | `5 << 1`                   | `10`        |
| `>>`     | Right shift           | `5 >> 1`                   | `2`         |

---

### **6. Ternary Operator**
A shorthand for `if-else`:

```javascript
let age = 20;
let canVote = age >= 18 ? "Yes" : "No";
console.log(canVote); // Outputs: Yes
```

---

### **7. Type Operators**
These operators help determine the type of a variable or perform type conversions:

| Operator        | Description                          | Example               | Result          |
|------------------|--------------------------------------|-----------------------|-----------------|
| `typeof`        | Returns the type of a variable       | `typeof "hello"`      | `"string"`      |
| `instanceof`    | Checks if an object is an instance   | `[] instanceof Array` | `true`          |

---

### **8. Special Operators**
#### Spread/Rest Operator (`...`)
Used to expand or merge arrays/objects:
```javascript
let numbers = [1, 2, 3];
let expanded = [...numbers, 4, 5];
console.log(expanded); // Outputs: [1, 2, 3, 4, 5]
```

#### `in` Operator
Checks if a property exists in an object:
```javascript
let obj = {name: "Alice", age: 30};
console.log("name" in obj); // Outputs: true
```

#### `delete` Operator
Deletes a property:
```javascript
delete obj.age;
console.log(obj); // Outputs: {name: "Alice"}
```

---

### **Advanced Examples**
**Short-Circuit Evaluation:**
Logical operators can short-circuit evaluations:
```javascript
let result = true || false; // Stops at true, result = true
```

**Optional Chaining (`?.`):**
Access nested properties safely:
```javascript
let user = {name: "John"};
console.log(user.address?.city); // Outputs: undefined (without error)
```

---

7. Type Operators
These operators help determine the type of a variable or perform type conversions:

Operator	Description	Example	Result
typeof	Returns the type of a variable	typeof "hello"	"string"
instanceof	Checks if an object is an instance	[] instanceof Array	true
8. Special Operators
Spread/Rest Operator (...)
Used to expand or merge arrays/objects:

javascript
let numbers = [1, 2, 3];
let expanded = [...numbers, 4, 5];
console.log(expanded); // Outputs: [1, 2, 3, 4, 5]
in Operator
Checks if a property exists in an object:

javascript
let obj = {name: "Alice", age: 30};
console.log("name" in obj); // Outputs: true
delete Operator
Deletes a property:

javascript
delete obj.age;
console.log(obj); // Outputs: {name: "Alice"}
Advanced Examples
Short-Circuit Evaluation: Logical operators can short-circuit evaluations:

javascript
let result = true || false; // Stops at true, result = true
Optional Chaining (?.): Access nested properties safely:

javascript
let user = {name: "John"};
console.log(user.address?.city); // Outputs: undefined (without error)

Here's a **complete guide to conditional statements** in JavaScript, including `if`, `else if`, `else`, and `switch`, with **multiple examples** and real use cases:

---

## 🔀 JavaScript Conditional Statements

Used to **perform different actions** based on different conditions.

---

### ✅ 1. `if` Statement

Executes a block if the condition is **true**.

```javascript
let age = 18;

if (age >= 18) {
  console.log("You are an adult.");
}
```

---

### ✅ 2. `if...else` Statement

Executes one block if true, another if false.

```javascript
let score = 45;

if (score >= 50) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

---

### ✅ 3. `if...else if...else`

Checks **multiple conditions** in order.

```javascript
let marks = 85;

if (marks >= 90) {
  console.log("Grade A");
} else if (marks >= 75) {
  console.log("Grade B");
} else if (marks >= 60) {
  console.log("Grade C");
} else {
  console.log("Fail");
}
```

---

### ✅ 4. Nested `if` Statements

You can place `if` inside another `if`.

```javascript
let isLoggedIn = true;
let isAdmin = false;

if (isLoggedIn) {
  if (isAdmin) {
    console.log("Welcome, Admin");
  } else {
    console.log("Welcome, User");
  }
} else {
  console.log("Please log in.");
}
```

---

## 🔁 5. `switch` Statement

Used when you have **multiple exact values** to match.

```javascript
let fruit = "apple";

switch (fruit) {
  case "banana":
    console.log("Banana is yellow");
    break;
  case "apple":
    console.log("Apple is red");
    break;
  case "grape":
    console.log("Grape is purple");
    break;
  default:
    console.log("Unknown fruit");
}
```

> Always use `break` to prevent **fall-through** to the next case.

---

### 🔁 Example: Grouping Cases

```javascript
let day = 3;

switch (day) {
  case 1:
  case 2:
  case 3:
  case 4:
  case 5:
    console.log("Weekday");
    break;
  case 6:
  case 7:
    console.log("Weekend");
    break;
  default:
    console.log("Invalid day");
}
```

---

### 🔁 Example: Switch with Boolean (trick)

```javascript
let score = 85;

switch (true) {
  case score >= 90:
    console.log("A");
    break;
  case score >= 75:
    console.log("B");
    break;
  case score >= 60:
    console.log("C");
    break;
  default:
    console.log("F");
}
```

---

## ⚡ Tip: Ternary Operator (Short `if...else`)
```javascript
let age = 20;
let message = age >= 18 ? "Adult" : "Minor";
console.log(message); // Adult
```

Sure! Here's a breakdown of all **JavaScript loop types** with **two examples each** for better understanding:

---

## 🔁 1. **`for` Loop**

### Example 1: Count from 1 to 5
```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
// Output: 1 2 3 4 5
```

### Example 2: Loop through array indexes
```javascript
const colors = ['red', 'green', 'blue'];
for (let i = 0; i < colors.length; i++) {
  console.log(colors[i]);
}
// Output: red green blue
```

---

## 🔁 2. **`while` Loop**

### Example 1: Count down from 5
```javascript
let i = 5;
while (i > 0) {
  console.log(i);
  i--;
}
// Output: 5 4 3 2 1
```

### Example 2: Print even numbers < 10
```javascript
let num = 0;
while (num < 10) {
  if (num % 2 === 0) console.log(num);
  num++;
}
// Output: 0 2 4 6 8
```

---

## 🔁 3. **`do...while` Loop**

### Example 1: Run at least once
```javascript
let count = 10;
do {
  console.log('Runs once even if condition is false');
} while (count < 5);
// Output: Runs once even if condition is false
```

### Example 2: Print numbers 1 to 3
```javascript
let i = 1;
do {
  console.log(i);
  i++;
} while (i <= 3);
// Output: 1 2 3
```

---

## 🔁 4. **`for...of` Loop** (Arrays / Iterables)

### Example 1: Loop over string characters
```javascript
for (const char of 'JS') {
  console.log(char);
}
// Output: J S
```

### Example 2: Sum array values
```javascript
const nums = [10, 20, 30];
let total = 0;
for (const num of nums) {
  total += num;
}
console.log(total);
// Output: 60
```

---

## 🔁 5. **`for...in` Loop** (Objects)

### Example 1: Print object properties
```javascript
const user = { name: 'Sam', age: 30 };
for (const key in user) {
  console.log(key, user[key]);
}
// Output: name Sam, age 30
```

### Example 2: Count number of properties
```javascript
const obj = { a: 1, b: 2, c: 3 };
let count = 0;
for (const key in obj) {
  count++;
}
console.log(count);
// Output: 3
```
 ### array methods along with examples for each. 

### 1. `push()`
Adds one or more elements to the end of an array and returns the new length of the array.

```javascript
let fruits = ['apple', 'banana'];
fruits.push('orange');
console.log(fruits); // Output: ['apple', 'banana', 'orange']
```

### 2. `pop()`
Removes the last element from an array and returns that element.

```javascript
let fruits = ['apple', 'banana', 'orange'];
let lastFruit = fruits.pop();
console.log(lastFruit); // Output: 'orange'
console.log(fruits); // Output: ['apple', 'banana']
```

### 3. `shift()`
Removes the first element from an array and returns that element.

```javascript
let fruits = ['apple', 'banana', 'orange'];
let firstFruit = fruits.shift();
console.log(firstFruit); // Output: 'apple'
console.log(fruits); // Output: ['banana', 'orange']
```

### 4. `unshift()`
Adds one or more elements to the beginning of an array and returns the new length of the array.

```javascript
let fruits = ['banana', 'orange'];
fruits.unshift('apple');
console.log(fruits); // Output: ['apple', 'banana', 'orange']
```

### 5. `splice()`
Changes the contents of an array by removing or replacing existing elements and/or adding new elements.

```javascript
let fruits = ['apple', 'banana', 'orange'];
fruits.splice(1, 1, 'kiwi'); // Remove 1 element at index 1 and add 'kiwi'
console.log(fruits); // Output: ['apple', 'kiwi', 'orange']
```

### 6. `slice()`
Returns a shallow copy of a portion of an array into a new array object.

```javascript
let fruits = ['apple', 'banana', 'orange', 'kiwi'];
let citrus = fruits.slice(1, 3); // From index 1 to 3 (not including 3)
console.log(citrus); // Output: ['banana', 'orange']
```

### 7. `forEach()`
Executes a provided function once for each array element.

```javascript
let fruits = ['apple', 'banana', 'orange'];
fruits.forEach(fruit => {
    console.log(fruit);
});
// Output:
// apple
// banana
// orange
```

### 8. `map()`
Creates a new array populated with the results of calling a provided function on every element in the calling array.

```javascript
let numbers = [1, 2, 3];
let doubled = numbers.map(num => num * 2);
console.log(doubled); // Output: [2, 4, 6]
```

### 9. `filter()`
Creates a new array with all elements that pass the test implemented by the provided function.

```javascript
let numbers = [1, 2, 3, 4, 5];
let evens = numbers.filter(num => num % 2 === 0);
console.log(evens); // Output: [2, 4]
```

### 10. `reduce()`
Executes a reducer function on each element of the array, resulting in a single output value.

```javascript
let numbers = [1, 2, 3, 4];
let sum = numbers.reduce((accumulator, current) => accumulator + current, 0);
console.log(sum); // Output: 10
```

### 11. `every()`
Tests whether all elements in the array pass the test implemented by the provided function.

```javascript
let numbers = [1, 2, 3, 4];
let allPositive = numbers.every(num => num > 0);
console.log(allPositive); // Output: true
```

### 12. `some()`
Tests whether at least one element in the array passes the test implemented by the provided function.

```javascript
let numbers = [1, -2, 3, 4];
let hasNegative = numbers.some(num => num < 0);
console.log(hasNegative); // Output: true
```

### 13. `find()`
Returns the value of the first element in the provided array that satisfies the provided testing function.

```javascript
let numbers = [5, 12, 8, 130, 44];
let found = numbers.find(num => num > 10);
console.log(found); // Output: 12
```

### 14. `findIndex()`
Returns the index of the first element in the array that satisfies the provided testing function.

```javascript
let numbers = [5, 12, 8, 130, 44];
let index = numbers.findIndex(num => num > 10);
console.log(index); // Output: 1
```

### 15. `includes()`
Determines whether an array includes a certain value among its entries.

```javascript
let fruits = ['apple', 'banana', 'orange'];
let hasBanana = fruits.includes('banana');
console.log(hasBanana); // Output: true
```

### 16. `sort()`
Sorts the elements of an array in place and returns the sorted array.

```javascript
let numbers = [4, 2, 5, 1, 3];
numbers.sort();
console.log(numbers); // Output: [1, 2, 3, 4, 5]
```

### 17. `reverse()`
Reverses the elements of an array in place.

```javascript
let numbers = [1, 2, 3];
numbers.reverse();
console.log(numbers); // Output: [3, 2, 1]
```

### 18. `join()`
Joins all elements of an array into a string.

```javascript
let fruits = ['apple', 'banana', 'orange'];
let fruitString = fruits.join(', ');
console.log(fruitString); // Output: 'apple, banana, orange'
```

### 19. `concat()`
Used to merge two or more arrays.

```javascript
let fruits1 = ['apple', 'banana'];
let fruits2 = ['orange', 'kiwi'];
let allFruits = fruits1.concat(fruits2);
console.log(allFruits); // Output: ['apple', 'banana', 'orange', 'kiwi']
```

### 20. `flat()`
Creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.

```javascript
let nestedArray = [1, 2, [3, 4, [5, 6]]];
let flatArray = nestedArray.flat(2);
console.log(flatArray); // Output: [1, 2, 3, 4, 5, 6]
```

### 21. `flatMap()`
Maps each element using a mapping function, then flattens the result into a new array.

```javascript
let arr = [1, 2, 3];
let flattened = arr.flatMap(x => [x, x * 2]);
console.log(flattened); // Output: [1, 2, 2, 4, 3, 6]
```

### 22. `from()`
Creates a new, shallow-copied Array instance from an array-like or iterable object.

```javascript
let str = 'hello';
let chars = Array.from(str);
console.log(chars); // Output: ['h', 'e', 'l', 'l', 'o']
```

### 23. `isArray()`
Determines whether the passed value is an Array.

```javascript
console.log(Array.isArray([1, 2, 3])); // Output: true
console.log(Array.isArray('hello')); // Output: false
```

### 24. `fill()`
Fills all the elements of an array from a start index to an end index with a static value.

```javascript
let arr = new Array(3).fill(5);
console.log(arr); // Output: [5, 5, 5]
```

### 25. `copyWithin()`
Shallow copies part of an array to another location in the same array and returns it.

```javascript
let arr = [1, 2, 3, 4, 5];
arr.copyWithin(0, 3);
console.log(arr); // Output: [4, 5, 3, 4, 5]
```

### 26. `keys()`
Returns a new Array Iterator object that contains the keys for each index in the array.

```javascript
let arr = ['a', 'b', 'c'];
let keys = arr.keys();
for (let key of keys) {
    console.log(key); // Output: 0, 1, 2
}
```

### 27. `values()`
Returns a new Array Iterator object that contains the values for each index in the array.

```javascript
let arr = ['a', 'b', 'c'];
let values = arr.values();
for (let value of values) {
    console.log(value); // Output: 'a', 'b', 'c'
}
```

### 28. `entries()`
Returns a new Array Iterator object that contains the key/value pairs for each index in the array.

```javascript
let arr = ['a', 'b', 'c'];
let entries = arr.entries();
for (let entry of entries) {
    console.log(entry); // Output: [0, 'a'], [1, 'b'], [2, 'c']
}
```


 ### JavaScript string methods along with examples for each:

### 1. `charAt()`
Returns the character at a specified index.

```javascript
let str = "Hello";
console.log(str.charAt(1)); // Output: 'e'
```

### 2. `charCodeAt()`
Returns the Unicode of the character at a specified index.

```javascript
let str = "Hello";
console.log(str.charCodeAt(1)); // Output: 101 (Unicode for 'e')
```

### 3. `concat()`
Joins two or more strings and returns a new string.

```javascript
let str1 = "Hello";
let str2 = "World";
let result = str1.concat(" ", str2);
console.log(result); // Output: 'Hello World'
```

### 4. `includes()`
Determines whether a string contains the characters of a specified string.

```javascript
let str = "Hello World";
console.log(str.includes("World")); // Output: true
```

### 5. `indexOf()`
Returns the index of the first occurrence of a specified value in a string.

```javascript
let str = "Hello World";
console.log(str.indexOf("o")); // Output: 4
```

### 6. `lastIndexOf()`
Returns the index of the last occurrence of a specified value in a string.

```javascript
let str = "Hello World";
console.log(str.lastIndexOf("o")); // Output: 7
```

### 7. `slice()`
Extracts a section of a string and returns it as a new string.

```javascript
let str = "Hello World";
console.log(str.slice(0, 5)); // Output: 'Hello'
```

### 8. `substring()`
Returns a subset of a string between two indices.

```javascript
let str = "Hello World";
console.log(str.substring(0, 5)); // Output: 'Hello'
```

### 9. `toLowerCase()`
Returns the calling string value converted to lowercase.

```javascript
let str = "Hello World";
console.log(str.toLowerCase()); // Output: 'hello world'
```

### 10. `toUpperCase()`
Returns the calling string value converted to uppercase.

```javascript
let str = "Hello World";
console.log(str.toUpperCase()); // Output: 'HELLO WORLD'
```

### 11. `trim()`
Removes whitespace from both ends of a string.

```javascript
let str = "   Hello World   ";
console.log(str.trim()); // Output: 'Hello World'
```

### 12. `split()`
Splits a string into an array of substrings.

```javascript
let str = "Hello World";
let arr = str.split(" ");
console.log(arr); // Output: ['Hello', 'World']
```

### 13. `replace()`
Returns a new string with some or all matches of a pattern replaced by a replacement.

```javascript
let str = "Hello World";
let newStr = str.replace("World", "JavaScript");
console.log(newStr); // Output: 'Hello JavaScript'
```

### 14. `search()`
Executes a search for a match between a regular expression and this String object.

```javascript
let str = "Hello World";
let index = str.search("World");
console.log(index); // Output: 6
```

### 15. `match()`
Retrieves the matches when matching a string against a regular expression.

```javascript
let str = "Hello World";
let matches = str.match(/o/g);
console.log(matches); // Output: ['o', 'o']
```

### 16. `repeat()`
Constructs and returns a new string which contains the specified number of copies of the string on which it was called.

```javascript
let str = "Hello ";
let repeated = str.repeat(3);
console.log(repeated); // Output: 'Hello Hello Hello '
```

### 17. `startsWith()`
Determines whether a string begins with the characters of a specified string.

```javascript
let str = "Hello World";
console.log(str.startsWith("Hello")); // Output: true
```

### 18. `endsWith()`
Determines whether a string ends with the characters of a specified string.

```javascript
let str = "Hello World";
console.log(str.endsWith("World")); // Output: true
```

### 19. `valueOf()`
Returns the primitive value of a String object.

```javascript
let str = new String("Hello World");
console.log(str.valueOf()); // Output: 'Hello World'
```

### 20. `codePointAt()`
Returns a non-negative integer that is the Unicode code point value of the character at the given index.

```javascript
let str = "Hello";
console.log(str.codePointAt(0)); // Output: 72 (Unicode for 'H')
```

### 21. `localeCompare()`
Compares two strings in the current locale.

```javascript
let str1 = "apple";
let str2 = "banana";
console.log(str1.localeCompare(str2)); // Output: -1 (because 'apple' comes before 'banana')
```

### 22. `fromCharCode()`
Static method that returns a string created by using the specified sequence of Unicode values.

```javascript
console.log(String.fromCharCode(72, 101, 108, 108, 111)); // Output: 'Hello'
```

### object methods along with examples for each

### 1. `Object.keys()`
Returns an array of a given object's own enumerable property names.

```javascript
const obj = { name: "Alice", age: 25 };
const keys = Object.keys(obj);
console.log(keys); // Output: ['name', 'age']
```

### 2. `Object.values()`
Returns an array of a given object's own enumerable property values.

```javascript
const obj = { name: "Alice", age: 25 };
const values = Object.values(obj);
console.log(values); // Output: ['Alice', 25]
```

### 3. `Object.entries()`
Returns an array of a given object's own enumerable string-keyed property [key, value] pairs.

```javascript
const obj = { name: "Alice", age: 25 };
const entries = Object.entries(obj);
console.log(entries); // Output: [['name', 'Alice'], ['age', 25]]
```

### 4. `Object.assign()`
Copies the values of all enumerable own properties from one or more source objects to a target object.

```javascript
const target = { a: 1 };
const source = { b: 2, c: 3 };
const returnedTarget = Object.assign(target, source);
console.log(target); // Output: { a: 1, b: 2, c: 3 }
console.log(returnedTarget); // Output: { a: 1, b: 2, c: 3 }
```

### 5. `Object.freeze()`
Freezes an object, preventing new properties from being added to it and marking all existing properties as read-only.

```javascript
const obj = { name: "Alice" };
Object.freeze(obj);
obj.name = "Bob"; // This will not change the name
console.log(obj.name); // Output: 'Alice'
```

### 6. `Object.seal()`
Seals an object, preventing new properties from being added and marking all existing properties as non-configurable.

```javascript
const obj = { name: "Alice" };
Object.seal(obj);
obj.name = "Bob"; // This will change the name
obj.age = 25; // This will not add a new property
console.log(obj); // Output: { name: 'Bob' }
```

### 7. `Object.assign()` (for shallow copy)
Creates a shallow copy of an object.

```javascript
const original = { name: "Alice" };
const copy = Object.assign({}, original);
console.log(copy); // Output: { name: 'Alice' }
```

### 8. `Object.create()`
Creates a new object with the specified prototype object and properties.

```javascript
const proto = { greet() { return "Hello"; } };
const obj = Object.create(proto);
console.log(obj.greet()); // Output: 'Hello'
```

### 9. `Object.defineProperty()`
Adds a property to an object or modifies an existing property, and returns the object.

```javascript
const obj = {};
Object.defineProperty(obj, 'name', {
    value: 'Alice',
    writable: false // The property is not writable
});
console.log(obj.name); // Output: 'Alice'
obj.name = 'Bob'; // This will not change the name
console.log(obj.name); // Output: 'Alice'
```

### 10. `Object.defineProperties()`
Adds or modifies multiple properties of an object.

```javascript
const obj = {};
Object.defineProperties(obj, {
    name: {
        value: 'Alice',
        writable: false
    },
    age: {
        value: 25,
        writable: true
    }
});
console.log(obj); // Output: { name: 'Alice', age: 25 }
```

### 11. `Object.getOwnPropertyDescriptor()`
Returns a property descriptor for an own property (not inherited) of an object.

```javascript
const obj = { name: 'Alice' };
const descriptor = Object.getOwnPropertyDescriptor(obj, 'name');
console.log(descriptor); // Output: { value: 'Alice', writable: true, enumerable: true, configurable: true }
```

### 12. `Object.getOwnPropertyDescriptors()`
Returns all own property descriptors of a given object.

```javascript
const obj = { name: 'Alice' };
const descriptors = Object.getOwnPropertyDescriptors(obj);
console.log(descriptors);
// Output: { name: { value: 'Alice', writable: true, enumerable: true, configurable: true } }
```

### 13. `Object.getPrototypeOf()`
Returns the prototype of the specified object.

```javascript
const obj = {};
const proto = Object.getPrototypeOf(obj);
console.log(proto === Object.prototype); // Output: true
```

### 14. `Object.setPrototypeOf()`
Sets the prototype of a specified object to another object or null.

```javascript
const proto = { greet() { return "Hello"; } };
const obj = {};
Object.setPrototypeOf(obj, proto);
console.log(obj.greet()); // Output: 'Hello'
```

### 15. `Object.is()`
Determines whether two values are the same value.

```javascript
console.log(Object.is('foo', 'foo')); // Output: true
console.log(Object.is({}, {})); // Output: false
```

### 16. `Object.values()`
Returns an array of a given object's own enumerable property values.

```javascript
const obj = { name: "Alice", age: 25 };
console.log(Object.values(obj)); // Output: ['Alice', 25]
```

### 17. `Object.entries()`
Returns an array of a given object's own enumerable string-keyed property [key, value] pairs.

```javascript
const obj = { name: "Alice", age: 25 };
console.log(Object.entries(obj)); // Output: [['name', 'Alice'], ['age', 25]]
```

### 18. `Object.keys()`
Returns an array of a given object's own enumerable property names.

```javascript
const obj = { name: "Alice", age: 25 };
console.log(Object.keys(obj)); // Output: ['name', 'age']
```

### 19. `Object.prototype.toString()`
Returns a string representation of the object.

```javascript
const obj = {};
console.log(Object.prototype.toString.call(obj)); // Output: '[object Object]'
```

### 20. `Object.prototype.hasOwnProperty()`
Returns a boolean indicating whether the object has the specified property as its own property.

```javascript
const obj = { name: "Alice" };
console.log(obj.hasOwnProperty('name')); // Output: true
console.log(obj.hasOwnProperty('age')); // Output: false
```

 ### methods and properties associated with functions

### 1. `Function.prototype.call()`
Calls a function with a given `this` value and arguments provided individually.

```javascript
function greet() {
    return `Hello, ${this.name}`;
}

const person = { name: "Alice" };
console.log(greet.call(person)); // Output: 'Hello, Alice'
```

### 2. `Function.prototype.apply()`
Calls a function with a given `this` value and arguments provided as an array (or an array-like object).

```javascript
function greet(greeting) {
    return `${greeting}, ${this.name}`;
}

const person = { name: "Alice" };
console.log(greet.apply(person, ["Hi"])); // Output: 'Hi, Alice'
```

### 3. `Function.prototype.bind()`
Creates a new function that, when called, has its `this` keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called.

```javascript
function greet() {
    return `Hello, ${this.name}`;
}

const person = { name: "Alice" };
const greetAlice = greet.bind(person);
console.log(greetAlice()); // Output: 'Hello, Alice'
```

### 4. `Function.prototype.toString()`
Returns a string representing the source code of the function.

```javascript
function greet() {
    return "Hello!";
}

console.log(greet.toString()); // Output: 'function greet() {\n    return "Hello!";\n}'
```

### 5. `Function.prototype.length`
Represents the number of parameters expected by the function.

```javascript
function add(a, b) {
    return a + b;
}

console.log(add.length); // Output: 2
```

### 6. `Function.prototype.name`
Returns the name of the function.

```javascript
function greet() {}
console.log(greet.name); // Output: 'greet'
```

### 7. `Function.prototype.prototype`
Allows you to add properties and methods to a function's prototype, which can then be accessed by instances created from that function (when used as a constructor).

```javascript
function Person(name) {
    this.name = name;
}

Person.prototype.greet = function() {
    return `Hello, ${this.name}`;
};

const alice = new Person("Alice");
console.log(alice.greet()); // Output: 'Hello, Alice'
```

### 8. `Function.prototype.hasOwnProperty()`
Checks if the function has a specific property as its own property.

```javascript
function greet() {}
greet.customProperty = "I'm a custom property";

console.log(greet.hasOwnProperty("customProperty")); // Output: true
console.log(greet.hasOwnProperty("name")); // Output: false
```

### 9. `Function.prototype.isGenerator()`
Checks if a function is a generator function (not a standard method, but can be defined).

```javascript
function* generatorFunction() {
    yield 1;
}

console.log(generatorFunction.prototype.constructor === generatorFunction); // Output: true
```

### 10. `Function.prototype.call()` with a delay (using `setTimeout`)
Demonstrates how to use `call` with `setTimeout`.

```javascript
function greet() {
    console.log(`Hello, ${this.name}`);
}

const person = { name: "Alice" };
setTimeout(greet.call.bind(greet, person), 1000); // Output after 1 second: 'Hello, Alice'
```

### 11. `setTimeout()` and `setInterval()`
These are global functions that can be used to execute a function after a specified delay or repeatedly at specified intervals.

```javascript
function sayHello() {
    console.log("Hello!");
}

// Executes sayHello once after 2 seconds
setTimeout(sayHello, 2000); // Output after 2 seconds: 'Hello!'

// Executes sayHello every 1 second
const intervalId = setInterval(sayHello, 1000);

// To stop the interval after 5 seconds
setTimeout(() => clearInterval(intervalId), 5000); // Stops after 5 seconds
```

### 12. `Function.prototype.bind()` with partial application
You can use `bind` to create a partially applied function.

```javascript
function multiply(a, b) {
    return a * b;
}

const double = multiply.bind(null, 2);
console.log(double(5)); // Output: 10
```

### 13. `Function.prototype.then()` (for Promise functions)
This method is used with promises to handle asynchronous operations.

```javascript
const promise = new Promise((resolve, reject) => {
    setTimeout(() => resolve("Done!"), 1000);
});

promise.then(result => {
    console.log(result); // Output after 1 second: 'Done!'
});
```

### 14. `Function.prototype.catch()` (for Promise functions)
This method is used to handle errors in promises.

```javascript
const promise = new Promise((resolve, reject) => {
    setTimeout(() => reject("Error!"), 1000);
});

promise.catch(error => {
    console.log(error); // Output after 1 second: 'Error!'
});
```

### 15. `Function.prototype.finally()` (for Promise functions)
This method is used to execute code after a promise is settled, regardless of its outcome.

```javascript
const promise = new Promise((resolve, reject) => {
    setTimeout(() => resolve("Done!"), 1000);
});

promise
    .then(result => console.log(result)) // Output after 1 second: 'Done!'
    .finally(() => console.log("Promise settled.")); // Output: 'Promise settled.'
```

### JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy for humans to read and write and easy for machines to parse and generate. It is primarily used to transmit data between a server and a web application as text.

### JSON Structure

1. **Objects**: An unordered collection of key/value pairs enclosed in curly braces `{}`.
   - Example: 
     ```json
     {
         "name": "Alice",
         "age": 25,
         "isStudent": false
     }
     ```

2. **Arrays**: An ordered collection of values enclosed in square brackets `[]`.
   - Example:
     ```json
     [
         "apple",
         "banana",
         "orange"
     ]
     ```

3. **Values**: Can be strings, numbers, objects, arrays, booleans, or null.
   - Example:
     ```json
     {
         "string": "Hello",
         "number": 123,
         "boolean": true,
         "nullValue": null,
         "array": [1, 2, 3],
         "object": { "key": "value" }
     }
     ```

### JSON Example

Here is a more complex example of a JSON object representing a person:

```json
{
    "name": "Alice",
    "age": 25,
    "isStudent": false,
    "hobbies": ["reading", "traveling", "swimming"],
    "address": {
        "street": "123 Main St",
        "city": "Anytown",
        "state": "CA"
    }
}
```

### JSON Methods in JavaScript

JavaScript provides two built-in methods for working with JSON:

1. **`JSON.stringify()`**: Converts a JavaScript object or value to a JSON string.

   ```javascript
   const person = {
       name: "Alice",
       age: 25,
       isStudent: false
   };

   const jsonString = JSON.stringify(person);
   console.log(jsonString); // Output: '{"name":"Alice","age":25,"isStudent":false}'
   ```

2. **`JSON.parse()`**: Converts a JSON string to a JavaScript object.

   ```javascript
   const jsonString = '{"name":"Alice","age":25,"isStudent":false}';
   const person = JSON.parse(jsonString);
   console.log(person); // Output: { name: 'Alice', age: 25, isStudent: false }
   ```

### Use Cases for JSON

- **Data Transmission**: JSON is commonly used to transmit data between a server and a web application.
- **APIs**: Many web APIs return data in JSON format.
- **Configuration Files**: JSON is often used for configuration files due to its readability.

### Advantages of JSON

- **Lightweight**: JSON is less verbose compared to XML, making it more efficient for data transmission.
- **Human-Readable**: JSON format is easy to read and understand.
- **Language Independence**: JSON is language-agnostic and can be used across different programming languages.

### Common JSON Errors

- **Invalid Syntax**: Missing commas, braces, or brackets can lead to parsing errors.
- **Data Types**: Keys must be strings (enclosed in double quotes), and values must be valid JSON data types.

 ### `Math` methods along with examples for each

### 1. `Math.abs()`
Returns the absolute value of a number.

```javascript
console.log(Math.abs(-5)); // Output: 5
console.log(Math.abs(5));  // Output: 5
```

### 2. `Math.ceil()`
Rounds a number up to the nearest integer.

```javascript
console.log(Math.ceil(4.2)); // Output: 5
console.log(Math.ceil(-4.2)); // Output: -4
```

### 3. `Math.floor()`
Rounds a number down to the nearest integer.

```javascript
console.log(Math.floor(4.7)); // Output: 4
console.log(Math.floor(-4.7)); // Output: -5
```

### 4. `Math.round()`
Rounds a number to the nearest integer.

```javascript
console.log(Math.round(4.5)); // Output: 5
console.log(Math.round(4.4)); // Output: 4
```

### 5. `Math.max()`
Returns the largest of the given numbers.

```javascript
console.log(Math.max(1, 2, 3, 4)); // Output: 4
console.log(Math.max(-1, -2, -3)); // Output: -1
```

### 6. `Math.min()`
Returns the smallest of the given numbers.

```javascript
console.log(Math.min(1, 2, 3, 4)); // Output: 1
console.log(Math.min(-1, -2, -3)); // Output: -3
```

### 7. `Math.pow()`
Returns the base raised to the exponent power.

```javascript
console.log(Math.pow(2, 3)); // Output: 8 (2^3)
console.log(Math.pow(5, 2)); // Output: 25 (5^2)
```

### 8. `Math.sqrt()`
Returns the square root of a number.

```javascript
console.log(Math.sqrt(16)); // Output: 4
console.log(Math.sqrt(25)); // Output: 5
```

### 9. `Math.random()`
Returns a pseudo-random number between 0 (inclusive) and 1 (exclusive).

```javascript
console.log(Math.random()); // Output: A random number between 0 and 1
```

### 10. `Math.sin()`
Returns the sine of a number (angle in radians).

```javascript
console.log(Math.sin(Math.PI / 2)); // Output: 1
```

### 11. `Math.cos()`
Returns the cosine of a number (angle in radians).

```javascript
console.log(Math.cos(0)); // Output: 1
```

### 12. `Math.tan()`
Returns the tangent of a number (angle in radians).

```javascript
console.log(Math.tan(Math.PI / 4)); // Output: 1
```

### 13. `Math.log()`
Returns the natural logarithm (base e) of a number.

```javascript
console.log(Math.log(Math.E)); // Output: 1
```

### 14. `Math.exp()`
Returns e raised to the power of a given number.

```javascript
console.log(Math.exp(1)); // Output: 2.718281828459045 (approximately e)
```

### 15. `Math.floor()`
Rounds a number down to the nearest integer.

```javascript
console.log(Math.floor(5.7)); // Output: 5
```

### 16. `Math.PI`
A constant representing the value of π (pi).

```javascript
console.log(Math.PI); // Output: 3.141592653589793
```

### 17. `Math.E`
A constant representing Euler's number (approximately 2.718).

```javascript
console.log(Math.E); // Output: 2.718281828459045
```

### 18. `Math.abs()`
Returns the absolute value of a number.

```javascript
console.log(Math.abs(-10)); // Output: 10
```

### 19. `Math.trunc()`
Returns the integer part of a number by removing any fractional digits.

```javascript
console.log(Math.trunc(4.9)); // Output: 4
console.log(Math.trunc(-4.9)); // Output: -4
```

### 20. `Math.sign()`
Returns the sign of a number, indicating whether the number is positive, negative, or zero.

```javascript
console.log(Math.sign(-5)); // Output: -1
console.log(Math.sign(0));  // Output: 0
console.log(Math.sign(5));  // Output: 1
```

### `Date` methods along with examples for each 

### Creating a Date Object

1. **`new Date()`**
   Creates a new date object with the current date and time.

   ```javascript
   const now = new Date();
   console.log(now); // Output: Current date and time
   ```

2. **`new Date(dateString)`**
   Creates a new date object from a date string.

   ```javascript
   const dateFromString = new Date("2023-04-17");
   console.log(dateFromString); // Output: Mon Apr 17 2023 00:00:00 GMT...
   ```

3. **`new Date(year, month, day, hours, minutes, seconds, milliseconds)`**
   Creates a new date object with specified parameters.

   ```javascript
   const specificDate = new Date(2023, 3, 17); // Month is 0-indexed (0 = January)
   console.log(specificDate); // Output: Mon Apr 17 2023 00:00:00 GMT...
   ```

### Getting Date Components

1. **`getFullYear()`**
   Returns the year of the specified date.

   ```javascript
   const date = new Date("2023-04-17");
   console.log(date.getFullYear()); // Output: 2023
   ```

2. **`getMonth()`**
   Returns the month (0-11) of the specified date.

   ```javascript
   const date = new Date("2023-04-17");
   console.log(date.getMonth()); // Output: 3 (April)
   ```

3. **`getDate()`**
   Returns the day of the month (1-31) for the specified date.

   ```javascript
   const date = new Date("2023-04-17");
   console.log(date.getDate()); // Output: 17
   ```

4. **`getDay()`**
   Returns the day of the week (0-6) for the specified date.

   ```javascript
   const date = new Date("2023-04-17");
   console.log(date.getDay()); // Output: 1 (Monday)
   ```

5. **`getHours()`**
   Returns the hour (0-23) of the specified date.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   console.log(date.getHours()); // Output: 15
   ```

6. **`getMinutes()`**
   Returns the minutes (0-59) of the specified date.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   console.log(date.getMinutes()); // Output: 30
   ```

7. **`getSeconds()`**
   Returns the seconds (0-59) of the specified date.

   ```javascript
   const date = new Date("2023-04-17T15:30:45");
   console.log(date.getSeconds()); // Output: 45
   ```

8. **`getMilliseconds()`**
   Returns the milliseconds (0-999) of the specified date.

   ```javascript
   const date = new Date("2023-04-17T15:30:45.123");
   console.log(date.getMilliseconds()); // Output: 123
   ```

### Setting Date Components

1. **`setFullYear(year, month, day)`**
   Sets the year of a date object.

   ```javascript
   const date = new Date("2023-04-17");
   date.setFullYear(2025);
   console.log(date); // Output: Mon Apr 17 2025 ...
   ```

2. **`setMonth(month, day)`**
   Sets the month of a date object.

   ```javascript
   const date = new Date("2023-04-17");
   date.setMonth(11); // December
   console.log(date); // Output: Fri Dec 17 2023 ...
   ```

3. **`setDate(day)`**
   Sets the day of the month for a date object.

   ```javascript
   const date = new Date("2023-04-17");
   date.setDate(25);
   console.log(date); // Output: Mon Apr 25 2023 ...
   ```

4. **`setHours(hours, minutes, seconds, milliseconds)`**
   Sets the hours for a date object.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   date.setHours(10);
   console.log(date); // Output: Mon Apr 17 2023 10:30:00 ...
   ```

5. **`setMinutes(minutes, seconds, milliseconds)`**
   Sets the minutes for a date object.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   date.setMinutes(45);
   console.log(date); // Output: Mon Apr 17 2023 15:45:00 ...
   ```

6. **`setSeconds(seconds, milliseconds)`**
   Sets the seconds for a date object.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   date.setSeconds(15);
   console.log(date); // Output: Mon Apr 17 2023 15:30:15 ...
   ```

7. **`setMilliseconds(milliseconds)`**
   Sets the milliseconds for a date object.

   ```javascript
   const date = new Date("2023-04-17T15:30:00.000");
   date.setMilliseconds(500);
   console.log(date); // Output: Mon Apr 17 2023 15:30:00.500 ...
   ```

### Date Formatting

1. **`toString()`**
   Returns a string representation of the date.

   ```javascript
   const date = new Date("2023-04-17");
   console.log(date.toString()); // Output: Mon Apr 17 2023 ...
   ```

2. **`toUTCString()`**
   Converts a date to a string, using the UTC timezone.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   console.log(date.toUTCString()); // Output: Mon, 17 Apr 2023 15:30:00 GMT
   ```

3. **`toISOString()`**
   Returns the date as a string in ISO format.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   console.log(date.toISOString()); // Output: 2023-04-17T15:30:00.000Z
   ```

4. **`toLocaleString()`**
   Returns a string with a language-sensitive representation of the date.

   ```javascript
   const date = new Date("2023-04-17T15:30:00");
   console.log(date.toLocaleString()); // Output: Depending on locale settings
   ```

### Other Useful Methods

1. **`Date.now()`**
   Returns the current timestamp in milliseconds since January 1, 1970.

   ```javascript
   console.log(Date.now()); // Output: Current timestamp in milliseconds
   ```

2. **`Date.parse()`**
   Parses a date string and returns the number of milliseconds since January 1, 1970.

   ```javascript
   const timestamp = Date.parse("2023-04-17");
   console.log(timestamp); // Output: Timestamp in milliseconds
   ```

3. **`Date.UTC()`**
   Accepts the same parameters as the `Date` constructor but returns the number of milliseconds since January 1, 1970, UTC.

   ```javascript
   const utcTimestamp = Date.UTC(2023, 3, 17); // Month is 0-indexed
   console.log(utcTimestamp); // Output: Timestamp in milliseconds
   ```
 DOM (Document Object Model) manipulation in JavaScript allows developers to interact with and modify the structure, style, and content of web pages dynamically. Here’s a deep dive into the key concepts and techniques involved in DOM manipulation:

### 1. Understanding the DOM
The DOM represents the document as a tree structure where each node corresponds to a part of the document (elements, attributes, text, etc.). JavaScript can access and modify this structure, allowing for dynamic content updates.

### 2. Selecting Elements
You can select DOM elements using various methods:
- **`document.getElementById(id)`**: Selects a single element by its ID.
- **`document.getElementsByClassName(className)`**: Returns a live HTMLCollection of elements with the specified class.
- **`document.getElementsByTagName(tagName)`**: Returns a live HTMLCollection of elements with the specified tag name.
- **`document.querySelector(selector)`**: Selects the first element that matches the CSS selector.
- **`document.querySelectorAll(selector)`**: Returns a NodeList of all elements that match the CSS selector.

### 3. Modifying Elements
Once you've selected an element, you can modify its properties:
- **Changing Content**: Use `innerHTML`, `textContent`, or `innerText` to change the content inside an element.
  ```javascript
  const element = document.getElementById('myElement');
  element.innerHTML = '<strong>New Content</strong>'; // Changes HTML content
  element.textContent = 'New Text Content'; // Changes text only
  ```
  
- **Changing Attributes**: Use `setAttribute()` and `getAttribute()` to modify attributes.
  ```javascript
  element.setAttribute('class', 'newClass'); // Set a new class
  const className = element.getAttribute('class'); // Get the class
  ```

- **Changing Styles**: Modify the `style` property directly.
  ```javascript
  element.style.color = 'red'; // Change text color
  element.style.display = 'none'; // Hide the element
  ```

### 4. Creating and Removing Elements
You can create new elements and remove existing ones:
- **Creating Elements**:
  ```javascript
  const newDiv = document.createElement('div');
  newDiv.textContent = 'Hello World!';
  document.body.appendChild(newDiv); // Adds the new element to the body
  ```

- **Removing Elements**:
  ```javascript
  const elementToRemove = document.getElementById('removeMe');
  elementToRemove.parentNode.removeChild(elementToRemove); // Removes the element
  ```

### 5. Event Handling
You can add event listeners to elements to respond to user actions:
- **Adding Event Listeners**:
  ```javascript
  element.addEventListener('click', function() {
      alert('Element clicked!');
  });
  ```

- **Removing Event Listeners**:
  ```javascript
  function handleClick() {
      alert('Element clicked!');
  }
  element.addEventListener('click', handleClick);
  element.removeEventListener('click', handleClick); // Removes the listener
  ```

### 6. Traversing the DOM
You can navigate through the DOM tree:
- **Parent and Child Nodes**:
  ```javascript
  const parent = element.parentNode; // Access parent node
  const children = element.childNodes; // Access child nodes
  ```

- **Sibling Nodes**:
  ```javascript
  const nextSibling = element.nextSibling; // Access next sibling
  const previousSibling = element.previousSibling; // Access previous sibling
  ```

### 7. Performance Considerations
- **Batch DOM Manipulations**: Minimize reflows and repaints by batching DOM changes.
- **Use Document Fragments**: Create a `DocumentFragment` to hold elements before appending them to the DOM.
  ```javascript
  const fragment = document.createDocumentFragment();
  // Append elements to fragment
  document.body.appendChild(fragment); // Append the fragment
  ```

### 8. Best Practices
- **Keep the DOM Manipulation Minimal**: Only update what is necessary to improve performance.
- **Use CSS Classes for Style Changes**: Instead of directly manipulating styles, toggle classes to apply styles.
- **Avoid Inline JavaScript**: Keep JavaScript separate from HTML for better maintainability.

### simple example of a CRUD (Create, Read, Update, Delete) application using JavaScript and DOM manipulation. This example will allow you to manage a list of items (like tasks) in a web page.

### HTML Structure
First, let's set up a basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD with DOM</title>
    <style>
        body { font-family: Arial, sans-serif; }
        #items { margin-top: 20px; }
        .item { display: flex; justify-content: space-between; padding: 5px; }
    </style>
</head>
<body>
    <h1>CRUD Application</h1>
    <input type="text" id="itemInput" placeholder="Enter item" />
    <button id="addButton">Add Item</button>
    
    <div id="items"></div>

    <script src="script.js"></script>
</body>
</html>
```

### JavaScript Logic (script.js)
Now, let's add the JavaScript to handle the CRUD operations:

```javascript
// Select DOM elements
const itemInput = document.getElementById('itemInput');
const addButton = document.getElementById('addButton');
const itemsContainer = document.getElementById('items');

// Array to hold items
let items = [];

// Function to render items
function renderItems() {
    itemsContainer.innerHTML = ''; // Clear the container
    items.forEach((item, index) => {
        const itemDiv = document.createElement('div');
        itemDiv.className = 'item';
        itemDiv.innerHTML = `
            <span>${item}</span>
            <button onclick="editItem(${index})">Edit</button>
            <button onclick="deleteItem(${index})">Delete</button>
        `;
        itemsContainer.appendChild(itemDiv);
    });
}

// Function to add item
addButton.addEventListener('click', () => {
    const itemText = itemInput.value.trim();
    if (itemText) {
        items.push(itemText); // Add item to the array
        itemInput.value = ''; // Clear input
        renderItems(); // Re-render the list
    }
});

// Function to edit item
function editItem(index) {
    const newItemText = prompt('Edit item:', items[index]);
    if (newItemText) {
        items[index] = newItemText; // Update the item
        renderItems(); // Re-render the list
    }
}

// Function to delete item
function deleteItem(index) {
    if (confirm('Are you sure you want to delete this item?')) {
        items.splice(index, 1); // Remove item from the array
        renderItems(); // Re-render the list
    }
}
```

### Explanation
1. **HTML Structure**: We have an input field for entering items, a button to add items, and a container to display the list of items.

2. **JavaScript Logic**:
    - **Selecting Elements**: We select the input field, button, and container using `document.getElementById`.
    - **Array for Items**: We maintain an array (`items`) to store the list of items.
    - **Render Function**: The `renderItems` function is responsible for displaying the items in the container. It clears the container and creates a new `div` for each item with buttons for editing and deleting.
    - **Add Item**: When the "Add Item" button is clicked, the item is added to the array, and the list is re-rendered.
    - **Edit Item**: The `editItem` function prompts the user to enter a new value for the selected item, updates the array, and re-renders the list.
    - **Delete Item**: The `deleteItem` function removes the item from the array after confirming with the user and then re-renders the list.

### Usage
1. Enter an item in the input field and click "Add Item" to add it to the list.
2. Click "Edit" next to an item to modify it.
3. Click "Delete" to remove an item from the list.


T### BOM (Browser Object Model) is a set of objects provided by the browser that allows JavaScript to interact with the browser itself, rather than just the document (DOM). It provides methods and properties to manipulate the browser window, handle events, and interact with the browser’s features. Here’s a complete overview of BOM, including examples.

### 1. Window Object
The `window` object is the global object in the browser. It represents the browser window and provides methods to control it.

#### Example: Window Properties and Methods
```javascript
// Display the width and height of the window
console.log(`Width: ${window.innerWidth}, Height: ${window.innerHeight}`);

// Open a new window
const newWindow = window.open('https://www.example.com', '_blank');

// Close the newly opened window after 3 seconds
setTimeout(() => {
    newWindow.close();
}, 3000);
```

### 2. Document Object
The `document` object is part of the DOM but is also part of the BOM. It represents the web page loaded in the browser.

#### Example: Accessing Document Properties
```javascript
// Change the title of the document
document.title = "New Title";

// Get the URL of the current document
console.log(document.URL);
```

### 3. Navigator Object
The `navigator` object contains information about the browser and the operating system.

#### Example: Checking Browser Information
```javascript
// Check if the browser is online
if (navigator.onLine) {
    console.log("You are online.");
} else {
    console.log("You are offline.");
}

// Display browser name and version
console.log(`Browser Name: ${navigator.appName}`);
console.log(`Browser Version: ${navigator.appVersion}`);
```

### 4. Screen Object
The `screen` object contains information about the user's screen, such as its size and color depth.

#### Example: Screen Properties
```javascript
// Display screen width and height
console.log(`Screen Width: ${screen.width}, Screen Height: ${screen.height}`);

// Display color depth
console.log(`Color Depth: ${screen.colorDepth} bits`);
```

### 5. History Object
The `history` object allows you to interact with the browser's session history (the pages visited in the current tab or window).

#### Example: Navigating History
```javascript
// Go back to the previous page
function goBack() {
    window.history.back();
}

// Go forward to the next page
function goForward() {
    window.history.forward();
}

// Go back two pages
function goBackTwoPages() {
    window.history.go(-2);
}
```

### 6. Location Object
The `location` object contains information about the current URL and provides methods to change it.

#### Example: Changing the URL
```javascript
// Get the current URL
console.log(location.href);

// Redirect to another URL
function redirect() {
    location.href = 'https://www.example.com';
}
```

### 7. Timing Events
The BOM provides methods to set timers for executing code after a specified delay.

#### Example: Using setTimeout and setInterval
```javascript
// Execute a function after 2 seconds
setTimeout(() => {
    console.log("This message is displayed after 2 seconds.");
}, 2000);

// Execute a function every second
const intervalId = setInterval(() => {
    console.log("This message is displayed every second.");
}, 1000);

// Stop the interval after 5 seconds
setTimeout(() => {
    clearInterval(intervalId);
    console.log("Interval cleared.");
}, 5000);
```

### 8. Event Handling
The BOM allows you to handle events such as resizing the window or closing it.

#### Example: Window Resize Event
```javascript
// Log the new size of the window when it is resized
window.addEventListener('resize', () => {
    console.log(`New Width: ${window.innerWidth}, New Height: ${window.innerHeight}`);
});
```

### Events in JavaScript are actions or occurrences that happen in the browser, which can be detected and responded to using event handlers. Understanding different types of events, event bubbling, and event delegation is crucial for effective event management in web applications. Here’s a comprehensive overview with examples.

### 1. Types of Events
JavaScript events can be broadly categorized into several types:

- **Mouse Events**: Triggered by mouse actions (e.g., `click`, `dblclick`, `mouseover`, `mouseout`, `mousemove`).
- **Keyboard Events**: Triggered by keyboard actions (e.g., `keydown`, `keyup`, `keypress`).
- **Form Events**: Triggered by form actions (e.g., `submit`, `change`, `focus`, `blur`).
- **Window Events**: Triggered by actions related to the window (e.g., `load`, `resize`, `scroll`).

### Example: Handling Different Types of Events
Here’s an example that demonstrates handling mouse and keyboard events:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Types Example</title>
    <style>
        #box {
            width: 100px;
            height: 100px;
            background-color: lightblue;
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1>Event Types Example</h1>
    <div id="box">Click Me!</div>
    <input type="text" id="inputField" placeholder="Type here..." />

    <script>
        const box = document.getElementById('box');
        const inputField = document.getElementById('inputField');

        // Mouse event
        box.addEventListener('click', () => {
            alert('Box clicked!');
        });

        // Keyboard event
        inputField.addEventListener('keyup', (event) => {
            console.log(`Key pressed: ${event.key}`);
        });
    </script>
</body>
</html>
```

### 2. Event Bubbling
Event bubbling is a mechanism where an event starts at the target element and bubbles up to the parent elements. This means that when an event occurs on an element, it first runs the handlers on that element, then on its parent, and so on up to the root of the DOM.

#### Example: Event Bubbling
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Bubbling Example</title>
    <style>
        #parent {
            padding: 20px;
            background-color: lightgray;
        }
        #child {
            padding: 20px;
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <div id="parent">Parent
        <div id="child">Child</div>
    </div>

    <script>
        const parent = document.getElementById('parent');
        const child = document.getElementById('child');

        // Event listener on parent
        parent.addEventListener('click', () => {
            alert('Parent clicked!');
        });

        // Event listener on child
        child.addEventListener('click', (event) => {
            alert('Child clicked!');
            // Stop the event from bubbling up
            event.stopPropagation();
        });
    </script>
</body>
</html>
```
In this example, clicking on the child div will trigger the child’s click event first, showing "Child clicked!" and then stop the event from bubbling up, preventing the parent’s click event from firing.

### 3. Event Delegation
Event delegation is a technique that allows you to attach a single event listener to a parent element, which can manage events for multiple child elements. This is particularly useful for dynamically added elements.

#### Example: Event Delegation
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Delegation Example</title>
</head>
<body>
    <h1>Event Delegation Example</h1>
    <ul id="itemList">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    <button id="addItem">Add Item</button>

    <script>
        const itemList = document.getElementById('itemList');
        const addItemButton = document.getElementById('addItem');
        let itemCount = 4;

        // Event delegation for list items
        itemList.addEventListener('click', (event) => {
            if (event.target.tagName === 'LI') {
                alert(`You clicked on ${event.target.textContent}`);
            }
        });

        // Add new item to the list
        addItemButton.addEventListener('click', () => {
            const newItem = document.createElement('li');
            newItem.textContent = `Item ${itemCount++}`;
            itemList.appendChild(newItem);
        });
    </script>
</body>
</html>
```

 ### ES6 features  along with examples for each 

### 1. `let` Keyword
The `let` keyword allows you to declare block-scoped variables, which means they are only accessible within the block they are defined in.

```javascript
if (true) {
    let x = 10;
}
console.log(x); // ReferenceError: x is not defined
```

### 2. `const` Keyword
The `const` keyword is used to declare variables that cannot be reassigned. However, objects declared with `const` can still be mutated.

```javascript
const y = 20;
// y = 30; // TypeError: Assignment to constant variable.
const obj = { name: 'Alice' };
obj.name = 'Bob'; // This is allowed
```

### 3. Arrow Functions
Arrow functions provide a shorter syntax for writing function expressions and do not have their own `this` context.

```javascript
const add = (a, b) => a + b;
console.log(add(2, 3)); // 5
```

### 4. Destructuring Assignment
Destructuring allows unpacking values from arrays or properties from objects into distinct variables.

```javascript
const arr = [1, 2, 3];
const [a, b] = arr; // a = 1, b = 2

const obj = { x: 1, y: 2 };
const { x, y } = obj; // x = 1, y = 2
```

### 5. Spread Operator (`...`)
The spread operator allows an iterable (like an array) to be expanded in places where zero or more arguments are expected.

```javascript
const arr1 = [1, 2];
const arr2 = [3, 4];
const combined = [...arr1, ...arr2]; // [1, 2, 3, 4]
```

### 6. `for...of` Loop
The `for...of` loop iterates over iterable objects (like arrays, strings, etc.), providing a simpler way to loop through elements.

```javascript
const arr = [10, 20, 30];
for (const value of arr) {
    console.log(value); // 10, 20, 30
}
```

### 7. Maps
Maps are collections of key-value pairs where keys can be of any data type, maintaining the insertion order.

```javascript
const map = new Map();
map.set('a', 1);
map.set('b', 2);
console.log(map.get('a')); // 1
```

### 8. Sets
Sets are collections of unique values, meaning that duplicates are not allowed.

```javascript
const set = new Set([1, 2, 2, 3]);
console.log(set.size); // 3
```

### 9. Classes
ES6 introduced a class syntax, providing a clearer way to create objects and handle inheritance.

```javascript
class Animal {
    constructor(name) {
        this.name = name;
    }
    speak() {
        console.log(`${this.name} makes a noise.`);
    }
}
const dog = new Animal('Dog');
dog.speak(); // Dog makes a noise.
```

### 10. Promises
Promises are used to handle asynchronous operations, providing a cleaner alternative to callbacks.

```javascript
const fetchData = () => {
    return new Promise((resolve, reject) => {
        setTimeout(() => resolve('Data received'), 1000);
    });
};

fetchData().then(data => console.log(data)); // Data received
```

### 11. Default Parameters
Functions can have default values for parameters, which are used if no value or `undefined` is passed.

```javascript
function multiply(a, b = 1) {
    return a * b;
}
console.log(multiply(5)); // 5
```

### 12. String Methods (`includes`, `startsWith`, `endsWith`)
These methods provide more ways to work with strings.

```javascript
const str = 'Hello, world!';
console.log(str.includes('world')); // true
console.log(str.startsWith('Hello')); // true
console.log(str.endsWith('!')); // true
```

### 13. Array Methods (`find`, `findIndex`, `from`)
These methods enhance how we work with arrays.

```javascript
const numbers = [5, 12, 8, 130, 44];
const found = numbers.find(num => num > 10); // 12
const foundIndex = numbers.findIndex(num => num > 10); // 1
const arrFrom = Array.from('hello'); // ['h', 'e', 'l', 'l', 'o']
```

### 14. Template Literals
Template literals allow for multi-line strings and string interpolation.

```javascript
const name = 'John';
const greeting = `Hello, ${name}!`;
console.log(greeting); // Hello, John!
```

### 15. Modules (`import`, `export`)
Modules allow for better organization of code by exporting and importing functionalities from different files.

```javascript
// module.js
export const pi = 3.14;

// main.js
import { pi } from './module.js';
console.log(pi); // 3.14
```

### 16. Rest Parameters (`...args`)
Rest parameters allow functions to accept an indefinite number of arguments as an array.

```javascript
function sum(...args) {
    return args.reduce((acc, num) => acc + num, 0);
}
console.log(sum(1, 2, 3)); // 6
```

### 17. Generators and Iterators (`function*`, `yield`)
Generators are functions that can be paused and resumed, allowing for more complex iteration.

```javascript
function* generator() {
    yield 1;
    yield 2;
    yield 3;
}
const gen = generator();
console.log(gen.next().value); // 1
console.log(gen.next().value); // 2
```

### 18. Binary and Octal Literals (`0b`, `0o`)
These allow for easier representation of binary and octal numbers.

```javascript
const binary = 0b1010; // 10 in decimal
const octal = 0o12; // 10 in decimal
console.log(binary, octal); // 10 10
```

### 19. Enhanced Object Literals
This feature allows for more concise object definitions, including shorthand property names and method definitions.

```javascript
const x = 1, y = 2;
const obj = { x, y, greet() { console.log('Hello!'); } };
obj.greet(); // Hello!
```

### 20. WeakMap
A `WeakMap` is a collection of key-value pairs where the keys are objects and can be garbage collected if there are no other references.

```javascript
const weakMap = new WeakMap();
const obj = {};
weakMap.set(obj, 'value');
console.log(weakMap.get(obj)); // value
```

### 21. WeakSet
A `WeakSet` is similar to a `Set`, but its keys are weakly referenced, meaning they can be garbage collected.

```javascript
const weakSet = new WeakSet();
const obj = {};
weakSet.add(obj);
console.log(weakSet.has(obj)); // true
```

### 22. Proxy
A `Proxy` allows you to define custom behavior for fundamental operations (e.g., property lookup, assignment, enumeration, function invocation).

```javascript
const target = {};
const handler = {
    get: (obj, prop) => {
        return prop in obj ? obj[prop] : 'Property does not exist';
    }
};
const proxy = new Proxy(target, handler);
console.log(proxy.someProperty); // Property does not exist
```

### 23. Reflect
The `Reflect` API provides methods for interceptable JavaScript operations, similar to the Proxy API.

```javascript
const obj = { a: 1 };
console.log(Reflect.get(obj, 'a')); // 1
```

### 24. Symbol
Symbols are unique and immutable primitive values that can be used as object property keys, allowing for hidden properties.

```javascript
const sym = Symbol('description');
const obj = { [sym]: 'value' };
console.log(obj[sym]); // value
```

### 25. Block-Scoped Functions
Functions defined within a block using `let` or `const` are scoped to that block, unlike traditional function declarations.

```javascript
if (true) {
    function blockScopedFunc() {
        console.log('I am block scoped!');
    }
    blockScopedFunc(); // I am block scoped!
}
// blockScopedFunc(); // ReferenceError: blockScopedFunc is not defined
```


Closures in JavaScript are a powerful feature that allows a function to access variables from its outer (enclosing) scope even after that scope has finished executing. This is particularly useful for data encapsulation and creating private variables.

### How Closures Work

When a function is defined inside another function, the inner function has access to the outer function's variables. This relationship creates a closure. The inner function "closes over" the variables of the outer function, allowing it to remember those variables even when the outer function has returned.

### Example of a Closure

Here's a simple example to illustrate how closures work:

```javascript
function makeCounter() {
    let count = 0; // This variable is private to makeCounter

    return function() { // This inner function forms a closure
        count++; // Increment the count
        return count; // Return the current count
    };
}

const counter = makeCounter(); // Create a new counter instance

console.log(counter()); // 1
console.log(counter()); // 2
console.log(counter()); // 3
```

### Explanation

1. **Outer Function**: `makeCounter` is the outer function that contains a variable `count` initialized to `0`.

2. **Inner Function**: The inner function (returned by `makeCounter`) has access to `count` due to closure. Each time you call `counter()`, it increments `count` and returns the new value.

3. **Encapsulation**: The variable `count` is not accessible from outside the `makeCounter` function. You cannot directly manipulate `count`, which effectively makes it a private variable.

### Practical Use Cases for Closures

- **Data Privacy**: You can create private variables that cannot be accessed from outside the function.
- **Partial Application**: Closures can be used to create functions with preset arguments.
- **Event Handlers**: They can help maintain state in callbacks, especially in asynchronous programming.

Sure! Here are more examples of closures in JavaScript, showcasing different scenarios and use cases.

### Example 1: Creating Private Variables

In this example, we use closures to create private variables that cannot be accessed directly from outside the function.

```javascript
function createPerson(name) {
    let age = 0; // Private variable

    return {
        getName: function() {
            return name; // Accessing the outer variable
        },
        getAge: function() {
            return age; // Accessing the private variable
        },
        setAge: function(newAge) {
            age = newAge; // Modifying the private variable
        }
    };
}

const person = createPerson('Alice');
console.log(person.getName()); // Alice
console.log(person.getAge()); // 0
person.setAge(30);
console.log(person.getAge()); // 30
```

### Example 2: Counter with Different Instances

This example demonstrates how closures can create multiple independent instances of a counter.

```javascript
function createCounter() {
    let count = 0;

    return {
        increment: function() {
            count++;
            return count;
        },
        decrement: function() {
            count--;
            return count;
        },
        reset: function() {
            count = 0;
            return count;
        }
    };
}

const counter1 = createCounter();
const counter2 = createCounter();

console.log(counter1.increment()); // 1
console.log(counter1.increment()); // 2
console.log(counter1.reset()); // 0

console.log(counter2.increment()); // 1
console.log(counter2.decrement()); // 0
```

### Example 3: Function Factory

In this example, we create a function factory that generates functions with preset values.

```javascript
function multiplyBy(factor) {
    return function(x) {
        return x * factor; // Closure captures the factor
    };
}

const double = multiplyBy(2);
const triple = multiplyBy(3);

console.log(double(5)); // 10
console.log(triple(5)); // 15
```

### Example 4: Maintaining State in Asynchronous Code

Closures are particularly useful in managing state in asynchronous operations, such as in event handlers or timers.

```javascript
function createTimer() {
    let count = 0;

    setInterval(function() {
        count++;
        console.log(`Timer: ${count} seconds`);
    }, 1000);
}

createTimer(); // Starts a timer that logs every second
```

### Example 5: Event Handlers

Closures are often used in event handlers to maintain state.

```javascript
function setupButton() {
    let count = 0;

    const button = document.createElement('button');
    button.innerText = 'Click me';
    document.body.appendChild(button);

    button.addEventListener('click', function() {
        count++;
        console.log(`Button clicked ${count} times`);
    });
}

setupButton(); // Each click will increment and log the count
```

### Example 6: Currying

Currying is a functional programming technique that transforms a function with multiple arguments into a sequence of functions, each taking a single argument. Closures are used to remember the arguments.

```javascript
function curriedAdd(a) {
    return function(b) {
        return a + b; // Closure captures the first argument
    };
}

const addFive = curriedAdd(5);
console.log(addFive(3)); // 8
console.log(addFive(10)); // 15
```

### Higher-order functions are a fundamental concept in JavaScript (and many other programming languages) that allow functions to operate on other functions. This means that a higher-order function can take one or more functions as arguments or return a function as its result. This capability is essential for functional programming and enables powerful abstractions and code reusability.


### Key Characteristics of Higher-Order Functions
1. **Accept Functions as Arguments**: A higher-order function can take one or more functions as parameters.
2. **Return Functions**: A higher-order function can return another function.
3. **Create Abstractions**: They allow for more abstract and reusable code.

### Examples of Higher-Order Functions

#### 1. Functions as Arguments
Here's an example of a higher-order function that accepts another function as an argument:

```javascript
// A higher-order function that takes a function as an argument
function greetUser(greetingFunction, name) {
    return greetingFunction(name);
}

// A simple greeting function
function sayHello(name) {
    return `Hello, ${name}!`;
}

// Using the higher-order function
console.log(greetUser(sayHello, 'Alice')); // Output: Hello, Alice!
```

In this example, `greetUser` is a higher-order function that takes another function (`greetingFunction`) and a name as arguments. It then calls the `greetingFunction` with the provided name.

#### 2. Returning Functions
Higher-order functions can also return other functions. Here’s an example:

```javascript
// A higher-order function that returns another function
function multiplier(factor) {
    return function(x) {
        return x * factor;
    };
}

// Create a function that doubles the input
const double = multiplier(2);

// Create a function that triples the input
const triple = multiplier(3);

console.log(double(5)); // Output: 10
console.log(triple(5)); // Output: 15
```

In this example, the `multiplier` function returns a new function that multiplies its argument by the `factor` provided. The `double` and `triple` functions are created by calling `multiplier` with different factors.

#### 3. Array Methods as Higher-Order Functions
Many built-in array methods in JavaScript, such as `map`, `filter`, and `reduce`, are higher-order functions because they take functions as arguments.

**Example with `map`:**

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using map to create a new array by doubling each number
const doubled = numbers.map(function(num) {
    return num * 2;
});

console.log(doubled); // Output: [2, 4, 6, 8, 10]
```

**Example with `filter`:**

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using filter to create a new array with only even numbers
const evens = numbers.filter(function(num) {
    return num % 2 === 0;
});

console.log(evens); // Output: [2, 4]
```

**Example with `reduce`:**

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using reduce to calculate the sum of the array
const sum = numbers.reduce(function(accumulator, current) {
    return accumulator + current;
}, 0);

console.log(sum); // Output: 15
```

Recursion is a programming technique in which a function calls itself in order to solve a problem. This approach is particularly useful for problems that can be broken down into smaller, similar subproblems. In JavaScript, recursion can be employed to simplify complex tasks, such as traversing data structures (like trees), calculating factorials, and generating sequences.

### Key Concepts of Recursion

1. **Base Case**: Every recursive function must have a base case that stops the recursion. This prevents infinite loops and allows the function to return a result.
2. **Recursive Case**: This is the part of the function where the function calls itself with modified arguments, moving towards the base case.

### How Recursion Works
When a recursive function is called, a new execution context is created for each call. The function continues to call itself until it reaches the base case, at which point it begins to return values back through the chain of calls.

### Example 1: Factorial Calculation
A classic example of recursion is calculating the factorial of a number.

#### Factorial Function
```javascript
function factorial(n) {
    // Base case
    if (n === 0 || n === 1) {
        return 1;
    }
    // Recursive case
    return n * factorial(n - 1);
}

console.log(factorial(5)); // Output: 120
```

In this example:
- **Base Case**: When `n` is 0 or 1, the function returns 1.
- **Recursive Case**: The function calls itself with `n - 1` until it reaches the base case.

### Example 2: Fibonacci Sequence
The Fibonacci sequence is another example where recursion can be applied.

#### Fibonacci Function
```javascript
function fibonacci(n) {
    // Base cases
    if (n === 0) return 0;
    if (n === 1) return 1;
    // Recursive case
    return fibonacci(n - 1) + fibonacci(n - 2);
}

console.log(fibonacci(6)); // Output: 8 (0, 1, 1, 2, 3, 5, 8)
```

In this example:
- **Base Cases**: When `n` is 0 or 1, the function returns the corresponding Fibonacci number.
- **Recursive Case**: The function calls itself twice with `n - 1` and `n - 2`.

### Example 3: Traversing a Tree Structure
Recursion is particularly useful for traversing tree-like structures, such as a binary tree.

#### Binary Tree Traversal
```javascript
class Node {
    constructor(value) {
        this.value = value;
        this.left = null;
        this.right = null;
    }
}

class BinaryTree {
    constructor() {
        this.root = null;
    }

    // Recursive method to insert a value
    insert(value) {
        const newNode = new Node(value);
        if (!this.root) {
            this.root = newNode;
            return;
        }
        this.insertNode(this.root, newNode);
    }

    insertNode(node, newNode) {
        if (newNode.value < node.value) {
            if (!node.left) {
                node.left = newNode;
            } else {
                this.insertNode(node.left, newNode);
            }
        } else {
            if (!node.right) {
                node.right = newNode;
            } else {
                this.insertNode(node.right, newNode);
            }
        }
    }

    // Recursive method for in-order traversal
    inOrderTraversal(node) {
        if (node) {
            this.inOrderTraversal(node.left);
            console.log(node.value);
            this.inOrderTraversal(node.right);
        }
    }
}

// Example usage
const tree = new BinaryTree();
tree.insert(10);
tree.insert(5);
tree.insert(15);
tree.insert(3);
tree.insert(7);

console.log("In-order Traversal:");
tree.inOrderTraversal(tree.root); // Output: 3, 5, 7, 10, 15
```

### Advantages of Recursion
- **Simplicity**: Recursive solutions can be more straightforward and easier to understand than their iterative counterparts.
- **Code Reduction**: Recursive functions can reduce the amount of code needed to solve a problem by eliminating the need for explicit loops and state management.

### Disadvantages of Recursion
- **Performance**: Recursive functions can be less efficient than iterative solutions due to the overhead of multiple function calls and stack space usage.
- **Stack Overflow**: Deep recursion can lead to a stack overflow error if the recursion depth exceeds the call stack size.

### Tail Recursion
Tail recursion is a specific type of recursion where the recursive call is the last operation in the function. Some languages optimize tail recursion to avoid increasing the call stack size, but JavaScript does not guarantee this optimization.

#### Example of Tail Recursion
```javascript
function tailRecursiveFactorial(n, accumulator = 1) {
    if (n === 0 || n === 1) {
        return accumulator;
    }
    return tailRecursiveFactorial(n - 1, n * accumulator);
}

console.log(tailRecursiveFactorial(5)); // Output: 120
```


Recursion is a powerful technique in JavaScript that can simplify complex problems and enhance code readability. While it has its advantages and disadvantages, understanding how to effectively use recursion is essential for any JavaScript developer. By mastering recursion, you can tackle problems that require a divide-and-conquer approach, such as traversing data structures and solving mathematical problems.

JavaScript modules are a way to organize and encapsulate code in a reusable manner. They allow developers to break down large codebases into smaller, manageable pieces, making it easier to maintain and reuse code. The `import` and `export` statements are essential parts of this module system, enabling the sharing of functionality between different files.

### Key Concepts of JavaScript Modules

1. **Module**: A module is a piece of code that is executed once it is loaded. It can export variables, functions, or classes that can be used in other modules.
2. **Exporting**: This is the process of making variables, functions, or classes available to other modules.
3. **Importing**: This is the process of bringing in exported functionalities from other modules to use in the current module.

### Types of Exports

There are two main types of exports in JavaScript modules: named exports and default exports.

#### 1. Named Exports
Named exports allow you to export multiple values from a module. You can export variables, functions, or classes by their names.

**Example of Named Exports**

**math.js** (Module File)
```javascript
// Named exports
export const pi = 3.14;

export function add(x, y) {
    return x + y;
}

export function multiply(x, y) {
    return x * y;
}
```

**app.js** (Importing Module)
```javascript
import { pi, add, multiply } from './math.js';

console.log(`Value of pi: ${pi}`); // Output: Value of pi: 3.14
console.log(`2 + 3 = ${add(2, 3)}`); // Output: 2 + 3 = 5
console.log(`2 * 3 = ${multiply(2, 3)}`); // Output: 2 * 3 = 6
```

#### 2. Default Exports
A module can have one default export, which is often used for the main functionality of the module. This allows you to import it without using curly braces.

**Example of Default Export**

**calculator.js** (Module File)
```javascript
// Default export
export default function subtract(x, y) {
    return x - y;
}
```

**app.js** (Importing Module)
```javascript
import subtract from './calculator.js';

console.log(`5 - 3 = ${subtract(5, 3)}`); // Output: 5 - 3 = 2
```

### Importing All Exports
You can also import all named exports from a module as a single object using the `*` syntax.

**Example**
```javascript
import * as math from './math.js';

console.log(`Value of pi: ${math.pi}`); // Output: Value of pi: 3.14
console.log(`2 + 3 = ${math.add(2, 3)}`); // Output: 2 + 3 = 5
console.log(`2 * 3 = ${math.multiply(2, 3)}`); // Output: 2 * 3 = 6
```

### Re-exporting
You can also re-export values from one module in another module.

**Example**
**index.js** (Re-exporting Module)
```javascript
export { add, multiply } from './math.js';
export { default as subtract } from './calculator.js';
```

**app.js** (Using Re-exported Module)
```javascript
import { add, multiply, subtract } from './index.js';

console.log(`3 + 4 = ${add(3, 4)}`); // Output: 3 + 4 = 7
console.log(`6 * 7 = ${multiply(6, 7)}`); // Output: 6 * 7 = 42
console.log(`10 - 5 = ${subtract(10, 5)}`); // Output: 10 - 5 = 5
```

### Module File Extensions
When importing modules, it’s important to include the file extension (e.g., `.js`) in the import statement, especially when using ES modules in environments like browsers.

### Module in Browsers
To use modules in the browser, you need to specify the `type="module"` attribute in your `<script>` tag.

**Example**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Modules</title>
</head>
<body>
    <script type="module" src="app.js"></script>
</body>
</html>
```

JavaScript modules using `import` and `export` are a powerful feature that allows for better organization, encapsulation, and reuse of code. By understanding how to create and use modules effectively, you can build more maintainable and scalable applications. Whether you are working in a browser environment or using Node.js, mastering modules is essential for modern JavaScript development.

Asynchronous JavaScript allows developers to write non-blocking code, enabling the execution of tasks without waiting for previous tasks to complete. This is essential for creating responsive web applications that can handle multiple operations, such as network requests, file handling, and user interactions. The main tools for managing asynchronous operations in JavaScript are `setTimeout`, Promises, and the `async/await` syntax. Let’s explore each of these in detail.

### 1. `setTimeout`
`setTimeout` is a built-in JavaScript function that allows you to execute a piece of code after a specified delay (in milliseconds). It is commonly used to schedule tasks.

#### Syntax
```javascript
setTimeout(callback, delay, ...args);
```
- **callback**: The function to execute after the delay.
- **delay**: The time in milliseconds to wait before executing the callback.
- **...args**: Optional arguments to pass to the callback function.

#### Example
```javascript
console.log("Start");

setTimeout(() => {
    console.log("Executed after 2 seconds");
}, 2000);

console.log("End");
```
**Output:**
```
Start
End
Executed after 2 seconds
```
In this example, the `setTimeout` function schedules the callback to be executed after 2 seconds, while the rest of the code continues executing immediately.

### 2. Promises
Promises are a way to handle asynchronous operations in JavaScript. A Promise represents a value that may be available now, or in the future, or never. It can be in one of three states:
- **Pending**: The initial state, neither fulfilled nor rejected.
- **Fulfilled**: The operation completed successfully.
- **Rejected**: The operation failed.

#### Creating a Promise
```javascript
const myPromise = new Promise((resolve, reject) => {
    const success = true; // Simulate success or failure
    if (success) {
        resolve("Promise resolved successfully!");
    } else {
        reject("Promise rejected!");
    }
});
```

#### Using Promises
You can handle the result of a Promise using `.then()` for fulfilled promises and `.catch()` for rejected ones.

#### Example
```javascript
myPromise
    .then(result => {
        console.log(result); // Output: Promise resolved successfully!
    })
    .catch(error => {
        console.error(error);
    });
```

#### Chaining Promises
Promises can be chained to handle multiple asynchronous operations in sequence.

```javascript
const fetchData = () => {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve("Data fetched!");
        }, 1000);
    });
};

fetchData()
    .then(data => {
        console.log(data); // Output: Data fetched!
        return "Processing data...";
    })
    .then(processedData => {
        console.log(processedData); // Output: Processing data...
    });
```

### 3. `async/await`
`async/await` is syntactic sugar built on top of Promises, making asynchronous code easier to read and write. The `async` keyword is used to declare a function as asynchronous, and the `await` keyword is used to pause the execution of the function until the Promise is resolved.

#### Example
```javascript
const fetchData = () => {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve("Data fetched!");
        }, 1000);
    });
};

const processData = async () => {
    try {
        const data = await fetchData();
        console.log(data); // Output: Data fetched!
        const processedData = "Processing data...";
        console.log(processedData); // Output: Processing data...
    } catch (error) {
        console.error("Error:", error);
    }
};

processData();
```

In this example:
- The `processData` function is declared as `async`, allowing the use of `await` within it.
- The execution pauses at `await fetchData()`, waiting for the Promise to resolve before proceeding.

### Error Handling with `async/await`
Error handling in `async/await` can be done using `try/catch` blocks, making it similar to synchronous error handling.

#### Example
```javascript
const fetchDataWithError = () => {
    return new Promise((_, reject) => {
        setTimeout(() => {
            reject("Error fetching data!");
        }, 1000);
    });
};

const processDataWithError = async () => {
    try {
        const data = await fetchDataWithError();
        console.log(data);
    } catch (error) {
        console.error("Caught an error:", error); // Output: Caught an error: Error fetching data!
    }
};

processDataWithError();
```

### Summary
- **`setTimeout`**: Used to schedule code execution after a specified delay.
- **Promises**: Provide a way to handle asynchronous operations, allowing for cleaner and more manageable code compared to traditional callback methods.
- **`async/await`**: Simplifies the syntax for working with Promises, making asynchronous code look more like synchronous code, which enhances readability and maintainability.



Promises, `async`, and `await` are all integral parts of handling asynchronous operations in JavaScript, but they serve different purposes and have different syntaxes. Here’s a breakdown of the differences between them:

### 1. Promises
- **Definition**: A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation and its resulting value. It can be in one of three states: **pending**, **fulfilled**, or **rejected**.
  
- **Usage**: Promises are used to handle asynchronous operations and can be chained using `.then()` for success and `.catch()` for errors.

- **Syntax**:
  ```javascript
  const myPromise = new Promise((resolve, reject) => {
      // Asynchronous operation
      if (/* operation successful */) {
          resolve('Success!');
      } else {
          reject('Error!');
      }
  });

  myPromise
      .then(result => console.log(result)) // Handle success
      .catch(error => console.error(error)); // Handle error
  ```

### 2. `async` Functions
- **Definition**: An `async` function is a function that is declared with the `async` keyword. It allows the use of `await` within it and automatically returns a Promise, even if the function does not explicitly return one.

- **Usage**: `async` functions simplify the syntax for working with Promises, making it easier to write and read asynchronous code.

- **Syntax**:
  ```javascript
  async function myAsyncFunction() {
      return 'Hello, world!'; // Implicitly returns a Promise
  }

  myAsyncFunction().then(result => console.log(result)); // Output: Hello, world!
  ```

### 3. `await`
- **Definition**: The `await` keyword can only be used inside an `async` function. It pauses the execution of the `async` function until the Promise is resolved or rejected.

- **Usage**: It allows you to write asynchronous code that looks synchronous, making it easier to read and maintain.

- **Syntax**:
  ```javascript
  async function myAsyncFunction() {
      const result = await myPromise; // Wait for the Promise to resolve
      console.log(result);
  }
  ```

### Key Differences

| Feature                | Promises                               | `async` Functions                     | `await`                      |
|------------------------|----------------------------------------|---------------------------------------|------------------------------|
| **Definition**         | Represents a value that may be available now or in the future. | A function that returns a Promise.   | Pauses execution until a Promise is resolved. |
| **Syntax**             | Uses `.then()` and `.catch()`.        | Declared with the `async` keyword.   | Used inside `async` functions. |
| **Return Value**       | Can return a value or another Promise. | Always returns a Promise.             | Returns the resolved value of the Promise. |
| **Error Handling**     | Uses `.catch()` for handling errors.  | Uses `try/catch` blocks for error handling. | Can use `try/catch` for error handling. |
| **Readability**        | Can lead to "callback hell" with multiple chained `.then()` calls. | More readable and resembles synchronous code. | Makes asynchronous code look synchronous. |

### Example Comparison
Here's an example that illustrates the differences:

#### Using Promises
```javascript
function fetchData() {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve("Data fetched!");
        }, 1000);
    });
}

fetchData()
    .then(data => {
        console.log(data); // Output: Data fetched!
    })
    .catch(error => {
        console.error(error);
    });
```

#### Using `async/await`
```javascript
async function fetchData() {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve("Data fetched!");
        }, 1000);
    });
}

async function processData() {
    try {
        const data = await fetchData();
        console.log(data); // Output: Data fetched!
    } catch (error) {
        console.error(error);
    }
}

processData();
```

In summary, Promises are the foundation for handling asynchronous operations, while `async` and `await` are syntactic sugar built on top of Promises that make it easier to work with asynchronous code. Using `async/await` can lead to cleaner, more readable code, especially when dealing with multiple asynchronous operations.

Promises in JavaScript are a powerful tool for handling asynchronous operations. They represent a value that may be available now, or in the future, or never. A Promise can be in one of three states:

1. **Pending**: The initial state, neither fulfilled nor rejected.
2. **Fulfilled**: The operation completed successfully.
3. **Rejected**: The operation failed.

### Creating a Promise

You can create a Promise using the `Promise` constructor, which takes a function (the executor) that has two parameters: `resolve` and `reject`.

```javascript
const myPromise = new Promise((resolve, reject) => {
    // Asynchronous operation
    const success = true; // Simulate success or failure
    if (success) {
        resolve('Operation was successful!');
    } else {
        reject('Operation failed.');
    }
});
```

### Using Promises

Promises are typically used with the following methods:

1. **then()**
2. **catch()**
3. **finally()**

### 1. `then()`

The `then()` method is used to handle the fulfilled state of a Promise. It takes two arguments: a callback function for the fulfilled case and an optional callback for the rejected case.

```javascript
myPromise
    .then(result => {
        console.log(result); // Output: Operation was successful!
    })
    .catch(error => {
        console.error(error);
    });
```

### 2. `catch()`

The `catch()` method is used to handle the rejected state of a Promise. It is a shorthand for `.then(null, rejection)`.

```javascript
const myPromiseWithError = new Promise((resolve, reject) => {
    reject('Something went wrong!');
});

myPromiseWithError
    .then(result => {
        console.log(result);
    })
    .catch(error => {
        console.error(error); // Output: Something went wrong!
    });
```

### 3. `finally()`

The `finally()` method is called regardless of the Promise's outcome (fulfilled or rejected). It is useful for cleanup actions.

```javascript
myPromise
    .then(result => {
        console.log(result); // Output: Operation was successful!
    })
    .catch(error => {
        console.error(error);
    })
    .finally(() => {
        console.log('Promise settled.'); // This runs regardless of success or failure
    });
```

### Chaining Promises

You can chain multiple `then()` calls to handle a series of asynchronous operations.

```javascript
const fetchData = () => {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve('Data received');
        }, 1000);
    });
};

fetchData()
    .then(data => {
        console.log(data); // Output: Data received
        return 'Processing data...';
    })
    .then(result => {
        console.log(result); // Output: Processing data...
    })
    .catch(error => {
        console.error(error);
    });
```

### Promise.all()

`Promise.all()` is a method that takes an array of Promises and returns a single Promise that resolves when all of the Promises in the array have resolved, or rejects if any of the Promises reject.

```javascript
const promise1 = Promise.resolve(3);
const promise2 = new Promise((resolve, reject) => {
    setTimeout(resolve, 1000, 'foo');
});
const promise3 = 42;

Promise.all([promise1, promise2, promise3])
    .then(values => {
        console.log(values); // Output: [3, 'foo', 42]
    })
    .catch(error => {
        console.error(error);
    });
```

### Promise.race()

`Promise.race()` returns a Promise that resolves or rejects as soon as one of the Promises in the iterable resolves or rejects, with the value or reason from that Promise.

```javascript
const promise1 = new Promise((resolve) => {
    setTimeout(resolve, 500, 'one');
});
const promise2 = new Promise((resolve) => {
    setTimeout(resolve, 100, 'two');
});

Promise.race([promise1, promise2])
    .then(value => {
        console.log(value); // Output: 'two' (the first to resolve)
    })
    .catch(error => {
        console.error(error);
    });
```

### Promise.allSettled()

`Promise.allSettled()` takes an array of Promises and returns a Promise that resolves after all of the given Promises have either resolved or rejected, with an array of objects that each describe the outcome of each Promise.

```javascript
const promise1 = Promise.resolve(3);
const promise2 = new Promise((resolve, reject) => {
    setTimeout(reject, 100, 'foo');
});
const promise3 = 42;

Promise.allSettled([promise1, promise2, promise3])
    .then(results => {
        results.forEach((result) => {
            console.log(result.status); // Output: 'fulfilled', 'rejected', 'fulfilled'
            console.log(result.value || result.reason);
        });
    });
```

`Promise.any()` is a method in JavaScript that takes an iterable of Promise objects and, unlike `Promise.all()`, it resolves as soon as any of the promises in the iterable fulfill. If no promises fulfill (i.e., all promises are rejected), it will reject with an `AggregateError`, which is a built-in error type that groups together multiple errors.

### Syntax

```javascript
Promise.any(iterable);
```

- **iterable**: An iterable such as an array that contains Promise objects.

### Returns

- A single Promise that resolves with the value of the first fulfilled promise.
- If no promises in the iterable fulfill, it rejects with an `AggregateError`, containing all the rejection reasons.

### Example of `Promise.any()`

Here’s a simple example to illustrate how `Promise.any()` works:

```javascript
const promise1 = Promise.reject('Error 1');
const promise2 = Promise.reject('Error 2');
const promise3 = new Promise((resolve) => {
    setTimeout(() => resolve('Success 3'), 1000);
});
const promise4 = new Promise((resolve) => {
    setTimeout(() => resolve('Success 4'), 500);
});

Promise.any([promise1, promise2, promise3, promise4])
    .then((result) => {
        console.log(result); // Output: 'Success 4'
    })
    .catch((error) => {
        console.error(error);
    });
```

### Explanation of the Example

1. **Promises**: In this example, `promise1` and `promise2` are rejected immediately, while `promise3` and `promise4` resolve after 1 second and 0.5 seconds, respectively.
  
2. **Using `Promise.any()`**: When we call `Promise.any()` with the array of promises, it will wait for the first promise that fulfills.

3. **Output**: Since `promise4` resolves first, the output will be `'Success 4'`.

### Handling Rejections

If all promises in the iterable are rejected, `Promise.any()` will reject with an `AggregateError`:

```javascript
const promise1 = Promise.reject('Error 1');
const promise2 = Promise.reject('Error 2');

Promise.any([promise1, promise2])
    .then((result) => {
        console.log(result);
    })
    .catch((error) => {
        console.error(error); // Output: AggregateError: All promises were rejected
        console.error(error.errors); // Output: ['Error 1', 'Error 2']
    });
```



`Promise.any()` is a useful method for scenarios where you want to proceed as soon as any of the promises fulfill, without waiting for all of them to complete. It's particularly helpful when dealing with multiple asynchronous operations where you only care about the first successful result, such as making multiple API calls and using the result from the first one that succeeds.



Promises are a powerful way to handle asynchronous operations in JavaScript. They provide a cleaner alternative to traditional callback-based approaches and allow for better error handling and chaining of operations. The main methods associated with Promises (`then()`, `catch()`, `finally()`, `Promise.all()`, `Promise.race()`, and `Promise.allSettled()`) offer a robust toolkit for managing asynchronous workflows effectively.

### AJAX (Asynchronous JavaScript and XML)

**AJAX** is a technique used to send and retrieve data asynchronously from a server without interfering with the display and behavior of the existing page. It allows web applications to be more dynamic and interactive by updating parts of a web page without reloading the whole page. 

#### Key Components of AJAX:

1. **XMLHttpRequest Object**: The core of AJAX is the `XMLHttpRequest` object, which is used to send requests to a server.
2. **Asynchronous Communication**: AJAX allows for asynchronous communication, meaning that the web page can continue to function while data is being fetched.
3. **Data Formats**: While the name includes XML, AJAX can handle various data formats, including JSON, XML, HTML, and plain text.

#### Example of AJAX using `XMLHttpRequest`

```javascript
const xhr = new XMLHttpRequest(); // Create a new XMLHttpRequest object

xhr.open('GET', 'https://api.example.com/data', true); // Initialize a GET request

xhr.onload = function() {
    if (xhr.status >= 200 && xhr.status < 300) {
        console.log('Response:', JSON.parse(xhr.responseText)); // Handle the response
    } else {
        console.error('Request failed with status:', xhr.status);
    }
};

xhr.onerror = function() {
    console.error('Request failed');
};

xhr.send(); // Send the request
```

### Fetch API

The **Fetch API** is a modern interface for making HTTP requests. It is built into most modern browsers and provides a more powerful and flexible feature set than `XMLHttpRequest`. The Fetch API returns a `Promise`, making it easier to work with asynchronous code.

#### Key Features of Fetch API:

1. **Promise-based**: Fetch API uses Promises, which means you can use `.then()` and `.catch()` for handling responses and errors.
2. **More Powerful**: It provides better support for handling various types of requests and responses, including streaming.
3. **Simpler Syntax**: The syntax is cleaner and more intuitive compared to `XMLHttpRequest`.

#### Example of Fetch API

```javascript
fetch('https://api.example.com/data') // Make a GET request
    .then(response => {
        if (!response.ok) {
            throw new Error('Network response was not ok ' + response.statusText);
        }
        return response.json(); // Parse JSON response
    })
    .then(data => {
        console.log('Data:', data); // Handle the data
    })
    .catch(error => {
        console.error('There has been a problem with your fetch operation:', error);
    });
```

### Working with REST APIs

**REST (Representational State Transfer)** is an architectural style for designing networked applications. RESTful APIs allow interaction with web services using standard HTTP methods such as GET, POST, PUT, and DELETE.

#### Key Principles of REST:

1. **Stateless**: Each request from the client contains all the information the server needs to fulfill that request. The server does not store any state about the client session.
2. **Resource-Based**: REST APIs are centered around resources, which are identified by URIs (Uniform Resource Identifiers). Resources can be represented in various formats, such as JSON or XML.
3. **HTTP Methods**: REST uses standard HTTP methods to perform operations:
   - **GET**: Retrieve data from the server.
   - **POST**: Send data to the server to create a new resource.
   - **PUT**: Update an existing resource.
   - **DELETE**: Remove a resource from the server.

#### Example of Working with a REST API

Let's consider a simple example of interacting with a REST API for a resource called "users".

1. **GET Request to Retrieve Users**

```javascript
fetch('https://api.example.com/users')
    .then(response => response.json())
    .then(users => {
        console.log('Users:', users);
    })
    .catch(error => {
        console.error('Error fetching users:', error);
    });
```

2. **POST Request to Create a New User**

```javascript
const newUser = {
    name: 'John Doe',
    email: 'john@example.com'
};

fetch('https://api.example.com/users', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify(newUser) // Convert object to JSON string
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    return response.json();
})
.then(data => {
    console.log('User created:', data);
})
.catch(error => {
    console.error('Error creating user:', error);
});
```

3. **PUT Request to Update an Existing User**

```javascript
const updatedUser = {
    name: 'John Smith',
    email: 'john.smith@example.com'
};

fetch('https://api.example.com/users/1', { // Assuming user ID is 1
    method: 'PUT',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify(updatedUser)
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    return response.json();
})
.then(data => {
    console.log('User updated:', data);
})
.catch(error => {
    console.error('Error updating user:', error);
});
```

4. **DELETE Request to Remove a User**

```javascript
fetch('https://api.example.com/users/1', { // Assuming user ID is 1
    method: 'DELETE'
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    console.log('User deleted successfully');
})
.catch(error => {
    console.error('Error deleting user:', error);
});
```

### Summary

- **AJAX** allows for asynchronous data fetching without refreshing the page, using `XMLHttpRequest`.
- The **Fetch API** is a modern, Promise-based way to make HTTP requests, providing a cleaner and more powerful interface.
- **REST APIs** follow a set of principles for designing networked applications, using standard HTTP methods to interact with resources.

The JSONPlaceholder API is a free online REST API that you can use for testing and prototyping. It provides a set of fake data for various resources, such as posts, comments, users, and more. Below are examples of how to use the JSONPlaceholder API with the Fetch API for common operations like GET, POST, PUT, and DELETE.

### Base URL

The base URL for JSONPlaceholder is:

```
https://jsonplaceholder.typicode.com
```

### 1. GET Request

To retrieve a list of posts:

```javascript
fetch('https://jsonplaceholder.typicode.com/posts')
    .then(response => response.json())
    .then(posts => {
        console.log('Posts:', posts);
    })
    .catch(error => {
        console.error('Error fetching posts:', error);
    });
```

### 2. POST Request

To create a new post:

```javascript
const newPost = {
    title: 'foo',
    body: 'bar',
    userId: 1
};

fetch('https://jsonplaceholder.typicode.com/posts', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify(newPost)
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    return response.json();
})
.then(data => {
    console.log('Post created:', data);
})
.catch(error => {
    console.error('Error creating post:', error);
});
```

### 3. PUT Request

To update an existing post (e.g., post with ID 1):

```javascript
const updatedPost = {
    id: 1,
    title: 'updated title',
    body: 'updated body',
    userId: 1
};

fetch('https://jsonplaceholder.typicode.com/posts/1', {
    method: 'PUT',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify(updatedPost)
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    return response.json();
})
.then(data => {
    console.log('Post updated:', data);
})
.catch(error => {
    console.error('Error updating post:', error);
});
```

### 4. DELETE Request

To delete a post (e.g., post with ID 1):

```javascript
fetch('https://jsonplaceholder.typicode.com/posts/1', {
    method: 'DELETE'
})
.then(response => {
    if (!response.ok) {
        throw new Error('Network response was not ok');
    }
    console.log('Post deleted successfully');
})
.catch(error => {
    console.error('Error deleting post:', error);
});
```

### Summary

- **GET**: Retrieve data from the API (e.g., posts, users).
- **POST**: Create new data in the API.
- **PUT**: Update existing data in the API.
- **DELETE**: Remove data from the API.

Error handling in JavaScript is a crucial aspect of writing robust and maintainable code. It allows developers to gracefully handle unexpected situations, such as runtime errors, and provide meaningful feedback to users or log errors for debugging purposes. The primary mechanisms for error handling in JavaScript are the `try/catch` block and the creation of custom error types.

### 1. Using `try/catch`

The `try/catch` statement allows you to test a block of code for errors while providing a way to handle those errors without crashing the program. 

#### Syntax
```javascript
try {
    // Code that may throw an error
} catch (error) {
    // Code to handle the error
} finally {
    // Code that will run regardless of the outcome (optional)
}
```

#### Example
```javascript
try {
    const result = riskyFunction(); // This function may throw an error
    console.log(result);
} catch (error) {
    console.error("An error occurred:", error.message);
} finally {
    console.log("This will always run.");
}
```

In this example:
- The code inside the `try` block is executed. If an error occurs, the control is transferred to the `catch` block.
- The `catch` block receives the error object, which can be used to log or handle the error.
- The `finally` block, if present, will execute after the `try` and `catch` blocks, regardless of whether an error occurred or not.

### 2. Custom Errors

JavaScript allows you to create custom error types by extending the built-in `Error` class. This is useful for creating more descriptive error types specific to your application.

#### Creating a Custom Error Class
```javascript
class CustomError extends Error {
    constructor(message) {
        super(message); // Call the parent constructor
        this.name = this.constructor.name; // Set the error name
        this.date = new Date(); // Add a timestamp
    }
}
```

#### Using a Custom Error
```javascript
function validateInput(input) {
    if (!input) {
        throw new CustomError("Input cannot be empty");
    }
    // Further validation logic...
}

try {
    validateInput(""); // This will throw a CustomError
} catch (error) {
    console.error(`${error.name} (${error.date}): ${error.message}`);
}
```

In this example:
- A custom error class `CustomError` is created by extending the built-in `Error` class.
- The `validateInput` function throws a `CustomError` if the input is empty.
- The `catch` block then captures the custom error and logs its name, date, and message.

### 3. Error Propagation

Errors can also be propagated up the call stack, allowing you to handle them at a higher level in your application.

#### Example
```javascript
function fetchData() {
    return new Promise((resolve, reject) => {
        // Simulating an asynchronous operation that may fail
        setTimeout(() => {
            const errorOccurred = true; // Simulate an error
            if (errorOccurred) {
                reject(new CustomError("Failed to fetch data"));
            } else {
                resolve("Data fetched successfully");
            }
        }, 1000);
    });
}

async function processData() {
    try {
        const data = await fetchData();
        console.log(data);
    } catch (error) {
        console.error(`${error.name}: ${error.message}`);
    }
}

processData();
```

In this example:
- The `fetchData` function simulates an asynchronous operation that may throw an error.
- The `processData` function uses `async/await` to handle the Promise returned by `fetchData`, catching any errors that occur.

### Summary

- **`try/catch`**: Use the `try/catch` statement to handle errors gracefully without crashing your application. The `catch` block allows you to respond to errors appropriately.
- **Custom Errors**: Create custom error classes to provide more context and specificity to errors in your application. This can help with debugging and improving error handling.
- **Error Propagation**: Errors can be propagated up the call stack, allowing for centralized error handling in your application.

By effectively using `try/catch` and custom error classes, you can build more resilient JavaScript applications that handle errors gracefully and provide meaningful feedback to users.
   

In web development, data storage on the client side is essential for maintaining state and storing user preferences. The three primary mechanisms for client-side storage in web browsers are **LocalStorage**, **SessionStorage**, and **Cookies**. Each has its own characteristics, use cases, and methods for data manipulation. Let's explore each of these in detail.

### 1. LocalStorage

**LocalStorage** is a web storage mechanism that allows you to store key-value pairs in a web browser with no expiration time. Data stored in LocalStorage persists even after the browser is closed and reopened.

#### Characteristics:
- **Storage Limit**: Typically around 5-10 MB per origin (varies by browser).
- **Persistence**: Data persists until explicitly deleted.
- **Scope**: Accessible only within the same origin (protocol, host, and port).

#### Methods:
- **`setItem(key, value)`**: Adds a key-value pair to LocalStorage.
- **`getItem(key)`**: Retrieves the value associated with the specified key.
- **`removeItem(key)`**: Removes the key-value pair from LocalStorage.
- **`clear()`**: Clears all key-value pairs in LocalStorage.
- **`key(index)`**: Returns the name of the key at the specified index.

#### Example:
```javascript
// Set an item
localStorage.setItem('username', 'JohnDoe');

// Get an item
const username = localStorage.getItem('username');
console.log(username); // Output: JohnDoe

// Remove an item
localStorage.removeItem('username');

// Clear all items
localStorage.clear();
```

### 2. SessionStorage

**SessionStorage** is similar to LocalStorage but with a key difference: the data is stored for the duration of the page session. Data stored in SessionStorage is cleared when the page session ends (i.e., when the tab or browser is closed).

#### Characteristics:
- **Storage Limit**: Typically around 5-10 MB per origin (varies by browser).
- **Persistence**: Data is lost when the tab or browser is closed.
- **Scope**: Accessible only within the same origin and the same tab.

#### Methods:
- **`setItem(key, value)`**: Adds a key-value pair to SessionStorage.
- **`getItem(key)`**: Retrieves the value associated with the specified key.
- **`removeItem(key)`**: Removes the key-value pair from SessionStorage.
- **`clear()`**: Clears all key-value pairs in SessionStorage.
- **`key(index)`**: Returns the name of the key at the specified index.

#### Example:
```javascript
// Set an item
sessionStorage.setItem('sessionData', 'Some temporary data');

// Get an item
const sessionData = sessionStorage.getItem('sessionData');
console.log(sessionData); // Output: Some temporary data

// Remove an item
sessionStorage.removeItem('sessionData');

// Clear all items
sessionStorage.clear();
```

### 3. Cookies

**Cookies** are small pieces of data that are stored in the user's browser and are sent to the server with every HTTP request. Cookies can have expiration dates and are suitable for storing small amounts of data.

#### Characteristics:
- **Storage Limit**: Typically around 4 KB per cookie, with a limit of 20-50 cookies per domain.
- **Persistence**: Can be set to expire at a specific time or persist until deleted.
- **Scope**: Accessible across different tabs and windows of the same origin.

#### Methods:
Cookies are not accessed through JavaScript methods but are manipulated using the `document.cookie` property.

- **Set a cookie**: 
  ```javascript
  document.cookie = "username=JohnDoe; expires=Fri, 31 Dec 2025 23:59:59 GMT; path=/";
  ```
- **Get a cookie**: 
  ```javascript
  const getCookie = (name) => {
      const value = `; ${document.cookie}`;
      const parts = value.split(`; ${name}=`);
      if (parts.length === 2) return parts.pop().split(';').shift();
  };

  const username = getCookie('username');
  console.log(username); // Output: JohnDoe
  ```
- **Delete a cookie**:
  ```javascript
  document.cookie = "username=; expires=Thu, 01 Jan 1970 00:00:00 GMT; path=/";
  ```

### Comparison of LocalStorage, SessionStorage, and Cookies

| Feature                | LocalStorage                          | SessionStorage                      | Cookies                              |
|------------------------|--------------------------------------|------------------------------------|--------------------------------------|
| **Lifetime**           | Persistent until deleted             | Until the tab/browser is closed    | Can be persistent or session-based   |
| **Storage Limit**      | ~5-10 MB per origin                  | ~5-10 MB per origin                | ~4 KB per cookie                     |
| **Scope**              | Same origin                          | Same origin and same tab           | Accessible across tabs/windows        |
| **Data Type**         | Only strings (must be serialized)    | Only strings (must be serialized)   | Strings (can store key-value pairs)  |
| **Expiration**         | No expiration                        | No expiration                      | Can set expiration                   |
| **Sending to Server**  | Not sent automatically               | Not sent automatically             | Sent with every HTTP request         |

### Conclusion

- **LocalStorage** is ideal for storing large amounts of data that need to persist across sessions.
- **SessionStorage** is useful for temporary data that should only last for the duration of a page session.
- **Cookies** are best for small pieces of data that need to be sent to the server with each request, such as session identifiers.

By understanding these storage mechanisms, you can choose the best option for your application's needs.

In web development, there are several browser storage options available for storing data on the client side. Each storage option has its own characteristics, use cases, and limitations. Here’s a comprehensive overview of the main browser storage options:

### 1. LocalStorage

**LocalStorage** is a key-value store that allows you to store data persistently in the browser. Data stored in LocalStorage does not expire and remains available even after the browser is closed and reopened.

- **Characteristics**:
  - Stores data as strings.
  - Typically allows around 5-10 MB of storage per origin (varies by browser).
  - Accessible only within the same origin (protocol, host, and port).
  - Data persists until explicitly deleted.

- **Methods**:
  - `setItem(key, value)`: Adds a key-value pair.
  - `getItem(key)`: Retrieves the value associated with the key.
  - `removeItem(key)`: Removes the key-value pair.
  - `clear()`: Clears all key-value pairs.
  - `key(index)`: Returns the name of the key at the specified index.

- **Example**:
  ```javascript
  localStorage.setItem('username', 'JohnDoe');
  const username = localStorage.getItem('username');
  console.log(username); // Output: JohnDoe
  localStorage.removeItem('username');
  localStorage.clear();
  ```

### 2. SessionStorage

**SessionStorage** is similar to LocalStorage but is designed for storing data for the duration of a page session. Data stored in SessionStorage is cleared when the tab or browser is closed.

- **Characteristics**:
  - Stores data as strings.
  - Typically allows around 5-10 MB of storage per origin (varies by browser).
  - Accessible only within the same origin and the same tab.
  - Data is lost when the tab or browser is closed.

- **Methods**:
  - `setItem(key, value)`: Adds a key-value pair.
  - `getItem(key)`: Retrieves the value associated with the key.
  - `removeItem(key)`: Removes the key-value pair.
  - `clear()`: Clears all key-value pairs.
  - `key(index)`: Returns the name of the key at the specified index.

- **Example**:
  ```javascript
  sessionStorage.setItem('sessionData', 'Some temporary data');
  const sessionData = sessionStorage.getItem('sessionData');
  console.log(sessionData); // Output: Some temporary data
  sessionStorage.removeItem('sessionData');
  sessionStorage.clear();
  ```

### 3. Cookies

**Cookies** are small pieces of data stored in the user's browser that can be sent to the server with every HTTP request. Cookies can have expiration dates and are suitable for storing small amounts of data.

- **Characteristics**:
  - Typically limited to around 4 KB per cookie.
  - Can be set to expire at a specific time or persist until deleted.
  - Accessible across different tabs and windows of the same origin.
  - Sent with every HTTP request, which can impact performance.

- **Methods**:
  Cookies are manipulated using the `document.cookie` property.

- **Setting a Cookie**:
  ```javascript
  document.cookie = "username=JohnDoe; expires=Fri, 31 Dec 2025 23:59:59 GMT; path=/";
  ```

- **Getting a Cookie**:
  ```javascript
  const getCookie = (name) => {
      const value = `; ${document.cookie}`;
      const parts = value.split(`; ${name}=`);
      if (parts.length === 2) return parts.pop().split(';').shift();
  };

  const username = getCookie('username');
  console.log(username); // Output: JohnDoe
  ```

- **Deleting a Cookie**:
  ```javascript
  document.cookie = "username=; expires=Thu, 01 Jan 1970 00:00:00 GMT; path=/";
  ```

### 4. IndexedDB

**IndexedDB** is a low-level API for storing significant amounts of structured data, including files and blobs. It allows for more complex queries and is suitable for applications that require offline capabilities.

- **Characteristics**:
  - Stores data as key-value pairs, supporting complex data types.
  - Asynchronous API for reading and writing data.
  - Supports transactions for data integrity.
  - Typically allows large amounts of storage (hundreds of MB or more).

- **Methods**:
  - `open(name, version)`: Opens a database connection.
  - `transaction(storeNames, mode)`: Creates a transaction.
  - `objectStore(name)`: Accesses an object store.
  - `add(value, key)`: Adds a new record.
  - `get(key)`: Retrieves a record by key.
  - `delete(key)`: Deletes a record by key.

- **Example**:
  ```javascript
  const request = indexedDB.open("myDatabase", 1);

  request.onupgradeneeded = (event) => {
      const db = event.target.result;
      const objectStore = db.createObjectStore("users", { keyPath: "id" });
  };

  request.onsuccess = (event) => {
      const db = event.target.result;
      const transaction = db.transaction("users", "readwrite");
      const objectStore = transaction.objectStore("users");

      objectStore.add({ id: 1, name: "John Doe" });
      objectStore.get(1).onsuccess = (event) => {
          console.log(event.target.result); // Output: { id: 1, name: "John Doe" }
      };
  };
  ```

### 5. Web SQL (Deprecated)

**Web SQL** was an API for storing data in a structured database, but it has been deprecated and is no longer recommended for use. It was primarily supported in WebKit-based browsers (like Safari) but is not part of any web standard.

### Summary of Browser Storage Options

| Feature                | LocalStorage                          | SessionStorage                      | Cookies                              | IndexedDB                           |
|------------------------|--------------------------------------|------------------------------------|--------------------------------------|-------------------------------------|
| **Lifetime**           | Persistent until deleted             | Until the tab/browser is closed    | Can be persistent or session-based   | Persistent until deleted            |
| **Storage Limit**      | ~5-10 MB per origin                  | ~5-10 MB per origin                | ~4 KB per cookie                     | Hundreds of MB or more             |
| **Scope**              | Same origin                          | Same origin and same tab           | Accessible across tabs/windows        | Same origin                         |
| **Data Type**          | Only strings (must be serialized)    | Only strings (must be serialized)   | Strings (can store key-value pairs)  | Supports complex data types         |
| **Expiration**         | No expiration                        | No expiration                      | Can set expiration                   |
| **Sending to Server**  | Not sent automatically               | Not sent automatically             | Sent with every HTTP request         |
| **API Complexity**     | Simple API                           | Simple API                         | Simple API                           | Asynchronous, more complex API      |

### Conclusion

Choosing the right storage option depends on your application’s requirements, such as the amount of data to be stored, the need for persistence, and whether the data needs to be sent to the server. Understanding these storage options will help you make informed decisions when developing web applications.


JavaScript ES5 (ECMAScript 5), released in December 2009, introduced several important features and improvements to the language. Here are some of the key features of ES5:

### 1. Strict Mode

Strict mode is a way to opt into a restricted variant of JavaScript, which helps catch common coding errors and "unsafe" actions such as defining global variables unintentionally.

```javascript
"use strict";

function myFunction() {
    x = 3.14; // ReferenceError: x is not defined
}
myFunction();
```

### 2. Array Methods

ES5 introduced several new methods for arrays, enhancing their functionality:

- **forEach()**: Executes a provided function once for each array element.

    ```javascript
    const arr = [1, 2, 3];
    arr.forEach((element) => {
        console.log(element); // Output: 1, 2, 3
    });
    ```

- **map()**: Creates a new array populated with the results of calling a provided function on every element in the calling array.

    ```javascript
    const doubled = arr.map((element) => element * 2);
    console.log(doubled); // Output: [2, 4, 6]
    ```

- **filter()**: Creates a new array with all elements that pass the test implemented by the provided function.

    ```javascript
    const filtered = arr.filter((element) => element > 1);
    console.log(filtered); // Output: [2, 3]
    ```

- **reduce()**: Executes a reducer function on each element of the array, resulting in a single output value.

    ```javascript
    const sum = arr.reduce((accumulator, current) => accumulator + current, 0);
    console.log(sum); // Output: 6
    ```

### 3. Object Methods

ES5 introduced several methods to enhance object manipulation:

- **Object.create()**: Creates a new object with the specified prototype object and properties.

    ```javascript
    const person = {
        greet: function() {
            console.log('Hello!');
        }
    };
    const john = Object.create(person);
    john.greet(); // Output: Hello!
    ```

- **Object.keys()**: Returns an array of a given object's own property names.

    ```javascript
    const obj = { a: 1, b: 2, c: 3 };
    const keys = Object.keys(obj);
    console.log(keys); // Output: ['a', 'b', 'c']
    ```

### 4. JSON Support

ES5 introduced a built-in JSON object for parsing and stringifying JSON data.

- **JSON.parse()**: Parses a JSON string and constructs the JavaScript value or object described by the string.

    ```javascript
    const jsonString = '{"name": "Alice", "age": 25}';
    const user = JSON.parse(jsonString);
    console.log(user.name); // Output: Alice
    ```

- **JSON.stringify()**: Converts a JavaScript object or value to a JSON string.

    ```javascript
    const userObj = { name: 'Bob', age: 30 };
    const jsonString = JSON.stringify(userObj);
    console.log(jsonString); // Output: '{"name":"Bob","age":30}'
    ```

### 5. Function Bind

The `bind()` method creates a new function that, when called, has its `this` keyword set to the provided value.

```javascript
const obj = {
    value: 42
};

function getValue() {
    return this.value;
}

const boundGetValue = getValue.bind(obj);
console.log(boundGetValue()); // Output: 42
```

### 6. Enhanced Functionality

- **Array.isArray()**: Returns `true` if the object is an array, and `false` otherwise.

    ```javascript
    console.log(Array.isArray([1, 2, 3])); // Output: true
    console.log(Array.isArray({})); // Output: false
    ```

- **Function.prototype.bind()**: Allows you to create a new function with a specific `this` context.

### 7. Improved Error Handling

ES5 introduced better error handling mechanisms, allowing for more descriptive error messages.

### Summary

ECMAScript 2016, also known as ES7, introduced several new features to JavaScript that enhance the language's capabilities and improve developer productivity. The key features added in ECMAScript 2016 include the exponentiation operator, the exponentiation assignment operator, and the `Array.prototype.includes()` method. Let’s explore each of these features in detail.

### 1. JavaScript Exponentiation Operator (`**`)

The exponentiation operator (`**`) allows you to raise a number to the power of another number. This operator provides a more concise and readable way to perform exponentiation compared to using the `Math.pow()` function.

#### Syntax
```javascript
base ** exponent
```

#### Example
```javascript
const result1 = 2 ** 3; // 2 raised to the power of 3
console.log(result1); // Output: 8

const result2 = 5 ** 2; // 5 raised to the power of 2
console.log(result2); // Output: 25

const result3 = 10 ** -1; // 10 raised to the power of -1 (1/10)
console.log(result3); // Output: 0.1
```

### 2. JavaScript Exponentiation Assignment Operator (`**=`)

The exponentiation assignment operator (`**=`) is a compound assignment operator that allows you to raise a variable to the power of a value and assign the result back to that variable. This operator combines the functionality of the exponentiation operator with assignment.

#### Syntax
```javascript
variable **= exponent;
```

#### Example
```javascript
let x = 2;
x **= 3; // Equivalent to x = x ** 3
console.log(x); // Output: 8

let y = 5;
y **= 2; // Equivalent to y = y ** 2
console.log(y); // Output: 25

let z = 10;
z **= -1; // Equivalent to z = z ** -1
console.log(z); // Output: 0.1
```

### 3. JavaScript `Array.prototype.includes()`

The `includes()` method is used to determine whether an array contains a certain value. It returns `true` if the value is found in the array, and `false` otherwise. This method provides a more readable alternative to using `indexOf()` for checking the presence of an element in an array.

#### Syntax
```javascript
array.includes(value, fromIndex);
```
- **value**: The value to search for in the array.
- **fromIndex** (optional): The index to begin the search (defaults to 0).

#### Example
```javascript
const fruits = ['apple', 'banana', 'orange'];

console.log(fruits.includes('banana')); // Output: true
console.log(fruits.includes('grape')); // Output: false
console.log(fruits.includes('orange', 1)); // Output: true (search starts from index 1)
console.log(fruits.includes('apple', 1)); // Output: false (search starts from index 1)
```

### Summary of New Features in ECMAScript 2016

- **Exponentiation Operator (`**`)**: A concise way to perform exponentiation.
- **Exponentiation Assignment Operator (`**=`)**: A shorthand for raising a variable to a power and assigning the result back to that variable.
- **Array.prototype.includes()**: A method for checking if an array contains a specific value, improving readability compared to `indexOf()`.

ECMAScript 2017, also known as ES8, introduced several new features that further enhance the JavaScript language. Below, we’ll explore the key features added in ECMAScript 2017, including string padding, new methods for objects, async/await for handling asynchronous operations, trailing commas in functions, and a method for getting property descriptors.

### 1. JavaScript String Padding

String padding allows you to pad a string with another string until it reaches a specified length. This can be useful for formatting output.

#### Methods:
- **`String.prototype.padStart(targetLength, padString)`**: Pads the current string with `padString` at the start until the string reaches `targetLength`.
- **`String.prototype.padEnd(targetLength, padString)`**: Pads the current string with `padString` at the end until the string reaches `targetLength`.

#### Example
```javascript
const str = '5';
console.log(str.padStart(2, '0')); // Output: '05'
console.log(str.padEnd(3, '0'));   // Output: '500'
```

### 2. JavaScript Object.entries()

The `Object.entries()` method returns an array of a given object's own enumerable string-keyed property [key, value] pairs. This is useful for iterating over an object's properties.

#### Syntax
```javascript
Object.entries(obj);
```

#### Example
```javascript
const obj = { name: 'Alice', age: 25 };
const entries = Object.entries(obj);
console.log(entries); // Output: [['name', 'Alice'], ['age', 25]]
```

### 3. JavaScript Object.values()

The `Object.values()` method returns an array of a given object's own enumerable string-keyed property values. This is useful for getting just the values from an object.

#### Syntax
```javascript
Object.values(obj);
```

#### Example
```javascript
const obj = { name: 'Alice', age: 25 };
const values = Object.values(obj);
console.log(values); // Output: ['Alice', 25]
```

### 4. JavaScript Async and Await

The `async` and `await` keywords provide a simpler way to work with Promises, allowing you to write asynchronous code that looks synchronous. This feature improves code readability and error handling.

#### Example
```javascript
function fetchData() {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve('Data fetched!');
        }, 1000);
    });
}

async function processData() {
    try {
        const data = await fetchData();
        console.log(data); // Output: Data fetched!
    } catch (error) {
        console.error('Error:', error);
    }
}

processData();
```

### 5. Trailing Commas in Functions

ECMAScript 2017 allows trailing commas in function parameter lists and in the destructuring assignment. This feature helps to make version control diffs cleaner and avoids syntax errors when adding new parameters.

#### Example
```javascript
function myFunction(param1, param2, param3,) {
    console.log(param1, param2, param3);
}

myFunction('a', 'b', 'c',); // Output: a b c

const arr = [1, 2, 3,];
console.log(arr); // Output: [1, 2, 3]
```

### 6. JavaScript `Object.getOwnPropertyDescriptors()`

The `Object.getOwnPropertyDescriptors()` method returns an object containing all own property descriptors for a given object. This is useful for getting detailed information about the properties of an object, including their value, writable, enumerable, and configurable attributes.

#### Syntax
```javascript
Object.getOwnPropertyDescriptors(obj);
```

#### Example
```javascript
const obj = {
    a: 1,
    get b() {
        return this.a + 1;
    }
};

const descriptors = Object.getOwnPropertyDescriptors(obj);
console.log(descriptors);
/*
Output:
{
  a: { value: 1, writable: true, enumerable: true, configurable: true },
  b: { get: [Function: get b], set: undefined, enumerable: true, configurable: true }
}
*/
```

### Summary of New Features in ECMAScript 2017

- **String Padding**: `String.prototype.padStart()` and `String.prototype.padEnd()` for padding strings.
- **Object.entries()**: Returns an array of a given object's own enumerable string-keyed property [key, value] pairs.
- **Object.values()**: Returns an array of a given object's own enumerable string-keyed property values.
- **Async/Await**: Simplifies working with Promises, making asynchronous code easier to read and write.
- **Trailing Commas**: Allows trailing commas in function parameter lists and destructuring assignments.
- **Object.getOwnPropertyDescriptors()**: Returns an object containing all own property descriptors for a given object.

ECMAScript 2017 (also known as ES8) introduced several new features and enhancements to JavaScript. Below are the key features introduced in ES2017:

### 1. JavaScript String Padding

The `padStart()` and `padEnd()` methods allow you to pad a string with another string until it reaches a specified length. This is useful for formatting output.

- **`padStart(targetLength, padString)`**: Pads the current string from the start.

- **`padEnd(targetLength, padString)`**: Pads the current string from the end.

#### Example:

```javascript
const str = '5';
console.log(str.padStart(2, '0')); // Output: '05'
console.log(str.padEnd(2, '0')); // Output: '50'
```

### 2. JavaScript Object.entries()

The `Object.entries()` method returns an array of a given object's own enumerable string-keyed property `[key, value]` pairs. This is useful for iterating over objects.

#### Example:

```javascript
const obj = {
    name: 'Alice',
    age: 25
};

const entries = Object.entries(obj);
console.log(entries); // Output: [['name', 'Alice'], ['age', 25]]
```

### 3. JavaScript Object.values()

The `Object.values()` method returns an array of a given object's own enumerable string-keyed property values. This allows you to easily retrieve all values from an object.

#### Example:

```javascript
const obj = {
    name: 'Bob',
    age: 30
};

const values = Object.values(obj);
console.log(values); // Output: ['Bob', 30]
```

### 4. JavaScript async and await

The `async` and `await` keywords provide a simpler way to work with asynchronous code, making it easier to read and write. An `async` function returns a Promise, and `await` can be used to pause the execution of the function until the Promise is resolved.

#### Example:

```javascript
function fetchData() {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve('Data received');
        }, 1000);
    });
}

async function getData() {
    const result = await fetchData();
    console.log(result); // Output: Data received
}

getData();
```

### 5. Trailing Commas in Functions

ES2017 allows trailing commas in function parameter lists and in the calls to functions. This helps with version control and minimizes diffs when adding or removing parameters.

#### Example:

```javascript
function myFunction(param1, param2, param3,) {
    console.log(param1, param2, param3);
}

myFunction(1, 2, 3,); // Output: 1 2 3
```

### 6. JavaScript Object.getOwnPropertyDescriptors()

The `Object.getOwnPropertyDescriptors()` method returns all own property descriptors of a given object. This can be useful for cloning objects or getting detailed information about properties.

#### Example:

```javascript
const obj = {
    name: 'Charlie',
    age: 35
};

const descriptors = Object.getOwnPropertyDescriptors(obj);
console.log(descriptors);
/*
Output:
{
    name: { value: 'Charlie', writable: true, enumerable: true, configurable: true },
    age: { value: 35, writable: true, enumerable: true, configurable: true }
}
*/
```

### Summary

ECMAScript 2017 introduced several new features that enhance the functionality and usability of JavaScript, including:

- **String Padding**: `padStart()` and `padEnd()` for formatting strings.
- **Object.entries()**: For retrieving key-value pairs from an object.
- **Object.values()**: For retrieving values from an object.
- **Async/Await**: A cleaner syntax for handling asynchronous operations.
- **Trailing Commas**: In function parameter lists and calls for easier maintenance.
- **Object.getOwnPropertyDescriptors()**: For obtaining property descriptors of an object.

These additions improved JavaScript's capabilities, making it easier for developers to write clean, efficient, and maintainable code.

ECMAScript 2018, also known as ES9, introduced several new features that enhance the JavaScript language, particularly in the areas of asynchronous programming, object manipulation, regular expressions, and shared memory. Here’s a detailed overview of the key features added in ECMAScript 2018:

### 1. Asynchronous Iteration

Asynchronous iteration allows you to work with asynchronous data sources using the `for await...of` loop. This is particularly useful for handling streams of data, such as reading files or fetching data from APIs.

#### Syntax
```javascript
for await (const item of asyncIterable) {
    // Process each item
}
```

#### Example
```javascript
async function* asyncGenerator() {
    yield 'Hello';
    yield 'World';
}

async function processAsyncIterable() {
    for await (const value of asyncGenerator()) {
        console.log(value); // Output: Hello World
    }
}

processAsyncIterable();
```

In this example, `asyncGenerator` is an asynchronous generator function that yields values, and `for await...of` is used to iterate over those values.

### 2. Promise.prototype.finally()

The `finally()` method is a new method for Promises that allows you to execute code after a Promise is settled (either fulfilled or rejected), regardless of the outcome. This is useful for cleanup operations or final actions that should occur after the Promise is handled.

#### Syntax
```javascript
promise.finally(onFinally);
```

#### Example
```javascript
const fetchData = () => {
    return new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve('Data fetched!');
        }, 1000);
    });
};

fetchData()
    .then(data => {
        console.log(data); // Output: Data fetched!
    })
    .catch(error => {
        console.error(error);
    })
    .finally(() => {
        console.log('Cleanup actions can go here.'); // Output: Cleanup actions can go here.
    });
```

### 3. Object Rest Properties

Object rest properties allow you to extract properties from an object and collect the remaining properties into a new object. This is useful for creating new objects while omitting certain properties.

#### Syntax
```javascript
const { prop1, prop2, ...rest } = obj;
```

#### Example
```javascript
const person = {
    name: 'Alice',
    age: 30,
    city: 'New York'
};

const { name, ...rest } = person;
console.log(name); // Output: Alice
console.log(rest); // Output: { age: 30, city: 'New York' }
```

### 4. New RegExp Features

ECMAScript 2018 introduced several enhancements to regular expressions, including:
- **Named Capture Groups**: Allows you to name capture groups in regular expressions, making it easier to work with matched substrings.
- **Lookbehind Assertions**: Enables you to assert what precedes a match without including it in the match.
- **Unicode Property Escapes**: Allows matching Unicode characters based on their properties.

#### Example of Named Capture Groups
```javascript
const regex = /(?<firstName>\w+) (?<lastName>\w+)/;
const str = 'John Doe';
const match = regex.exec(str);
console.log(match.groups.firstName); // Output: John
console.log(match.groups.lastName); // Output: Doe
```

#### Example of Lookbehind Assertions
```javascript
const regex = /(?<=@)\w+/;
const str = 'user@example.com';
const match = regex.exec(str);
console.log(match[0]); // Output: example
```

#### Example of Unicode Property Escapes
```javascript
const regex = /\p{Script=Greek}/u; // Matches any Greek character
const str = 'αβγ';
console.log(regex.test(str)); // Output: true
```

### 5. JavaScript Shared Memory

Shared memory allows JavaScript to share memory between different threads using `SharedArrayBuffer`. This is particularly useful for web workers and allows for more efficient data sharing in concurrent programming.

#### Example
```javascript
// Create a SharedArrayBuffer with a byte length of 4
const sharedBuffer = new SharedArrayBuffer(4);
const sharedArray = new Int32Array(sharedBuffer);

// Set a value in the shared array
sharedArray[0] = 42;

// Access the value from the shared array
console.log(sharedArray[0]); // Output: 42
```

### Summary of New Features in ECMAScript 2018

- **Asynchronous Iteration**: Introduces `for await...of` for iterating over asynchronous data sources.
- **Promise.prototype.finally()**: Allows executing code after a Promise is settled, regardless of its outcome.
- **Object Rest Properties**: Enables extracting properties from objects while collecting remaining properties into a new object.
- **New RegExp Features**: Includes named capture groups, lookbehind assertions, and Unicode property escapes for enhanced regex capabilities.
- **JavaScript Shared Memory**: Introduces `SharedArrayBuffer` for sharing memory between threads, useful in concurrent programming.

These features enhance the functionality of JavaScript, making it more powerful and flexible for developers working on modern web applications.

ECMAScript 2019, also known as ES10, introduced several new features that enhance the JavaScript language, providing developers with more tools for working with strings, objects, arrays, and functions. Here’s a detailed overview of the key features added in ECMAScript 2019:

### 1. `String.prototype.trimStart()` and `String.prototype.trimEnd()`

The `trimStart()` and `trimEnd()` methods are used to remove whitespace from the beginning and end of a string, respectively. These methods are useful for cleaning up user input or formatting strings.

#### Example
```javascript
const str = '   Hello, World!   ';

console.log(str.trimStart()); // Output: 'Hello, World!   '
console.log(str.trimEnd());   // Output: '   Hello, World!'
```

### 2. `Object.fromEntries()`

The `Object.fromEntries()` method transforms a list of key-value pairs (typically from a `Map` or an array of arrays) into an object. This is useful for converting data structures into plain objects.

#### Example
```javascript
const entries = new Map([
    ['name', 'Alice'],
    ['age', 30]
]);

const obj = Object.fromEntries(entries);
console.log(obj); // Output: { name: 'Alice', age: 30 }

const arr = [['name', 'Bob'], ['age', 25]];
const objFromArr = Object.fromEntries(arr);
console.log(objFromArr); // Output: { name: 'Bob', age: 25 }
```

### 3. Optional Catch Binding

In ES2019, the `catch` clause in a `try...catch` statement can now omit the binding of the error variable if it is not needed. This allows for cleaner code when the error is not used.

#### Example
```javascript
try {
    // Some code that may throw an error
} catch {
    console.log('An error occurred, but we don\'t need to know what it was.');
}
```

### 4. `Array.prototype.flat()`

The `flat()` method creates a new array with all sub-array elements concatenated into it recursively up to the specified depth. This is useful for flattening nested arrays.

#### Example
```javascript
const nestedArray = [1, 2, [3, 4, [5, 6]]];
const flatArray = nestedArray.flat(2); // Flattens to a depth of 2
console.log(flatArray); // Output: [1, 2, 3, 4, 5, 6]
```

### 5. `Array.prototype.flatMap()`

The `flatMap()` method first maps each element using a mapping function, then flattens the result into a new array. This is useful for combining mapping and flattening operations in a single method.

#### Example
```javascript
const arr = [1, 2, 3, 4];
const flatMappedArray = arr.flatMap(x => [x, x * 2]);
console.log(flatMappedArray); // Output: [1, 2, 2, 4, 3, 6, 4, 8]
```

### 6. Revised `Array.prototype.sort()`

The `Array.prototype.sort()` method now behaves more consistently across different engines. It is recommended to provide a compare function to ensure predictable sorting behavior.

#### Example
```javascript
const numbers = [4, 2, 3, 1];
numbers.sort(); // Sorts as strings by default
console.log(numbers); // Output: [1, 2, 3, 4]

const sortedNumbers = [4, 2, 3, 1].sort((a, b) => a - b); // Sorts numerically
console.log(sortedNumbers); // Output: [1, 2, 3, 4]
```

### 7. Revised `JSON.stringify()`

The `JSON.stringify()` method now supports a second argument for optional `replacer` functions. This allows for more control over how objects are serialized into JSON format.

#### Example
```javascript
const obj = {
    name: 'Alice',
    age: 30,
    password: 'secret'
};

const jsonString = JSON.stringify(obj, (key, value) => {
    if (key === 'password') {
        return undefined; // Exclude the password field
    }
    return value;
});
console.log(jsonString); // Output: {"name":"Alice","age":30}
```

### 8. Separator Symbols Allowed in String Literals

ES2019 allows the use of separator symbols (like underscores) in numeric literals for better readability. However, this feature is primarily for numeric literals, and there's no direct impact on string literals.

#### Example
```javascript
const largeNumber = 1_000_000; // More readable representation of 1000000
console.log(largeNumber); // Output: 1000000
```

### 9. Revised `Function.prototype.toString()`

The `Function.prototype.toString()` method now returns the exact source code of the function, including comments and whitespace. This change improves the behavior of `toString()` for functions, making it more predictable and useful for debugging.

#### Example
```javascript
function example() {
    // This is a comment
    return 'Hello, World!';
}

console.log(example.toString());
/*
Output:
function example() {
    // This is a comment
    return 'Hello, World!';
}
*/
```

### Summary of New Features in ECMAScript 2019

- **String.prototype.trimStart()** and **String.prototype.trimEnd()**: Methods for trimming whitespace from the beginning and end of strings.
- **Object.fromEntries()**: Converts a list of key-value pairs into an object.
- **Optional catch binding**: Allows omission of the error variable in `catch` clauses.
- **Array.prototype.flat()**: Flattens nested arrays to a specified depth.
- **Array.prototype.flatMap()**: Maps and flattens arrays in one operation.
- **Revised Array.sort()**: Improved consistency in sorting behavior.
- **Revised JSON.stringify()**: Enhanced control over JSON serialization with a `replacer` function.
- **Separator symbols in numeric literals**: Improves readability of large numbers.
- **Revised Function.prototype.toString()**: Returns the exact source code of functions, including comments.

These features enhance the functionality and usability of JavaScript, making it easier for developers to write cleaner, more efficient code.

ECMAScript 2020, also known as ES11, introduced several powerful new features that enhance the JavaScript language, particularly in areas such as data types, operators, and asynchronous programming. Here’s a detailed overview of the key features added in ECMAScript 2020:

### 1. BigInt

**BigInt** is a new primitive data type that allows you to represent integers larger than the maximum safe integer limit (2^53 - 1). BigInt can be created by appending `n` to the end of an integer literal or by using the `BigInt()` constructor.

#### Example
```javascript
const bigInt1 = 1234567890123456789012345678901234567890n; // Using the 'n' suffix
const bigInt2 = BigInt("1234567890123456789012345678901234567890"); // Using the constructor

console.log(bigInt1 + bigInt2); // Output: 2469135780246913578024691357802469135780n
```

### 2. `String.prototype.matchAll()`

The `matchAll()` method returns an iterator of all matches of a regular expression against a string. This feature is useful for finding all occurrences of a pattern within a string.

#### Example
```javascript
const str = 'test1 test2 test3';
const regex = /test(\d)/g;

const matches = str.matchAll(regex);
for (const match of matches) {
    console.log(`Found: ${match[0]}, Group: ${match[1]}`); 
}
// Output:
// Found: test1, Group: 1
// Found: test2, Group: 2
// Found: test3, Group: 3
```

### 3. The Nullish Coalescing Operator (`??`)

The nullish coalescing operator (`??`) allows you to provide a default value when dealing with `null` or `undefined`. This operator is useful for setting defaults without overriding falsy values like `0`, `false`, or `""`.

#### Example
```javascript
const value1 = null;
const value2 = 0;

console.log(value1 ?? 'default'); // Output: 'default'
console.log(value2 ?? 'default'); // Output: 0
```

### 4. The Optional Chaining Operator (`?.`)

The optional chaining operator (`?.`) allows you to safely access deeply nested properties of an object without having to check if each reference in the chain is valid. If a reference is `null` or `undefined`, it short-circuits and returns `undefined`.

#### Example
```javascript
const user = {
    name: 'Alice',
    address: {
        city: 'Wonderland'
    }
};

console.log(user.address?.city); // Output: 'Wonderland'
console.log(user.address?.zip); // Output: undefined
```

### 5. Logical AND Assignment Operator (`&&=`)

The logical AND assignment operator (`&&=`) is a compound assignment operator that assigns a value to a variable only if the variable is truthy.

#### Example
```javascript
let a = 5;
let b = 0;

a &&= 10; // a remains 10 because a is truthy
b &&= 10; // b remains 0 because b is falsy

console.log(a); // Output: 10
console.log(b); // Output: 0
```

### 6. Logical OR Assignment Operator (`||=`)

The logical OR assignment operator (`||=`) assigns a value to a variable only if the variable is falsy.

#### Example
```javascript
let x = 0;
let y = 5;

x ||= 10; // x becomes 10 because x is falsy
y ||= 10; // y remains 5 because y is truthy

console.log(x); // Output: 10
console.log(y); // Output: 5
```

### 7. Nullish Coalescing Assignment Operator (`??=`)

The nullish coalescing assignment operator (`??=`) assigns a value to a variable only if the variable is `null` or `undefined`.

#### Example
```javascript
let z = null;
let w = 5;

z ??= 10; // z becomes 10 because z is null
w ??= 10; // w remains 5 because w is not null or undefined

console.log(z); // Output: 10
console.log(w); // Output: 5
```

### 8. `Promise.allSettled()`

The `Promise.allSettled()` method takes an array of Promises and returns a single Promise that resolves after all of the given Promises have either resolved or rejected. This method is useful for handling multiple asynchronous operations where you want to know the outcome of all Promises.

#### Example
```javascript
const promise1 = Promise.resolve(3);
const promise2 = new Promise((resolve, reject) => setTimeout(reject, 100, 'error'));
const promise3 = Promise.resolve(42);

Promise.allSettled([promise1, promise2, promise3])
    .then(results => {
        results.forEach((result) => {
            if (result.status === 'fulfilled') {
                console.log(`Fulfilled with value: ${result.value}`);
            } else {
                console.log(`Rejected with reason: ${result.reason}`);
            }
        });
    });
/*
Output:
Fulfilled with value: 3
Rejected with reason: error
Fulfilled with value: 42
*/
```

### 9. Dynamic Import

Dynamic import allows you to load modules asynchronously. This feature is useful for code splitting and loading modules on demand, improving performance by reducing the initial load time.

#### Syntax
```javascript
import(moduleSpecifier)
    .then(module => {
        // Use the imported module
    });
```

#### Example
```javascript
const loadModule = async () => {
    const module = await import('./myModule.js');
    module.myFunction();
};

loadModule();
```

### Summary of New Features in ECMAScript 2020

- **BigInt**: A new primitive type for representing large integers.
- **String.prototype.matchAll()**: Returns an iterator of all matches of a regular expression against a string.
- **Nullish Coalescing Operator (`??`)**: Provides a default value when dealing with `null` or `undefined`.
- **Optional Chaining Operator (`?.`)**: Safely accesses deeply nested properties of an object.
- **Logical AND Assignment Operator (`&&=`)**: Assigns a value only if the variable is truthy.
- **Logical OR Assignment Operator (`||=`)**: Assigns a value only if the variable is falsy.
- **Nullish Coalescing Assignment Operator (`??=`)**: Assigns a value only if the variable is `null` or `undefined`.
- **Promise.allSettled()**: Resolves after all Promises have settled, regardless of their outcome.
- **Dynamic Import**: Allows loading modules asynchronously.

These features enhance the flexibility and usability of JavaScript, making it easier for developers to write modern and efficient code.

ECMAScript 2021, also known as ES12, introduced several new features that enhance the JavaScript language, providing developers with more tools for working with promises, strings, and numeric literals. Here’s a detailed overview of the key features added in ECMAScript 2021:

### 1. `Promise.any()`

The `Promise.any()` method takes an iterable of Promise objects and, as soon as one of the promises in the iterable fulfills, returns a single Promise that resolves with the value from that promise. If no promises in the iterable fulfill (i.e., all of them are rejected), then the returned Promise is rejected with an `AggregateError`, a new subclass of `Error` that groups together individual errors.

#### Syntax
```javascript
Promise.any(iterable);
```

#### Example
```javascript
const promise1 = Promise.reject('Error 1');
const promise2 = Promise.reject('Error 2');
const promise3 = Promise.resolve('Success!');

Promise.any([promise1, promise2, promise3])
    .then((result) => {
        console.log(result); // Output: 'Success!'
    })
    .catch((error) => {
        console.error(error); // This will not run
    });
```

If all promises are rejected:
```javascript
const promiseA = Promise.reject('Error A');
const promiseB = Promise.reject('Error B');

Promise.any([promiseA, promiseB])
    .catch((error) => {
        console.error(error); // Output: AggregateError: All promises were rejected
    });
```

### 2. `String.prototype.replaceAll()`

The `replaceAll()` method returns a new string with all matches of a pattern replaced by a replacement. This method is useful for replacing all occurrences of a substring or pattern in a string without needing to use a global regular expression.

#### Syntax
```javascript
string.replaceAll(searchValue, replaceValue);
```

#### Example
```javascript
const str = 'Hello, World! Hello, everyone!';
const newStr = str.replaceAll('Hello', 'Hi');

console.log(newStr); // Output: 'Hi, World! Hi, everyone!'
```

You can also use it with regular expressions:
```javascript
const text = 'The cat sat on the mat.';
const newText = text.replaceAll(/at/g, 'og');

console.log(newText); // Output: 'The cog sog on the mog.'
```

### 3. Numeric Separators (`_`)

Numeric separators allow you to use underscores (`_`) as visual separators in numeric literals to improve readability. This feature is particularly useful for large numbers, making them easier to read and understand.

#### Example
```javascript
const billion = 1_000_000_000; // One billion
console.log(billion); // Output: 1000000000

const hex = 0xFF_FF_FF; // Hexadecimal representation
console.log(hex); // Output: 16777215

const binary = 0b1010_1011; // Binary representation
console.log(binary); // Output: 171

const float = 1_234.56; // Floating-point number
console.log(float); // Output: 1234.56
```

### Summary of New Features in ECMAScript 2021

- **`Promise.any()`**: Returns a single Promise that resolves as soon as one of the promises in the iterable fulfills; if all are rejected, it rejects with an `AggregateError`.
- **`String.prototype.replaceAll()`**: Replaces all occurrences of a substring or pattern in a string with a specified replacement.
- **Numeric Separators (`_`)**: Allows the use of underscores in numeric literals for better readability.

These features enhance the functionality and usability of JavaScript, making it easier for developers to write cleaner, more efficient code while improving the handling of asynchronous operations and string manipulations.

ECMAScript 2022 (also known as ES13) introduced several new features that enhance the language's capabilities and improve developer experience. Below are the key features introduced in ES2022:

### 1. Array `at()`

The `at()` method allows you to access elements in an array using a relative index. This method can handle negative integers, which count back from the last item in the array.

#### Example:

```javascript
const array = [1, 2, 3, 4, 5];

console.log(array.at(0)); // Output: 1
console.log(array.at(-1)); // Output: 5 (last element)
console.log(array.at(-2)); // Output: 4 (second to last element)
```

### 2. String `at()`

Similar to the `at()` method for arrays, the `String.prototype.at()` method allows you to access characters in a string using a relative index.

#### Example:

```javascript
const str = 'Hello';

console.log(str.at(0)); // Output: 'H'
console.log(str.at(-1)); // Output: 'o' (last character)
console.log(str.at(-2)); // Output: 'l' (second to last character)
```

### 3. Regular Expression `/d`

The `/d` flag in regular expressions is used to match Unicode digits. This allows for better handling of numbers in various scripts and languages.

#### Example:

```javascript
const regex = /\d+/u; // Matches Unicode digits

console.log(regex.test('123')); // Output: true
console.log(regex.test('一二三')); // Output: false
console.log(regex.test('123一二三')); // Output: true
```

### 4. `Object.hasOwn()`

The `Object.hasOwn()` method provides a safe way to check if an object has a property as its own (not inherited). This method is a more concise alternative to `Object.prototype.hasOwnProperty()`.

#### Example:

```javascript
const obj = { a: 1 };

console.log(Object.hasOwn(obj, 'a')); // Output: true
console.log(Object.hasOwn(obj, 'b')); // Output: false
```

### 5. `error.cause`

The `cause` property allows you to attach a cause to an error when throwing it. This provides more context about the error, making it easier to debug.

#### Example:

```javascript
try {
    throw new Error('Something went wrong', { cause: 'Invalid input' });
} catch (error) {
    console.log(error.message); // Output: Something went wrong
    console.log(error.cause); // Output: Invalid input
}
```

### 6. `await import`

The `await import` syntax allows you to dynamically import modules asynchronously. This can be useful for code splitting and loading modules only when they are needed.

#### Example:

```javascript
async function loadModule() {
    const module = await import('./myModule.js');
    module.myFunction();
}

loadModule();
```

### 7. Class Field Declarations

Class field declarations allow you to define properties directly in the class body, making the syntax cleaner and more intuitive.

#### Example:

```javascript
class Person {
    name = 'Alice'; // Class field
    age = 30; // Another class field

    greet() {
        console.log(`Hello, my name is ${this.name}`);
    }
}

const person = new Person();
console.log(person.name); // Output: Alice
```

### 8. Private Methods and Fields

Private methods and fields in classes are prefixed with `#` and are only accessible within the class. This encapsulation improves data privacy and integrity.

#### Example:

```javascript
class Counter {
    #count = 0; // Private field

    increment() {
        this.#count++;
    }

    getCount() {
        return this.#count;
    }

    #privateMethod() {
        console.log('This is a private method');
    }
}

const counter = new Counter();
counter.increment();
console.log(counter.getCount()); // Output: 1
// counter.#privateMethod(); // SyntaxError: Private field '#privateMethod' must be declared in an enclosing class
```

### Summary

ECMAScript 2022 introduced several enhancements that improve the usability and functionality of JavaScript, including:

- **Array `at()`**: Access elements using relative indices.
- **String `at()`**: Access characters using relative indices.
- **Regular Expression `/d`**: Match Unicode digits.
- **`Object.hasOwn()`**: A safer way to check for own properties.
- **`error.cause`**: Attach a cause to errors for better debugging.
- **`await import`**: Dynamically import modules asynchronously.
- **Class Field Declarations**: Define properties directly in classes.
- **Private Methods and Fields**: Enhance encapsulation and data privacy.

These features enhance JavaScript's capabilities, making it easier for developers to write clean, efficient, and maintainable code.

ECMAScript 2023 (also known as ES14) introduced several new features that enhance the functionality and usability of JavaScript. Below are the key features introduced in ES2023:

### 1. `Array.prototype.findLast()`

The `findLast()` method returns the value of the last element in the array that satisfies the provided testing function. It executes the callback function from the last element to the first.

#### Example:

```javascript
const array = [5, 12, 50, 130, 44];

const found = array.findLast(element => element > 45);
console.log(found); // Output: 130
```

### 2. `Array.prototype.findLastIndex()`

The `findLastIndex()` method returns the index of the last element in the array that satisfies the provided testing function. It operates similarly to `findLast()`, but returns the index instead of the element.

#### Example:

```javascript
const array = [5, 12, 50, 130, 44];

const index = array.findLastIndex(element => element > 45);
console.log(index); // Output: 3 (index of 130)
```

### 3. `Array.prototype.toReversed()`

The `toReversed()` method returns a new array with the elements in reverse order without modifying the original array.

#### Example:

```javascript
const array = [1, 2, 3, 4, 5];

const reversedArray = array.toReversed();
console.log(reversedArray); // Output: [5, 4, 3, 2, 1]
console.log(array); // Output: [1, 2, 3, 4, 5] (original array remains unchanged)
```

### 4. `Array.prototype.toSorted()`

The `toSorted()` method returns a new array with the elements sorted according to the specified compare function without modifying the original array.

#### Example:

```javascript
const array = [5, 2, 9, 1, 5, 6];

const sortedArray = array.toSorted((a, b) => a - b);
console.log(sortedArray); // Output: [1, 2, 5, 5, 6, 9]
console.log(array); // Output: [5, 2, 9, 1, 5, 6] (original array remains unchanged)
```

### 5. `Array.prototype.toSpliced()`

The `toSpliced()` method returns a new array with elements removed or replaced based on the specified start index and delete count, without modifying the original array.

#### Example:

```javascript
const array = [1, 2, 3, 4, 5];

const splicedArray = array.toSpliced(1, 2, 10, 20);
console.log(splicedArray); // Output: [1, 10, 20, 4, 5]
console.log(array); // Output: [1, 2, 3, 4, 5] (original array remains unchanged)
```

### 6. `Array.prototype.with()`

The `with()` method creates a new array with a specific index replaced by a new value, without modifying the original array.

#### Example:

```javascript
const array = [1, 2, 3, 4, 5];

const newArray = array.with(2, 10);
console.log(newArray); // Output: [1, 2, 10, 4, 5]
console.log(array); // Output: [1, 2, 3, 4, 5] (original array remains unchanged)
```

### 7. `#!` (Shebang)

The shebang (`#!`) is a special syntax that allows for specifying the interpreter for scripts. This feature is particularly useful for Node.js scripts and makes it easier to run scripts directly from the command line.

#### Example:

```javascript
#!/usr/bin/env node

console.log('This script is running with Node.js!');
```

### Summary

ECMAScript 2023 introduced several enhancements that improve the usability and functionality of JavaScript, including:

- **Array `findLast()`**: Find the last element that satisfies a condition.
- **Array `findLastIndex()`**: Find the index of the last element that satisfies a condition.
- **Array `toReversed()`**: Return a new array with elements in reverse order.
- **Array `toSorted()`**: Return a new array sorted without modifying the original.
- **Array `toSpliced()`**: Return a new array with elements removed or replaced.
- **Array `with()`**: Create a new array with a specified index replaced by a new value.
- **`#!` (Shebang)**: Specify the interpreter for scripts, making it easier to run scripts directly.

These features enhance JavaScript's capabilities, making it easier for developers to write clean, efficient, and maintainable code.

ECMAScript 2024, also known as ES14, introduces several new features aimed at improving the handling of data structures and enhancing date/time management in JavaScript. Below is a detailed overview of the key features added in ECMAScript 2024:

### 1. `Object.groupBy()`

The `Object.groupBy()` method allows you to group the properties of an object based on a specified criterion. This method takes a callback function that defines the grouping logic and returns an object where the keys are the results of the callback and the values are arrays of objects that share the same key.

#### Syntax
```javascript
Object.groupBy(obj, callback);
```

#### Example
```javascript
const data = [
    { name: 'Alice', age: 25 },
    { name: 'Bob', age: 30 },
    { name: 'Charlie', age: 25 },
];

const groupedByAge = Object.groupBy(data, person => person.age);
console.log(groupedByAge);
/*
Output:
{
    '25': [{ name: 'Alice', age: 25 }, { name: 'Charlie', age: 25 }],
    '30': [{ name: 'Bob', age: 30 }]
}
*/
```

### 2. `Map.groupBy()`

Similar to `Object.groupBy()`, the `Map.groupBy()` method allows you to group entries in a `Map` based on a specified criterion. This method returns a new `Map` where the keys are the results of the callback function and the values are arrays of entries that share the same key.

#### Syntax
```javascript
map.groupBy(callback);
```

#### Example
```javascript
const map = new Map([
    ['Alice', 25],
    ['Bob', 30],
    ['Charlie', 25],
]);

const groupedByAge = map.groupBy((value, key) => value);
console.log(groupedByAge);
/*
Output:
Map(2) {
    25 => [ ['Alice', 25], ['Charlie', 25] ],
    30 => [ ['Bob', 30] ]
}
*/
```

### 3. `Temporal.PlainDate`

The `Temporal.PlainDate` class is part of the Temporal API, which provides a modern way to handle dates and times in JavaScript. `PlainDate` represents a date without a time zone, allowing for easy manipulation and formatting of date values.

#### Example
```javascript
const date = Temporal.PlainDate.from('2024-04-17');
console.log(date); // Output: 2024-04-17
```

### 4. `Temporal.PlainTime`

The `Temporal.PlainTime` class represents a time without a time zone or date. It allows you to work with time values independently of any date context.

#### Example
```javascript
const time = Temporal.PlainTime.from('14:30:00');
console.log(time); // Output: 14:30:00
```

### 5. `Temporal.PlainMonthDay`

The `Temporal.PlainMonthDay` class represents a month and day without a year, allowing you to work with month-day combinations regardless of the year.

#### Example
```javascript
const monthDay = Temporal.PlainMonthDay.from('04-17');
console.log(monthDay); // Output: 04-17
```

### 6. `Temporal.PlainYearMonth`

The `Temporal.PlainYearMonth` class represents a year and month without a day. This is useful for scenarios where you only need to work with the year and month.

#### Example
```javascript
const yearMonth = Temporal.PlainYearMonth.from('2024-04');
console.log(yearMonth); // Output: 2024-04
```

### Summary of New Features in ECMAScript 2024

- **`Object.groupBy()`**: Groups properties of an object based on a specified criterion.
- **`Map.groupBy()`**: Groups entries in a `Map` based on a specified criterion.
- **`Temporal.PlainDate`**: Represents a date without a time zone.
- **`Temporal.PlainTime`**: Represents a time without a date or time zone.
- **`Temporal.PlainMonthDay`**: Represents a month and day without a year.
- **`Temporal.PlainYearMonth`**: Represents a year and month without a specific day.

These features enhance the capabilities of JavaScript, particularly in data manipulation and date/time handling, making it easier for developers to work with complex data structures and temporal values.

JavaScript tooling is essential for modern web development, providing developers with the necessary tools to build, manage, and optimize their applications. Here’s an overview of some of the most commonly used tools in the JavaScript ecosystem: NPM, Babel, and Webpack/Vite.

### 1. NPM (Node Package Manager)

**NPM** is the default package manager for Node.js and is widely used for managing JavaScript libraries and dependencies. It allows developers to install, share, and manage packages in their projects.

#### Key Features:

- **Package Management**: NPM allows you to easily install packages from the NPM registry using the command line.
  
  ```bash
  npm install package-name
  ```

- **Package.json**: This file is created in your project directory when you initialize a new Node.js project. It contains metadata about the project, including dependencies, scripts, and versioning.

  ```json
  {
    "name": "my-project",
    "version": "1.0.0",
    "dependencies": {
      "express": "^4.17.1"
    },
    "scripts": {
      "start": "node index.js"
    }
  }
  ```

- **Versioning**: NPM allows you to specify versions for your dependencies, ensuring compatibility and stability in your project.

- **Scripts**: You can define custom scripts in the `package.json` file to automate tasks, such as running tests or building your project.

  ```bash
  npm run start
  ```

### 2. Babel

**Babel** is a JavaScript compiler that allows developers to use the latest JavaScript features while maintaining compatibility with older browsers. It transforms modern JavaScript (ES6+) into a version that can run in environments that do not support these features.

#### Key Features:

- **Transpilation**: Babel converts ES6+ code into ES5, making it compatible with older browsers.

- **Plugins and Presets**: Babel uses a system of plugins and presets to enable specific transformations. For example, you can use the `@babel/preset-env` preset to automatically include the necessary transformations based on your target environments.

  ```bash
  npm install --save-dev @babel/core @babel/cli @babel/preset-env
  ```

- **Configuration**: You can configure Babel using a `.babelrc` file or directly in your `package.json`.

  ```json
  {
    "presets": ["@babel/preset-env"]
  }
  ```

- **Polyfills**: Babel can also include polyfills for new JavaScript features that are not natively supported in older environments.

### 3. Webpack

**Webpack** is a powerful module bundler for JavaScript applications. It takes modules with dependencies and generates static assets representing those modules. Webpack is highly configurable and can handle various file types, including JavaScript, CSS, images, and more.

#### Key Features:

- **Module Bundling**: Webpack bundles JavaScript files and other assets into a single or multiple output files, optimizing loading times.

- **Loaders**: Loaders allow you to preprocess files as you import or "load" them. For example, you can use `babel-loader` to transpile JavaScript files with Babel.

  ```bash
  npm install --save-dev webpack webpack-cli babel-loader
  ```

- **Plugins**: Webpack has a rich plugin system that allows you to extend its functionality. Common plugins include `HtmlWebpackPlugin` for generating HTML files and `MiniCssExtractPlugin` for extracting CSS into separate files.

- **Development Server**: Webpack Dev Server provides a local development server with live reloading capabilities.

#### Example Configuration (webpack.config.js):

```javascript
const path = require('path');

module.exports = {
    entry: './src/index.js',
    output: {
        filename: 'bundle.js',
        path: path.resolve(__dirname, 'dist'),
    },
    module: {
        rules: [
            {
                test: /\.js$/,
                exclude: /node_modules/,
                use: {
                    loader: 'babel-loader',
                },
            },
        ],
    },
    devServer: {
        contentBase: './dist',
    },
};
```

### 4. Vite

**Vite** is a modern build tool that focuses on speed and performance. It leverages native ES modules in the browser for development and uses Rollup for production builds. Vite is particularly popular for its fast hot module replacement (HMR) and simplified configuration.

#### Key Features:

- **Instant Server Start**: Vite starts the development server quickly, regardless of the size of your application.

- **Hot Module Replacement (HMR)**: Vite updates modules in the browser without a full reload, providing a seamless development experience.

- **Optimized Build**: Vite uses Rollup under the hood for production builds, optimizing code for performance.

- **Configurable**: Vite has a straightforward configuration file (`vite.config.js`) for customizing its behavior.

#### Example Configuration (vite.config.js):

```javascript
import { defineConfig } from 'vite';

export default defineConfig({
    root: 'src',
    build: {
        outDir: '../dist',
    },
});
```

### Summary

- **NPM** is the package manager for managing JavaScript libraries and dependencies, allowing for easy installation and script automation.
- **Babel** is a JavaScript compiler that enables the use of modern JavaScript features while ensuring compatibility with older browsers.
- **Webpack** is a powerful module bundler that optimizes loading times by bundling JavaScript files and other assets, with support for loaders and plugins.
- **Vite** is a modern build tool that offers fast development experiences with instant server starts and hot module replacement, using Rollup for optimized production builds.

These tools are essential for modern JavaScript development, helping developers create efficient, maintainable, and high-performance applications.


Object-oriented programming (OOP) is a programming paradigm that uses "objects" to represent data and methods to manipulate that data. JavaScript supports OOP through the use of classes, inheritance, and other features. In this overview, we'll explore the key concepts of object-oriented JavaScript, including classes, inheritance, and the `super` keyword, along with other OOP principles.

### Key Concepts of Object-Oriented Programming

1. **Classes**: A class is a blueprint for creating objects. It defines properties and methods that the created objects will have.
2. **Objects**: An object is an instance of a class. It contains data and functions that operate on that data.
3. **Inheritance**: Inheritance allows one class to inherit properties and methods from another class, promoting code reuse and creating a hierarchical relationship.
4. **Encapsulation**: Encapsulation is the bundling of data and methods that operate on that data within a single unit or class, restricting access to some components.
5. **Polymorphism**: Polymorphism allows methods to do different things based on the object it is acting upon, typically through method overriding in subclasses.

### 1. Classes in JavaScript

In ES6 (ECMAScript 2015), JavaScript introduced a class syntax that provides a clearer and more concise way to create objects and handle inheritance.

#### Defining a Class
```javascript
class Person {
    constructor(name, age) {
        this.name = name; // Property
        this.age = age;   // Property
    }

    greet() { // Method
        console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
    }
}

// Creating an instance of the class
const alice = new Person('Alice', 30);
alice.greet(); // Output: Hello, my name is Alice and I am 30 years old.
```

### 2. Inheritance

Inheritance allows one class (the child class) to inherit properties and methods from another class (the parent class). This promotes code reuse and establishes a hierarchical relationship between classes.

#### Syntax for Inheritance
You can use the `extends` keyword to create a subclass that inherits from a parent class.

```javascript
class Employee extends Person {
    constructor(name, age, position) {
        super(name, age); // Call the parent class constructor
        this.position = position; // Additional property
    }

    describe() {
        console.log(`I am ${this.name}, a ${this.position}.`);
    }
}

// Creating an instance of the subclass
const bob = new Employee('Bob', 25, 'Developer');
bob.greet(); // Output: Hello, my name is Bob and I am 25 years old.
bob.describe(); // Output: I am Bob, a Developer.
```

### 3. The `super` Keyword

The `super` keyword is used to call the constructor and methods of the parent class from the child class. This allows the child class to inherit properties and methods from the parent class.

#### Example of Using `super`
```javascript
class Animal {
    constructor(name) {
        this.name = name;
    }

    speak() {
        console.log(`${this.name} makes a noise.`);
    }
}

class Dog extends Animal {
    constructor(name) {
        super(name); // Call the parent class constructor
    }

    speak() {
        console.log(`${this.name} barks.`);
    }
}

const dog = new Dog('Rex');
dog.speak(); // Output: Rex barks.
```

### 4. Encapsulation

Encapsulation is the practice of keeping the internal state of an object private and exposing only necessary methods. In JavaScript, we can use closures or symbols to create private properties, but in modern JavaScript (ES2022), we can use the `#` syntax to define private fields.

#### Example of Encapsulation with Private Fields
```javascript
class BankAccount {
    #balance; // Private field

    constructor(initialBalance) {
        this.#balance = initialBalance;
    }

    deposit(amount) {
        this.#balance += amount;
    }

    withdraw(amount) {
        if (amount <= this.#balance) {
            this.#balance -= amount;
        } else {
            console.log('Insufficient funds');
        }
    }

    getBalance() {
        return this.#balance;
    }
}

const account = new BankAccount(100);
account.deposit(50);
console.log(account.getBalance()); // Output: 150
account.withdraw(200); // Output: Insufficient funds
```

### 5. Polymorphism

Polymorphism allows methods to be overridden in subclasses, enabling different behaviors based on the object type. This is particularly useful when working with a hierarchy of classes.

#### Example of Polymorphism
```javascript
class Cat extends Animal {
    speak() {
        console.log(`${this.name} meows.`);
    }
}

const cat = new Cat('Whiskers');
cat.speak(); // Output: Whiskers meows.

const animals = [dog, cat];
animals.forEach(animal => animal.speak()); 
// Output:
// Rex barks.
// Whiskers meows.
```

### Summary of Object-Oriented JavaScript Concepts

- **Classes**: Define blueprints for creating objects with properties and methods.
- **Objects**: Instances of classes that encapsulate data and behavior.
- **Inheritance**: Allows classes to inherit properties and methods from other classes using the `extends` keyword.
- **Encapsulation**: Bundles data and methods, restricting access to internal state, often using private fields.
- **Polymorphism**: Enables method overriding in subclasses, allowing for different implementations of the same method.

### Conclusion

Object-oriented programming in JavaScript provides developers with powerful tools for organizing and structuring code. By using classes, inheritance, and the `super` keyword, you can create reusable and maintainable code that adheres to OOP principles. Understanding these concepts is essential for building complex applications and leveraging the full potential of JavaScript.


Certainly! Let's dive deeper into the concepts of Object-Oriented Programming (OOP) in JavaScript with more comprehensive examples that illustrate classes, inheritance, encapsulation, polymorphism, and the use of the `super` keyword.

### 1. Classes and Constructors

Classes are the foundation of OOP in JavaScript. They can have constructors to initialize properties and methods to define behavior.

#### Example: A Simple Class with Constructor
```javascript
class Vehicle {
    constructor(make, model, year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    displayInfo() {
        console.log(`Vehicle Info: ${this.year} ${this.make} ${this.model}`);
    }
}

const myCar = new Vehicle('Toyota', 'Camry', 2020);
myCar.displayInfo(); // Output: Vehicle Info: 2020 Toyota Camry
```

### 2. Inheritance

Inheritance allows a class to inherit properties and methods from another class, enabling code reuse and establishing a parent-child relationship.

#### Example: Inheriting from a Parent Class
```javascript
class Car extends Vehicle {
    constructor(make, model, year, doors) {
        super(make, model, year); // Call the parent constructor
        this.doors = doors; // Additional property specific to Car
    }

    displayInfo() {
        super.displayInfo(); // Call the parent method
        console.log(`Doors: ${this.doors}`);
    }
}

const mySedan = new Car('Honda', 'Accord', 2021, 4);
mySedan.displayInfo(); 
// Output: 
// Vehicle Info: 2021 Honda Accord
// Doors: 4
```

### 3. Encapsulation with Private Fields

Encapsulation helps protect the internal state of an object. In modern JavaScript, you can use private fields to restrict access to certain properties.

#### Example: Encapsulation with Private Fields
```javascript
class BankAccount {
    #balance; // Private field

    constructor(initialBalance) {
        this.#balance = initialBalance;
    }

    deposit(amount) {
        if (amount > 0) {
            this.#balance += amount;
            console.log(`Deposited: $${amount}`);
        } else {
            console.log('Deposit amount must be positive.');
        }
    }

    withdraw(amount) {
        if (amount > this.#balance) {
            console.log('Insufficient funds.');
        } else {
            this.#balance -= amount;
            console.log(`Withdrew: $${amount}`);
        }
    }

    getBalance() {
        return this.#balance;
    }
}

const account = new BankAccount(100);
account.deposit(50); // Output: Deposited: $50
account.withdraw(30); // Output: Withdrew: $30
console.log(`Current Balance: $${account.getBalance()}`); // Output: Current Balance: $120
```

### 4. Polymorphism

Polymorphism allows subclasses to provide specific implementations of methods that are defined in their parent class.

#### Example: Polymorphism in Action
```javascript
class Animal {
    speak() {
        console.log('Animal makes a sound');
    }
}

class Dog extends Animal {
    speak() {
        console.log('Dog barks');
    }
}

class Cat extends Animal {
    speak() {
        console.log('Cat meows');
    }
}

const animals = [new Dog(), new Cat()];

animals.forEach(animal => {
    animal.speak(); // Output: Dog barks \n Cat meows
});
```

### 5. Using `super` in Inheritance

The `super` keyword allows you to call functions on an object's parent class, particularly useful for calling the constructor and methods of the parent class.

#### Example: Using `super` to Access Parent Methods
```javascript
class Shape {
    constructor(color) {
        this.color = color;
    }

    describe() {
        console.log(`This shape is ${this.color}.`);
    }
}

class Circle extends Shape {
    constructor(color, radius) {
        super(color); // Call the parent constructor
        this.radius = radius; // Additional property specific to Circle
    }

    describe() {
        super.describe(); // Call the parent method
        console.log(`It has a radius of ${this.radius}.`);
    }
}

const circle = new Circle('red', 5);
circle.describe(); 
// Output: 
// This shape is red.
// It has a radius of 5.
```

### 6. Abstract Classes and Methods

JavaScript does not have built-in support for abstract classes, but you can simulate them by throwing errors in methods that should be overridden.

#### Example: Simulating Abstract Classes
```javascript
class Shape {
    constructor() {
        if (new.target === Shape) {
            throw new Error('Cannot instantiate abstract class Shape directly.');
        }
    }

    area() {
        throw new Error('Method "area()" must be implemented.');
    }
}

class Rectangle extends Shape {
    constructor(width, height) {
        super();
        this.width = width;
        this.height = height;
    }

    area() {
        return this.width * this.height;
    }
}

const rect = new Rectangle(10, 5);
console.log(`Area of Rectangle: ${rect.area()}`); // Output: Area of Rectangle: 50

// const shape = new Shape(); // This would throw an error
```

### Conclusion

These examples demonstrate how to effectively use object-oriented programming concepts in JavaScript, including:

- **Classes**: Define blueprints for creating objects with properties and methods.
- **Inheritance**: Create subclasses that inherit from parent classes, allowing for code reuse.
- **Encapsulation**: Protect internal state using private fields, ensuring that data is accessed only through methods.
- **Polymorphism**: Override methods in subclasses to provide specific implementations.
- **Using `super`**: Access parent class methods and constructors, facilitating inheritance.

Understanding these concepts will help you design more organized and maintainable code in JavaScript, especially for complex applications. By leveraging OOP principles, you can create reusable components and improve the overall structure of your code.

Certainly! Let's dive deeper into the concepts of Object-Oriented Programming (OOP) in JavaScript with more comprehensive examples that illustrate classes, inheritance, encapsulation, polymorphism, and the use of the `super` keyword.

### 1. Classes and Constructors

Classes are the foundation of OOP in JavaScript. They can have constructors to initialize properties and methods to define behavior.

#### Example: A Simple Class with Constructor
```javascript
class Vehicle {
    constructor(make, model, year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    displayInfo() {
        console.log(`Vehicle Info: ${this.year} ${this.make} ${this.model}`);
    }
}

const myCar = new Vehicle('Toyota', 'Camry', 2020);
myCar.displayInfo(); // Output: Vehicle Info: 2020 Toyota Camry
```

### 2. Inheritance

Inheritance allows a class to inherit properties and methods from another class, enabling code reuse and establishing a parent-child relationship.

#### Example: Inheriting from a Parent Class
```javascript
class Car extends Vehicle {
    constructor(make, model, year, doors) {
        super(make, model, year); // Call the parent constructor
        this.doors = doors; // Additional property specific to Car
    }

    displayInfo() {
        super.displayInfo(); // Call the parent method
        console.log(`Doors: ${this.doors}`);
    }
}

const mySedan = new Car('Honda', 'Accord', 2021, 4);
mySedan.displayInfo(); 
// Output: 
// Vehicle Info: 2021 Honda Accord
// Doors: 4
```

### 3. Encapsulation with Private Fields

Encapsulation helps protect the internal state of an object. In modern JavaScript, you can use private fields to restrict access to certain properties.

#### Example: Encapsulation with Private Fields
```javascript
class BankAccount {
    #balance; // Private field

    constructor(initialBalance) {
        this.#balance = initialBalance;
    }

    deposit(amount) {
        if (amount > 0) {
            this.#balance += amount;
            console.log(`Deposited: $${amount}`);
        } else {
            console.log('Deposit amount must be positive.');
        }
    }

    withdraw(amount) {
        if (amount > this.#balance) {
            console.log('Insufficient funds.');
        } else {
            this.#balance -= amount;
            console.log(`Withdrew: $${amount}`);
        }
    }

    getBalance() {
        return this.#balance;
    }
}

const account = new BankAccount(100);
account.deposit(50); // Output: Deposited: $50
account.withdraw(30); // Output: Withdrew: $30
console.log(`Current Balance: $${account.getBalance()}`); // Output: Current Balance: $120
```

### 4. Polymorphism

Polymorphism allows subclasses to provide specific implementations of methods that are defined in their parent class.

#### Example: Polymorphism in Action
```javascript
class Animal {
    speak() {
        console.log('Animal makes a sound');
    }
}

class Dog extends Animal {
    speak() {
        console.log('Dog barks');
    }
}

class Cat extends Animal {
    speak() {
        console.log('Cat meows');
    }
}

const animals = [new Dog(), new Cat()];

animals.forEach(animal => {
    animal.speak(); // Output: Dog barks \n Cat meows
});
```

### 5. Using `super` in Inheritance

The `super` keyword allows you to call functions on an object's parent class, particularly useful for calling the constructor and methods of the parent class.

#### Example: Using `super` to Access Parent Methods
```javascript
class Shape {
    constructor(color) {
        this.color = color;
    }

    describe() {
        console.log(`This shape is ${this.color}.`);
    }
}

class Circle extends Shape {
    constructor(color, radius) {
        super(color); // Call the parent constructor
        this.radius = radius; // Additional property specific to Circle
    }

    describe() {
        super.describe(); // Call the parent method
        console.log(`It has a radius of ${this.radius}.`);
    }
}

const circle = new Circle('red', 5);
circle.describe(); 
// Output: 
// This shape is red.
// It has a radius of 5.
```

### 6. Abstract Classes and Methods

JavaScript does not have built-in support for abstract classes, but you can simulate them by throwing errors in methods that should be overridden.

#### Example: Simulating Abstract Classes
```javascript
class Shape {
    constructor() {
        if (new.target === Shape) {
            throw new Error('Cannot instantiate abstract class Shape directly.');
        }
    }

    area() {
        throw new Error('Method "area()" must be implemented.');
    }
}

class Rectangle extends Shape {
    constructor(width, height) {
        super();
        this.width = width;
        this.height = height;
    }

    area() {
        return this.width * this.height;
    }
}

const rect = new Rectangle(10, 5);
console.log(`Area of Rectangle: ${rect.area()}`); // Output: Area of Rectangle: 50

// const shape = new Shape(); // This would throw an error
```

### Conclusion

These examples demonstrate how to effectively use object-oriented programming concepts in JavaScript, including:

- **Classes**: Define blueprints for creating objects with properties and methods.
- **Inheritance**: Create subclasses that inherit from parent classes, allowing for code reuse.
- **Encapsulation**: Protect internal state using private fields, ensuring that data is accessed only through methods.
- **Polymorphism**: Override methods in subclasses to provide specific implementations.
- **Using `super`**: Access parent class methods and constructors, facilitating inheritance.

Understanding these concepts will help you design more organized and maintainable code in JavaScript, especially for complex applications. By leveraging OOP principles, you can create reusable components and improve the overall structure of your code.

Functional programming (FP) is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data. JavaScript, while primarily an object-oriented language, supports functional programming concepts, allowing developers to write cleaner, more modular, and more maintainable code. Below are key concepts of functional programming in JavaScript, along with examples to illustrate each concept.

### Key Concepts of Functional Programming

1. **First-Class Functions**
2. **Higher-Order Functions**
3. **Pure Functions**
4. **Immutability**
5. **Function Composition**
6. **Recursion**
7. **Closures**
8. **Map, Filter, and Reduce**

### 1. First-Class Functions

In JavaScript, functions are first-class citizens, meaning they can be treated like any other variable. You can assign functions to variables, pass them as arguments to other functions, and return them from functions.

#### Example
```javascript
function greet(name) {
    return `Hello, ${name}!`;
}

const sayHello = greet; // Assigning a function to a variable
console.log(sayHello('Alice')); // Output: Hello, Alice!
```

### 2. Higher-Order Functions

Higher-order functions are functions that take other functions as arguments or return functions as their results. This allows for powerful abstractions and code reuse.

#### Example
```javascript
function applyOperation(x, y, operation) {
    return operation(x, y);
}

const add = (a, b) => a + b;
const result = applyOperation(5, 3, add);
console.log(result); // Output: 8
```

### 3. Pure Functions

A pure function is a function that, given the same inputs, will always return the same output and has no side effects (it does not modify any external state).

#### Example
```javascript
function square(x) {
    return x * x; // Pure function
}

console.log(square(4)); // Output: 16
console.log(square(4)); // Output: 16 (same input, same output)
```

### 4. Immutability

Immutability means that once a data structure is created, it cannot be changed. Instead of modifying existing data, you create new data structures. This helps avoid side effects and makes your code easier to reason about.

#### Example
```javascript
const originalArray = [1, 2, 3];

// Creating a new array without mutating the original
const newArray = [...originalArray, 4];

console.log(originalArray); // Output: [1, 2, 3]
console.log(newArray); // Output: [1, 2, 3, 4]
```

### 5. Function Composition

Function composition is the process of combining two or more functions to produce a new function. This allows you to build complex operations from simpler ones.

#### Example
```javascript
const add = (x) => x + 1;
const double = (x) => x * 2;

// Composing functions
const addThenDouble = (x) => double(add(x));

console.log(addThenDouble(3)); // Output: 8 (3 + 1 = 4, then 4 * 2 = 8)
```

### 6. Recursion

Recursion is a technique where a function calls itself to solve a problem. It is often used as an alternative to iterative loops.

#### Example
```javascript
function factorial(n) {
    if (n === 0) {
        return 1; // Base case
    }
    return n * factorial(n - 1); // Recursive case
}

console.log(factorial(5)); // Output: 120
```

### 7. Closures

A closure is a function that retains access to its lexical scope, even when the function is executed outside that scope. Closures allow for data encapsulation and private variables.

#### Example
```javascript
function makeCounter() {
    let count = 0; // Private variable

    return function() {
        count += 1; // Accessing the private variable
        return count;
    };
}

const counter = makeCounter();
console.log(counter()); // Output: 1
console.log(counter()); // Output: 2
```

### 8. Map, Filter, and Reduce

These are higher-order functions that operate on arrays and are fundamental to functional programming in JavaScript:

- **Map**: Transforms each element in an array based on a provided function.
- **Filter**: Creates a new array with elements that pass a specified test.
- **Reduce**: Reduces an array to a single value based on a provided function.

#### Example
```javascript
const numbers = [1, 2, 3, 4, 5];

// Using map to square each number
const squares = numbers.map(num => num * num);
console.log(squares); // Output: [1, 4, 9, 16, 25]

// Using filter to get even numbers
const evens = numbers.filter(num => num % 2 === 0);
console.log(evens); // Output: [2, 4]

// Using reduce to sum the numbers
const sum = numbers.reduce((acc, num) => acc + num, 0);
console.log(sum); // Output: 15
```

### Conclusion

Functional programming in JavaScript encourages a declarative style of programming where you focus on what to solve rather than how to solve it. By utilizing first-class functions, higher-order functions, pure functions, immutability, and other functional programming concepts, you can create cleaner, more modular, and maintainable code. Understanding these concepts will help you write better JavaScript and leverage the full potential of the language.

Memory management and performance optimization are critical aspects of JavaScript development that help ensure that applications run efficiently and effectively, especially in environments like browsers where resources are limited. Below, we’ll explore key concepts related to memory management and techniques for optimizing performance in JavaScript applications.

## Memory Management in JavaScript

JavaScript uses automatic memory management, primarily through a process known as **garbage collection**. This means that developers do not need to manually allocate and deallocate memory; instead, the JavaScript engine automatically frees up memory that is no longer in use.

### Key Concepts of Memory Management

1. **Heap and Stack Memory**:
   - **Heap Memory**: Used for dynamic memory allocation where objects and functions are stored. It is managed by the garbage collector.
   - **Stack Memory**: Used for static memory allocation, which includes function execution contexts and primitive values. It follows a Last In First Out (LIFO) order.

2. **Garbage Collection**:
   - The JavaScript engine periodically checks for memory that is no longer reachable or referenced. When it finds such memory, it reclaims it, making it available for future allocations.
   - Common garbage collection algorithms include **Mark-and-Sweep** and **Reference Counting**.

3. **Memory Leaks**:
   - A memory leak occurs when memory that is no longer needed is not released. Common causes include:
     - Global variables that are not cleared.
     - Event listeners that are not removed.
     - Closures that maintain references to unused variables.

### Detecting Memory Leaks

To detect memory leaks, you can use browser developer tools to monitor memory usage over time. Look for increasing memory consumption and use the following techniques:
- **Heap Snapshots**: Capture and analyze the memory heap to identify objects that are still in memory but should have been garbage collected.
- **Performance Profiling**: Use profiling tools to monitor memory usage and identify potential leaks.

### Example of a Memory Leak
```javascript
let myArray = [];

function createLeak() {
    const largeObject = new Array(1000000).fill('*'); // Large object
    myArray.push(largeObject); // Reference held in myArray
}

// Call the function multiple times
setInterval(createLeak, 1000);
```
In this example, `myArray` continuously grows, holding references to large objects, leading to a memory leak.

## Performance Optimization in JavaScript

Optimizing performance in JavaScript involves writing efficient code and utilizing best practices to reduce execution time and resource usage. Here are some key techniques for performance optimization:

### 1. Minimize DOM Manipulation

Manipulating the DOM is often a performance bottleneck. To optimize:
- **Batch DOM Updates**: Instead of making multiple updates, batch them together to reduce reflows and repaints.
- **Use Document Fragments**: Create elements in memory and append them to the DOM in one operation.

#### Example
```javascript
const fragment = document.createDocumentFragment();
for (let i = 0; i < 1000; i++) {
    const div = document.createElement('div');
    div.textContent = `Item ${i}`;
    fragment.appendChild(div);
}
document.body.appendChild(fragment); // Append all at once
```

### 2. Use Efficient Algorithms and Data Structures

Choose appropriate algorithms and data structures based on the problem. For example:
- Use arrays for ordered collections and objects for key-value pairs.
- Use `Map` for frequent additions and removals of key-value pairs.

### 3. Debounce and Throttle Events

When handling events such as scrolling or resizing, use debouncing or throttling to limit the number of function calls.

#### Example of Debouncing
```javascript
function debounce(func, delay) {
    let timeout;
    return function(...args) {
        clearTimeout(timeout);
        timeout = setTimeout(() => func.apply(this, args), delay);
    };
}

window.addEventListener('resize', debounce(() => {
    console.log('Window resized!');
}, 200));
```

### 4. Optimize Loops

Loops can be optimized by:
- Caching the length of the array when using a `for` loop.
- Using `forEach`, `map`, or other array methods for better readability and potential optimizations by the engine.

#### Example
```javascript
const arr = [1, 2, 3, 4, 5];
const length = arr.length;

for (let i = 0; i < length; i++) {
    console.log(arr[i]);
}
```

### 5. Use Web Workers for Heavy Computation

Web Workers allow you to run scripts in background threads, freeing up the main thread and keeping the UI responsive. Use them for CPU-intensive tasks.

#### Example
```javascript
// worker.js
self.onmessage = function(event) {
    const result = heavyComputation(event.data);
    self.postMessage(result);
};

// main.js
const worker = new Worker('worker.js');
worker.onmessage = function(event) {
    console.log('Result from worker:', event.data);
};
worker.postMessage(data);
```

### 6. Minimize Global Variables

Global variables can lead to conflicts and increased memory usage. Use local variables whenever possible and encapsulate code within functions or modules.

### 7. Use Lazy Loading

For large applications, consider lazy loading modules or components to improve initial load times. This can be done using dynamic imports.

#### Example
```javascript
button.addEventListener('click', async () => {
    const module = await import('./module.js');
    module.doSomething();
});
```

### 8. Optimize JSON Operations

When working with JSON, consider using `JSON.stringify()` and `JSON.parse()` efficiently. Avoid unnecessary conversions and optimize the structure of the data when possible.


Certainly! Let’s dive deeper into memory management and performance optimization in JavaScript with more detailed explanations, examples, and best practices.

## Memory Management in JavaScript

### Understanding Memory Allocation

JavaScript uses two types of memory allocation:

1. **Stack Memory**: 
   - Used for static memory allocation.
   - Stores primitive values (e.g., numbers, strings, booleans) and function call contexts.
   - Follows a Last In First Out (LIFO) structure, meaning that the last function called is the first to return.

2. **Heap Memory**: 
   - Used for dynamic memory allocation.
   - Stores objects, arrays, and functions.
   - Memory in the heap is managed by the garbage collector, which periodically checks for unreachable objects.

### Garbage Collection

Garbage collection is the process by which JavaScript automatically frees up memory that is no longer in use. The most common algorithm used is **Mark-and-Sweep**.

1. **Mark Phase**: The garbage collector marks all reachable objects starting from root references (global variables, active function calls).
2. **Sweep Phase**: It then sweeps through the heap and collects all unmarked objects, freeing their memory.

#### Example of Garbage Collection
```javascript
function createObject() {
    const obj = { name: 'Alice' };
    return obj;
}

const myObject = createObject();
// After this function execution, myObject is still reachable,
// so it will not be collected by the garbage collector.
```

### Memory Leaks

A memory leak occurs when memory that is no longer needed is not released, leading to increased memory usage over time. Common causes include:

- **Global Variables**: Variables that are not properly scoped can remain in memory.
- **Event Listeners**: If event listeners are not removed, they can keep references to DOM elements, preventing garbage collection.
- **Closures**: Closures can inadvertently capture variables that are no longer needed.

#### Example of a Memory Leak
```javascript
let myArray = [];

function createLeak() {
    const largeObject = new Array(1000000).fill('*'); // Large object
    myArray.push(largeObject); // Reference held in myArray
}

// Call the function repeatedly
setInterval(createLeak, 1000);
```
In this example, `myArray` continues to grow, holding references to large objects, leading to a memory leak.

### Detecting Memory Leaks

To detect memory leaks, use the following techniques:

1. **Browser Developer Tools**: Most browsers have built-in tools for monitoring memory usage. Use the "Memory" tab to take heap snapshots and analyze memory allocation.
2. **Performance Profiling**: Monitor memory usage over time to identify trends and potential leaks.

## Performance Optimization in JavaScript

### 1. Minimize DOM Manipulation

Manipulating the DOM is one of the most expensive operations in web development. To optimize DOM interactions:

- **Batch DOM Updates**: Instead of making multiple updates, batch them together to minimize reflows and repaints.
  
#### Example of Batching DOM Updates
```javascript
const list = document.createElement('ul');
const fragment = document.createDocumentFragment();

for (let i = 0; i < 1000; i++) {
    const listItem = document.createElement('li');
    listItem.textContent = `Item ${i}`;
    fragment.appendChild(listItem);
}

list.appendChild(fragment); // Append all at once
document.body.appendChild(list);
```

### 2. Use Efficient Algorithms and Data Structures

Choosing the right algorithms and data structures can significantly impact performance.

- **Arrays vs. Objects**: Use arrays for ordered collections and objects for key-value pairs.
- **Use `Map` for Frequent Additions/Removals**: Maps provide better performance for frequent additions and deletions compared to plain objects.

#### Example of Using `Map`
```javascript
const map = new Map();
map.set('key1', 'value1');
map.set('key2', 'value2');
console.log(map.get('key1')); // Output: value1
```

### 3. Debounce and Throttle Events

Debouncing and throttling are techniques used to limit the rate at which a function is executed in response to events.

- **Debouncing**: Ensures that a function is only called after a specified period of inactivity.
- **Throttling**: Ensures that a function is called at most once in a specified time period.

#### Example of Debouncing
```javascript
function debounce(func, delay) {
    let timeout;
    return function(...args) {
        clearTimeout(timeout);
        timeout = setTimeout(() => func.apply(this, args), delay);
    };
}

window.addEventListener('resize', debounce(() => {
    console.log('Window resized!');
}, 200));
```

### 4. Optimize Loops

Loops can be optimized by:

- **Caching the Length**: When iterating over arrays, cache the length to avoid recalculating it on each iteration.
- **Using `for...of` or `forEach`**: These methods can be more readable and may have optimizations.

#### Example of Optimizing a Loop
```javascript
const arr = [1, 2, 3, 4, 5];
const length = arr.length;

for (let i = 0; i < length; i++) {
    console.log(arr[i]);
}
```

### 5. Use Web Workers for Heavy Computation

Web Workers allow you to run scripts in background threads, freeing up the main thread for UI updates and user interactions. This is especially useful for CPU-intensive tasks.

#### Example of Using Web Workers
```javascript
// worker.js
self.onmessage = function(event) {
    const result = heavyComputation(event.data);
    self.postMessage(result);
};

// main.js
const worker = new Worker('worker.js');
worker.onmessage = function(event) {
    console.log('Result from worker:', event.data);
};
worker.postMessage(data);
```

### 6. Minimize Global Variables

Global variables can lead to conflicts and increased memory usage. Use local variables whenever possible and encapsulate code within functions or modules.

#### Example of Avoiding Globals
```javascript
(function() {
    let localVar = 'I am local'; // Local variable
    console.log(localVar);
})();
// console.log(localVar); // ReferenceError: localVar is not defined
```

### 7. Use Lazy Loading

For large applications, consider lazy loading modules or components to improve initial load times. This can be done using dynamic imports.

#### Example of Lazy Loading
```javascript
const button = document.getElementById('loadButton');
button.addEventListener('click', async () => {
    const module = await import('./module.js');
    module.doSomething();
});
```

### 8. Optimize JSON Operations

When working with JSON, consider using `JSON.stringify()` and `JSON.parse()` efficiently. Avoid unnecessary conversions and optimize the structure of the data when possible.

#### Example of Efficient JSON Handling
```javascript
const obj = {
    name: 'Alice',
    age: 30,
    password: 'secret'
};

// Custom replacer to exclude sensitive data
const jsonString = JSON.stringify(obj, (key, value) => {
    if (key === 'password') {
        return undefined; // Exclude the password field
    }
    return value;
});

console.log(jsonString); // Output: {"name":"Alice","age":30}
```

### 9. Use Performance APIs

JavaScript provides various APIs to measure performance, such as the `Performance` interface. Use these APIs to gather metrics and identify bottlenecks in your code.

#### Example of Using Performance API
```javascript
performance.mark('start');

// Code block to measure
for (let i = 0; i < 1000000; i++) {
    // Some computation
}

performance.mark('end');
performance.measure('My Measurement', 'start', 'end');

const measures = performance.getEntriesByName('My Measurement');
console.log(measures); // Output: Array of performance entries
```

Design patterns are reusable solutions to common problems in software design. They provide a template for solving issues in a way that is efficient, maintainable, and scalable. In JavaScript, several design patterns are commonly used, including creational, structural, and behavioral patterns. Below, we’ll cover key design patterns with explanations and code examples.

### 1. Creational Patterns

These patterns deal with object creation mechanisms, trying to create objects in a manner suitable to the situation.

#### a. Singleton Pattern

The Singleton pattern ensures that a class has only one instance and provides a global point of access to it.

**Example:**
```javascript
class Singleton {
    constructor() {
        if (Singleton.instance) {
            return Singleton.instance;
        }
        Singleton.instance = this;
    }

    getInstance() {
        return this;
    }
}

// Usage
const instance1 = new Singleton();
const instance2 = new Singleton();

console.log(instance1 === instance2); // Output: true
```

#### b. Factory Pattern

The Factory pattern defines an interface for creating an object but allows subclasses to alter the type of objects that will be created.

**Example:**
```javascript
class Car {
    constructor(model) {
        this.model = model;
    }
}

class Truck {
    constructor(model) {
        this.model = model;
    }
}

class VehicleFactory {
    static createVehicle(type, model) {
        switch (type) {
            case 'car':
                return new Car(model);
            case 'truck':
                return new Truck(model);
            default:
                throw new Error('Vehicle type not supported');
        }
    }
}

// Usage
const car = VehicleFactory.createVehicle('car', 'Toyota');
const truck = VehicleFactory.createVehicle('truck', 'Ford');

console.log(car instanceof Car); // Output: true
console.log(truck instanceof Truck); // Output: true
```

#### c. Constructor Pattern

The Constructor pattern uses functions to create objects and is the most common way to create objects in JavaScript.

**Example:**
```javascript
function Person(name, age) {
    this.name = name;
    this.age = age;
}

const alice = new Person('Alice', 30);
console.log(alice.name); // Output: Alice
```

### 2. Structural Patterns

These patterns deal with object composition and help ensure that if one part of a system changes, the entire system doesn’t need to change.

#### a. Adapter Pattern

The Adapter pattern allows incompatible interfaces to work together. It acts as a bridge between two incompatible interfaces.

**Example:**
```javascript
class OldSystem {
    request() {
        return 'Request from the old system';
    }
}

class NewSystem {
    specificRequest() {
        return 'Request from the new system';
    }
}

class Adapter {
    constructor(newSystem) {
        this.newSystem = newSystem;
    }

    request() {
        return this.newSystem.specificRequest();
    }
}

// Usage
const oldSystem = new OldSystem();
console.log(oldSystem.request()); // Output: Request from the old system

const newSystem = new NewSystem();
const adapter = new Adapter(newSystem);
console.log(adapter.request()); // Output: Request from the new system
```

#### b. Decorator Pattern

The Decorator pattern allows behavior to be added to individual objects, either statically or dynamically, without affecting the behavior of other objects from the same class.

**Example:**
```javascript
class Coffee {
    cost() {
        return 5;
    }
}

class MilkDecorator {
    constructor(coffee) {
        this.coffee = coffee;
    }

    cost() {
        return this.coffee.cost() + 1;
    }
}

class SugarDecorator {
    constructor(coffee) {
        this.coffee = coffee;
    }

    cost() {
        return this.coffee.cost() + 0.5;
    }
}

// Usage
let myCoffee = new Coffee();
console.log(myCoffee.cost()); // Output: 5

myCoffee = new MilkDecorator(myCoffee);
console.log(myCoffee.cost()); // Output: 6

myCoffee = new SugarDecorator(myCoffee);
console.log(myCoffee.cost()); // Output: 6.5
```

### 3. Behavioral Patterns

These patterns are concerned with algorithms and the assignment of responsibilities between objects.

#### a. Observer Pattern

The Observer pattern defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.

**Example:**
```javascript
class Subject {
    constructor() {
        this.observers = [];
    }

    subscribe(observer) {
        this.observers.push(observer);
    }

    unsubscribe(observer) {
        this.observers = this.observers.filter(obs => obs !== observer);
    }

    notify(data) {
        this.observers.forEach(observer => observer.update(data));
    }
}

class Observer {
    update(data) {
        console.log(`Observer received data: ${data}`);
    }
}

// Usage
const subject = new Subject();
const observer1 = new Observer();
const observer2 = new Observer();

subject.subscribe(observer1);
subject.subscribe(observer2);

subject.notify('Hello Observers!');
// Output:
// Observer received data: Hello Observers!
// Observer received data: Hello Observers!
```

#### b. Strategy Pattern

The Strategy pattern enables selecting an algorithm's behavior at runtime. It defines a family of algorithms, encapsulates each one, and makes them interchangeable.

**Example:**
```javascript
class Context {
    constructor(strategy) {
        this.strategy = strategy;
    }

    setStrategy(strategy) {
        this.strategy = strategy;
    }

    executeStrategy(data) {
        return this.strategy.execute(data);
    }
}

class StrategyA {
    execute(data) {
        return `Strategy A executed with ${data}`;
    }
}

class StrategyB {
    execute(data) {
        return `Strategy B executed with ${data}`;
    }
}

// Usage
const context = new Context(new StrategyA());
console.log(context.executeStrategy('data')); // Output: Strategy A executed with data

context.setStrategy(new StrategyB());
console.log(context.executeStrategy('data')); // Output: Strategy B executed with data
```

#### c. Command Pattern

The Command pattern encapsulates a request as an object, thereby allowing for parameterization of clients with queues, requests, and operations.

**Example:**
```javascript
class Command {
    execute() {}
}

class Light {
    turnOn() {
        console.log('Light is on');
    }

    turnOff() {
        console.log('Light is off');
    }
}

class LightOnCommand extends Command {
    constructor(light) {
        super();
        this.light = light;
    }

    execute() {
        this.light.turnOn();
    }
}

class LightOffCommand extends Command {
    constructor(light) {
        super();
        this.light = light;
    }

    execute() {
        this.light.turnOff();
    }
}

class RemoteControl {
    submit(command) {
        command.execute();
    }
}

// Usage
const light = new Light();
const lightOn = new LightOnCommand(light);
const lightOff = new LightOffCommand(light);

const remote = new RemoteControl();
remote.submit(lightOn); // Output: Light is on
remote.submit(lightOff); // Output: Light is off
```
JavaScript testing is an essential practice in software development that helps ensure code quality, functionality, and maintainability. Testing frameworks like **Jest** provide tools for writing and running tests efficiently. Test-Driven Development (TDD) is a methodology that emphasizes writing tests before writing the actual code. This overview will cover the key concepts of JavaScript testing, focusing on Jest and TDD, along with practical examples.

## JavaScript Testing Concepts

### Why Test?

1. **Catch Bugs Early**: Testing helps identify bugs and issues early in the development process.
2. **Refactor Safely**: With tests in place, you can refactor code with confidence that existing functionality will remain intact.
3. **Documentation**: Tests serve as documentation for how the code is expected to behave.
4. **Improved Design**: Writing tests can lead to better code design and architecture.

### Types of Testing

1. **Unit Testing**: Testing individual components or functions in isolation.
2. **Integration Testing**: Testing how different components work together.
3. **End-to-End Testing**: Testing the entire application flow from start to finish, simulating user interactions.

## Jest Testing Framework

Jest is a popular testing framework for JavaScript, particularly for testing React applications, but it can be used with any JavaScript codebase. It provides a simple and intuitive API, built-in test runners, and powerful features like mocking, spies, and snapshot testing.

### Getting Started with Jest

#### Installation

To get started with Jest, you can install it using npm or yarn:

```bash
npm install --save-dev jest
```

Or with yarn:

```bash
yarn add --dev jest
```

#### Configuration

You can configure Jest in your `package.json` file or by creating a `jest.config.js` file.

**Example `package.json` configuration:**
```json
{
  "scripts": {
    "test": "jest"
  }
}
```

### Writing Tests with Jest

#### Basic Test Structure

A typical Jest test consists of three main functions: `describe`, `it` (or `test`), and `expect`.

- **`describe()`**: Groups related tests.
- **`it()` or `test()`**: Defines a single test case.
- **`expect()`**: Contains the assertion to verify the expected outcome.

#### Example of a Simple Test

Let's say we have a function that adds two numbers:

```javascript
// math.js
function add(a, b) {
    return a + b;
}

module.exports = add;
```

Now, we can write a test for this function:

```javascript
// math.test.js
const add = require('./math');

describe('add function', () => {
    it('should return the sum of two numbers', () => {
        expect(add(1, 2)).toBe(3);
    });

    it('should return a negative number when adding a negative and a positive number', () => {
        expect(add(-1, 2)).toBe(1);
    });
});
```

### Running Tests

You can run your tests using the following command:
```bash
npm test
```

### Advanced Jest Features

#### Mocking Functions

Jest allows you to mock functions to isolate tests and avoid external dependencies.

**Example of Mocking a Function:**
```javascript
const fetchData = jest.fn(() => Promise.resolve('data'));

test('mocking a function', () => {
    return fetchData().then(data => {
        expect(data).toBe('data');
    });
});
```

#### Snapshot Testing

Snapshot testing allows you to capture the rendered output of a component and compare it to a stored snapshot. This is especially useful for testing React components.

**Example of Snapshot Testing:**
```javascript
import React from 'react';
import renderer from 'react-test-renderer';
import MyComponent from './MyComponent';

test('renders correctly', () => {
    const tree = renderer.create(<MyComponent />).toJSON();
    expect(tree).toMatchSnapshot();
});
```

### Test-Driven Development (TDD)

TDD is a software development methodology that emphasizes writing tests before writing the actual code. The process typically follows these steps:

1. **Write a Failing Test**: Start by writing a test for the new functionality you want to implement. This test should fail initially since the functionality is not yet implemented.
2. **Implement the Functionality**: Write the minimum code necessary to make the test pass.
3. **Refactor**: Clean up the code while ensuring that the tests still pass.
4. **Repeat**: Continue this cycle for each new feature or piece of functionality.

#### Example of TDD

Let’s say we want to create a function that multiplies two numbers.

1. **Write a Failing Test**:
```javascript
// math.test.js
describe('multiply function', () => {
    it('should return the product of two numbers', () => {
        expect(multiply(2, 3)).toBe(6); // This will fail because multiply is not defined yet
    });
});
```

2. **Implement the Functionality**:
```javascript
// math.js
function multiply(a, b) {
    return a * b;
}

module.exports = { add, multiply }; // Export both functions
```

3. **Run the Tests**:
```bash
npm test
```
If the multiply test passes, you can move on to the next feature.

4. **Refactor**: If necessary, improve the code structure while ensuring all tests pass.

### Conclusion

JavaScript testing, particularly with Jest, is a powerful way to ensure code quality and maintainability. Understanding the principles of TDD can lead to better-designed applications. By writing tests first, developers can clarify requirements, reduce bugs, and create a more reliable codebase.

Key takeaways:
- **Jest** is a popular testing framework that simplifies writing and running tests.
- **TDD** promotes writing tests before implementation, leading to better design and fewer bugs.
- Familiarity with mocking, snapshot testing, and assertions enhances your testing capabilities.



