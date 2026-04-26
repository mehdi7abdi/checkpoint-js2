# JavaScript Functions – Exercices

A collection of JavaScript utility functions covering string manipulation, array operations, and mathematical calculations.

---

## 📁 Project Structure

```
CHECKPOINT-JS2/
└── functions.js   # All functions grouped by category
```

---

## 🔤 String Manipulation

### `reverseString(str)`

Reverses a given string.

```js
reverseString("bonjour"); // → "ruojnob"
```

### `countCharacters(str)`

Returns the number of characters in a string.

```js
countCharacters("hello"); // → 5
```

### `capitalizeWords(sentence)`

Capitalizes the first letter of each word in a sentence.

```js
capitalizeWords("salut le monde"); // → "Salut Le Monde"
```

---

## 📊 Array Functions

### `findMax(arr)`

Returns the maximum value in an array of numbers.

```js
findMax([3, 7, 1, 9, 4]); // → 9
```

### `findMin(arr)`

Returns the minimum value in an array of numbers.

```js
findMin([3, 7, 1, 9, 4]); // → 1
```

### `sumArray(arr)`

Calculates the sum of all elements in an array.

```js
sumArray([1, 2, 3, 4, 5]); // → 15
```

### `filterArray(arr, condition)`

Filters elements from an array based on a callback condition.

```js
filterArray([1, 2, 3, 4, 5, 6], (n) => n % 2 === 0); // → [2, 4, 6]
```

---

## 🔢 Mathematical Functions

### `factorial(n)`

Calculates the factorial of a number using recursion.

```js
factorial(5); // → 120  (5 × 4 × 3 × 2 × 1)
```

### `isPrime(n)`

Checks whether a number is prime. Returns `true` or `false`.

```js
isPrime(17); // → true
isPrime(10); // → false
```

### `fibonacci(terms)`

Generates the Fibonacci sequence up to a given number of terms.

```js
fibonacci(8); // → [0, 1, 1, 2, 3, 5, 8, 13]
```

---

## 🚀 How to Run

1. Clone or download the project
2. Open a terminal in the project folder

---

## 💡 Key Concepts Used

| Concept                  | Used In              |
| ------------------------ | -------------------- |
| `split / reverse / join` | `reverseString`      |
| `string.length`          | `countCharacters`    |
| `map`                    | `capitalizeWords`    |
| `Math.max / Math.min`    | `findMax`, `findMin` |
| `reduce`                 | `sumArray`           |
| `filter` + callback      | `filterArray`        |
| Recursion                | `factorial`          |
| `Math.sqrt` optimization | `isPrime`            |
| Loop + array push        | `fibonacci`          |

---

## 👨‍💻 Author

**Mehdi**  
Web Development Student
