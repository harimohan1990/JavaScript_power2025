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

   







