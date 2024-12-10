# **🧮 Mastering Algebra in Node.js**

Algebra isn't just for math class—it’s the heart of programming too! In Node.js, algebraic operations help you manipulate numbers and solve equations. So, let’s break it down in a simple way.

---

## **🌟 What is Algebra in Programming?**

In programming, algebra is all about **using variables and operators** to perform calculations and solve problems.
Algebra makes all of this possible.

---

## **🔢 Operators in Node.js**

### **1. Arithmetic Operators**
The basic building blocks of math:
**Operator**   | **Symbol** | **Example** | **Result** | **Usage**
Addition       |   `+`      |  `5 + 3`    |   `8`      |  To add number
Subtraction    |   `-`      |  `10 - 4`   |   `6`      |  To subtract numbers
Multiplication |   `*`      |  `6 * 7`    |   `42`     |  To multiply numbers
Division       |   `/`      |  `20 / 5`   |   `4`      |  To divide numbers
Modulus        |   `%`      |  `10 % 3`   |   `1`      |  To find the remainder

Try it out:
```js
let a = 10, b = 3;
console.log(a + b); // 13
console.log(a % b); // 1
```

---

### **2. Assignment Operators**
These let you assign values to variables *and* perform operations in one step.
**Operator** | **Example** | **Equivalent To** | **Usage**
   `=`       |  `x = 5`    |       ---         |   To set the value
   `+=`      |  `x += 3`   |   `x = x + 3`     |   To add something to value
   `-=`      |  `x -= 2`   |   `x = x - 2`     |   To subtract something from value
   `*=`      |  `x *= 4`   |   `x = x * 4`     |   To multiply value by something
   `/=`      |  `x /= 2`   |   `x = x / 2`     |   To divide the value by something
   `%=`      |  `x %= 2`   |   `x = x % 2`     |   To set value as remainder of value and input

Try it out:
```js
let x = 10;
x += 5; // x is now 15
console.log(x);
```

---

### **3. Comparison Operators**
Used to compare values, gives back (returns) a boolean value!
**Operator**          | **Symbol** | **Example** | **Result**
Equal to              |   `==`     |  `5 == 5`   |  `true`
Not equal             |   `!=`     |  `5 != 3`   |  `true`
Greater than          |   `>`      |  `7 > 3`    |  `true`
Less than             |   `<`      |  `2 < 5`    |  `true`
Greater than or equal |   `>=`     |  `6 >= 6`   |  `true`
Less than or equal    |   `<=`     |  `4 <= 5`   |  `true`

---

## **🔄 Using Algebra in Node.js**
Let’s solve some fun problems:

### **1. Calculating Areas**
```js
let length = 5;
let width = 3;
let area = length * width;
console.log("Area of the rectangle:", area); // 15
```

### **2. Finding Discounts**
```js
let price = 100;
let discountRate = 0.2; // 20%
let discountedPrice = price - (price * discountRate);
console.log("Discounted Price:", discountedPrice); // 80
```

---

### **🎯 Summary**  
Algebra in Node.js is necessary when it comes to building logical and mathematical solutions, whether you’re calculating areas, discounts, or checking conditions.  

Next up: **If-else Statements.md**