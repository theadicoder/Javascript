Here's the markdown documentation for your JavaScript examples and explanations:

```markdown
# JavaScript

This repository provides examples and basic understanding of JavaScript concepts.

---

## Hello World Example

A simple introduction to JavaScript's `console.log` for outputting text:

```javascript
console.log("Hello World");
console.log('Aditya Thakur');
console.log('I Love Apple I - Phone');
```

---

## Variables in JavaScript

### Examples:

```javascript
// String variable
let Naturalname = 'theadicoder';

// Integer variable
let age = 16;

// String variable (representing a price)
let price = '100 $';

// Null variable
let X = null;

// Undefined variable
let Y = undefined;

// Integer variable
let radius = 14;

// Boolean variable
let isFollow = true;

// Output variables
console.log(Naturalname, age, price, X, Y);
```

### Key Points:
1. **Dynamically Typed Language**: JavaScript allows changing variable values at runtime.
2. **Variable Naming Rules**:
   - Variables can't start with a number.
   - Variables can start with an underscore `_`, a letter, or a `$`.

### Example of Valid and Invalid Variables:
- ✅ Valid:
  ```javascript
  let _example = "Valid";
  let example123 = "Valid";
  let $example = "Valid";
  ```

- ❌ Invalid:
  ```javascript
  // Error: Variables can't start with a number
  let 1example = "Invalid";
  ```

---

## Variable Declaration

### `const`, `let`, and `var` in JavaScript:
- `const`: Immutable and cannot be re-assigned.
- `let`: Block-scoped and can be updated.
- `var`: Function-scoped (older way of declaring variables).

#### Example:
```javascript
// Using const
const userId = "hvfhsvfhshvf";

// Using let
let name = 'Ayush Thakur';
let age = 19;
let where_He_live = 'Delhi';
let totalPrice = 1000;

// Example of a variable re-declaration error:
var newage = 24; // Avoid using 'var', prefer 'let' or 'const'
```

---

## Summary

- JavaScript is a dynamically typed language.
- Follow proper naming conventions and avoid using invalid variable names.
- Use `const` for constants, `let` for variables that can change, and avoid `var` unless necessary.

---

**Explore more and enhance your JavaScript skills!**
``` 

This markdown provides a structured format for explaining JavaScript basics, variables, and examples, making it easy to read and understand for learners.
