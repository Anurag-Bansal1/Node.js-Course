# **📘 Understanding Data Types in Node.js**

👋 **Hello again!**
Now that you have everything ready, it’s time to learn about the **building blocks** of programming: **data types**. Think of data types as different kinds of "stuff" you’ll use in your code—numbers, text, true/false values, and more. Node.js, being based on JavaScript, has some really flexible data types.

Before learning about Data Types, we should know about creating a variable. A variable, just like maths is a name which has it's value. For example,
```js
let x = 25;
```
Here we say that "let it that x is a variable whose value is 25" and optionally add a semicolon (;) at the end.
Let's continue!

---

### **🌟 What Are Data Types?**
In programming, **data types** define what kind of value you’re working with.
For example:
- Is it a **number** you can do math with?
- Is it **text** for a message?
- Is it a **true/false** condition for logic?

---

### 1. **Integer**
Numbers in JavaScript are super straightforward. Use them for calculations, counters, or anything math-y.
```js
let age = 17; // An integer
let price = 99.99; // A number with decimal values
```
These are just simply numbers written as it is, nothing complex!


### 2. **Strings**
Strings are **text values**. Wrap them in quotes (`'single'` or `"double"`) — JavaScript doesn’t mind!
```js
let name = "Anurag Bansal";
let welcome = 'Welcome to Node.js!';
```
Think of it like this, when we write something as it is, it's recognized as numbers but we are writing plain text and hence we enclose them in " " or ' ' not to mention that not all the symbols we can put in a string are allowed in Integer data type

### 3. **Boolean**
Booleans are **true** or **false**.
```js
let isHandsome = true;
let isBored = false;
```
Just like Binary, the base of a computer where the only 2 values are 0 and 1, or No and Yes, or false and true. We will learn in detail about it later.

### 4. **Undefined**
When a variable exists but hasn’t been given a value yet, it’s `undefined`.
```js
let futurePlan; // No value assigned yet
```

### 5. **Null**
`Null` is used to say, **"This variable has no value on purpose."**
```js
let score = null; // Intentionally empty
```

### 6. **Symbol**
A `Symbol` is a unique, one-of-a-kind value. It's a bit advanced but useful in certain cases.
```js
let uniqueID = Symbol('id');
```

### 7. **BigInt**
For **HUGE numbers** beyond JavaScript’s normal limits, nothing else.
```js
let bigNumber = 123456789012345678901234567890n;
```

### 8. **Objects**
Objects are dictionary of data in `key: value` pairs. Think of them like real-world objects (e.g., a car with properties like color and brand). Enclosed in `{}`
```js
let car = {
	brand: "Tesla",
	color: "red",
	speed: 250
};
```
Just like a dictionary which has a word and it's meaning, an object has a key and the value it refers to.

### 9. **Arrays**
Arrays are ordered lists of items. They can hold **anything** — numbers, strings, objects, or even other arrays! Enclosed in `[]`
```js
let fruits = ["apple", "banana", "cherry"];
let random = [42, "Node.js", true];
```

---

## **🛠️ Type Checking**
Use the `typeof` operator to check the type of any variable.
```js
let x = "Hello!";
console.log(typeof x); // Output: string
```

---

### **🎯 Summary**
Data types are like the ingredients of a recipe—you mix them to create something! We will more about each of them later in this course.

Next up: **Algebra.md**