# 📘 JavaScript Fundamentals – Interview Topics & Questions

## 1. Variable Declarations
- What is the difference between `var`, `let`, and `const`?
- What is hoisting and how does it affect `var`, `let`, and `const`?
- What are temporal dead zones?

## 2. Scope
- What are the different types of scopes in JavaScript (global, function, block)?
- How does lexical scoping work?
- What is a closure? Can you provide a real-world example?
- How do closures enable data privacy?

## 3. `this` Keyword
- How does `this` behave in:
  - A regular function?
  - An arrow function?
  - A method inside an object?
  - A constructor function?
  - Event listeners?
- How can you manually set `this` using `call`, `apply`, and `bind`?

## 4. Execution Context & Hoisting
- What happens during the creation and execution phases of the JS engine?
- What is the call stack?
- What gets hoisted? How are variables and functions hoisted differently?

## 5. Closures
- What is a closure and how is it created?
- Give examples where closures are practically used (e.g., private counters).
- What are common memory pitfalls with closures?

## 6. Data Types & Type Coercion
- What are primitive and reference types?
- What is the difference between `==` and `===`?
- What is coercion? Give examples of implicit and explicit coercion.
- What is `typeof null` and why?

## 7. Prototype & Inheritance
- How does prototypal inheritance work?
- What is the difference between a prototype and `__proto__`?
- How would you implement classical inheritance in ES5?
- What are `Object.create()` and `Object.setPrototypeOf()`?

## 8. Functions
- What is the difference between a function declaration and a function expression?
- What are arrow functions and how do they differ from regular functions?
- What is an IIFE (Immediately Invoked Function Expression)?
- What is the use of rest (`...args`) and spread (`...obj`) operators?

## 9. Asynchronous JavaScript
- What is the event loop?
- What are microtasks and macrotasks?
- What is the difference between `setTimeout`, `Promise`, and `async/await`?
- How do promises work under the hood?
- What happens when you `await` a non-promise?

## 10. ES6+ Features
- Destructuring and default parameters
- Template literals
- Modules: `import`/`export`, `default` vs named exports
- Object shorthand and computed properties
- Optional chaining and nullish coalescing
- Symbol and BigInt

## 11. Memory Management
- What is a memory leak? How can it occur in JS?
- What is garbage collection?
- How can closures contribute to memory leaks?

## 12. Error Handling
- What’s the difference between `throw` and `return Error()`?
- How does `try/catch/finally` work?
- How to handle async errors with `Promise.catch()` and `try/catch` with `async/await`?

## 13. Event Handling
- What is event bubbling and capturing?
- What is event delegation? Why is it useful?
- How do you prevent default behavior and stop propagation?

## 14. Miscellaneous & Tricky Concepts
- What is the difference between `Object.freeze()`, `Object.seal()`, and `Object.preventExtensions()`?
- What is the difference between shallow copy and deep copy?
- What are symbols and how are they used?
- How do iterables and generators work?

## 15. Common Tricky Questions
- What is the output of:
  ```js
  console.log(typeof NaN);      // ?
  console.log([] == false);     // ?
  console.log({} + []);         // ?
  console.log(!!'');            // ?
