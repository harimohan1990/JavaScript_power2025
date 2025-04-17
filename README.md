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


