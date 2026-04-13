# recap-js-again-it-s-final
# High level programming language 
# 📘 JavaScript Basics Guide

This repository contains a beginner-friendly guide to understanding the core concepts of JavaScript.

---

## 🚀 What is JavaScript?

JavaScript is a powerful programming language used to make web pages interactive. It runs directly in the browser.

```js
console.log("Hello World!");
```

---

## 📦 Variables

Variables are used to store data.

```js
let name = "Al Amin";   // can be changed
const age = 22;         // cannot be changed
var country = "BD";     // old (avoid using)
```

---

## 🔢 Data Types

### Primitive Types:

* String → `"Hello"`
* Number → `10`
* Boolean → `true / false`
* Undefined
* Null

### Non-Primitive Types:

* Object
* Array

```js
let user = { name: "Amin", age: 22 };
let numbers = [1, 2, 3, 4];
```

---

## ➕ Operators

```js
let a = 10;
let b = 5;

console.log(a + b); // 15
console.log(a - b); // 5
console.log(a * b); // 50
console.log(a / b); // 2
```

---

## 🔁 Condition (if-else)

```js
let age = 18;

if (age >= 18) {
  console.log("You are an adult");
} else {
  console.log("You are underage");
}
```

---

## 🔄 Loops

### For Loop

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

### While Loop

```js
let i = 0;
while (i < 5) {
  console.log(i);
  i++;
}
```

---

## ⚙️ Functions

```js
function greet(name) {
  return "Hello " + name;
}

console.log(greet("Amin"));
```

### Arrow Function

```js
const greet = (name) => {
  return "Hello " + name;
};
```

---

## 📚 Array Methods

```js
let nums = [1, 2, 3, 4];

nums.map(n => n * 2);      // [2,4,6,8]
nums.filter(n => n > 2);   // [3,4]
nums.find(n => n === 3);   // 3
```

---

## 🌐 DOM Manipulation (Basic)

```js
document.getElementById("demo").innerText = "Hello JavaScript!";
```

---

## 🎯 Summary

* JavaScript is essential for web development
* It makes websites interactive
* Practice is the key to mastering JavaScript

---

## 💡 Tips for Beginners

* Practice daily
* Build small projects
* Don't be afraid of errors
* Use Google & documentation

---

✨ Happy Coding!
