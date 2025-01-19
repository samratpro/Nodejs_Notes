# Nodejs_Notes

### 01. How to start Node.js
- Installing Node.js: Node.js installation and setting up Node Package Manager (NPM).
- Understanding the Workspace: Structure of a Node.js project (node_modules, package.json, etc.).
- Basic Commands: `node`, `npm install`, `npm run`, `npm init`.

### 02. Data Types and common variable rules
- Variable Declaration: `var`, `let`, `const` and their scope differences.
- Zero Values: Behavior of uninitialized variables in JavaScript.
- Type Inference: Dynamic typing in JavaScript.
- Type Casting: Explicit and implicit type casting in JavaScript.

### 03. Statement
- If-Else: Multi-condition handling with logical operators.
- Switch: Handling multiple conditions efficiently.
- Ternary Operator: Shortening simple `if-else` logic.
- Error Handling with `try-catch`: Using `try-catch` blocks for synchronous error handling.

### 04. Loop
- Basic `for` Loop: Looping over numbers.
- `for...in` Loop: Iterating over object properties.
- `for...of` Loop: Iterating over arrays and iterable objects.
- `while` Loop: Basic while loop structure and usage.

### 05. Function
- Function Declarations and Expressions: Defining and calling functions.
- Anonymous Functions: Functions without names, often used in callbacks.
- Arrow Functions: Shorter function syntax.
- Callback Functions: Functions passed as arguments to other functions.
- Returning Values: Using `return` to output results from functions.

### 06. Common Built-in Methods
- Time and Sleep:
  - Formatting and parsing time using `Date`.
  - Using `setTimeout` and `setInterval` for delays.
- Type and Typecasting:
  - Using `typeof` to check types.
  - Converting values using `String()`, `Number()`, etc.
- Array Operations:
  - `push`, `pop`, `shift`, `unshift`, `concat`, `slice`, `splice`.
- Object Manipulation:
  - Accessing, adding, and deleting object properties.

### 07. Callback Methods
- Passing Functions as Arguments:
  - Defining and using callbacks in functions.
  - Using closures for callback behavior.
- Asynchronous Callbacks:
  - Using callbacks in asynchronous operations like `fs.readFile`.
- Promises:
  - Working with Promises for handling asynchronous code.
- Async/Await:
  - Handling asynchronous code with `async` and `await`.

### 08. String Manipulation
- String Operations:
  - Concatenation and splitting using `+`, `.concat()`, `.split()`.
  - String trimming using `.trim()`, `.padStart()`, `.padEnd()`.
- String Formatting:
  - Template literals and string interpolation.
  - Using `.replace()`, `.match()`, `.search()` methods.
- Regular Expressions:
  - Working with regular expressions using `RegExp`.
  - `test()`, `exec()`, and `replace()` methods for matching and replacing strings.
- String to other types: Converting to `String`, `Number`, and `Boolean`.

### 09. List, Array, Map, Object, Class (also project base usecase)
- List (Arrays):
  - Creating and manipulating arrays with `push`, `pop`, `shift`, `unshift`.
- Arrays: Using `forEach()`, `map()`, `filter()`, `reduce()` for data transformation.
- Map:
  - Creating and manipulating `Map` for key-value pairs.
- Objects:
  - Creating, updating, and deleting properties in JavaScript objects.
- Class:
  - Creating and using classes in JavaScript (ES6 class syntax).
  - Instantiating objects and working with methods.

### 10. Strong OOP in Node.js (following Java or Python's)
- Classes and Objects:
  - Understanding `class`, `constructor`, and `this`.
  - Inheritance and extending classes.
- Encapsulation:
  - Using private fields and methods.
- Polymorphism:
  - Overriding methods in child classes.
- Method and Getter/Setter Functions:
  - Using methods to manipulate data in an object.
- Design Patterns:
  - Implementing common design patterns like Singleton, Factory, and Observer.

### 11. Threading, Basic Request, Data Scraping etc
- Threading:
  - Using `worker_threads` for multi-threading.
  - Understanding concurrency and parallelism in Node.js.
- Requests:
  - Basic HTTP requests with `http` or third-party libraries like `axios` or `node-fetch`.
  - Parsing JSON responses.
- Data Scraping:
  - Using `cheerio` or `puppeteer` for scraping web pages.
  - Automating data scraping tasks.
  
### 12. Error Handling (Try Catch)
- Error Handling Idioms:
  - Using `try-catch` for synchronous error handling.
  - Creating custom error classes.
- Asynchronous Error Handling:
  - Using `.catch()` with promises.
  - Handling errors with `async` and `await`.
- Handling Uncaught Exceptions:
  - Using `process.on('uncaughtException')` to catch unexpected errors.

### 13. File Handling and IO
- File Operations:
  - Reading and writing files using `fs` module.
  - Asynchronous vs. synchronous file operations.
- Buffering:
  - Using `Buffer` to handle binary data.
- Stream Operations:
  - Working with streams (`readStream`, `writeStream`, `pipe()`).
- File Manipulation:
  - Renaming, deleting, and checking file existence using `fs` module.
