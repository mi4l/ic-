# Statements
> In computer programming, a statement is a syntactic unit of an imperative programming language that expresses some action to be carried out. A program written in such a language is formed by a sequence of one or more statements. A statement may have internal components (e.g. expressions).

Basically, statements are our building blocks that let us create assignments, make assertions, return values, and introduce control flow among other things.  This document will describe each category as specified in JavaScript.

----

# Control Flow
Control flow is the order in which statements are executed.

## `return`
`return` specifies a value to be returned by a function.  A `return` statement immediately ceases execution of a function.

```js
const giveMeOne = () => {
  return 1;
};

const one = giveMeOne();

console.log(one); // 1
```

[`return`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return)

## `break`
Terminates the current loop, label, or switch and provides control to the next statement.

```js
const isTrue = true;

switch (isTrue) {
  case true:
    break;
  default:
    throw new Error("Oh no!");
}

console.log(isTrue); // true
```

[`break`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/break)

## `continue`
The `continue` statement terminates execution of the statements in the current iteration of the current or labeled loop, and continues execution of the loop with the next iteration.

```js
let text = '';

for (let i = 0; i < 10; i++) {
  if (i === 3) {
    continue;
  }
  text = text + i;
}

console.log(text); // "012456789"
```

The continue statement can include an optional label that allows the program to jump to the next iteration of a labeled loop statement instead of the innermost loop. In this case, the continue statement needs to be nested within this labeled statement.

A continue statement, with or without a following label, cannot be used at the top level of a script, module, function's body, or static initialization block, even when the function or class is further contained within a loop.

For information on labels, see here: [label: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label)

[`continue`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/continue)

## `throw`
Throws an exception as defined by a user.

```js
const isTrue = false;

switch (isTrue) {
  case true:
    break;
  default:
    throw new Error("Oh no!");
}

// Uncaught Error: Oh no!
```

[`throw`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)

## `if/else`
The if/else statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement in the optional else clause will be executed.

```js
function testNum(a) {
  let result;

  if (a > 0) {
    result = 'positive';
  } else {
    result = 'NOT positive';
  }

  return result;
}

console.log(testNum(-5)); // "NOT positive"
```

[`if`/`else`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

## `switch`
The switch statement evaluates an expression, matching the expression's value against a series of case clauses, and executes statements after the first case clause with a matching value, until a break statement is encountered. The default clause of a switch statement will be jumped to if no case matches the expression's value.

```js
const expr = 'Papayas';

switch (expr) {
  case 'Oranges':
    console.log('Oranges are $0.59 a pound.');
    break;
  case 'Mangoes':
  case 'Papayas':
    console.log('Mangoes and papayas are $2.79 a pound.');
    break;
  default:
    console.log(`Sorry, we are out of ${expr}.`);
}

// "Mangoes and papayas are $2.79 a pound."
```

[`switch`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)

## `try/catch`
The try...catch statement is comprised of a try block and either a catch block, a finally block, or both. The code in the try block is executed first, and if it throws an exception, the code in the catch block will be executed. The code in the finally block will always be executed before control flow exits the entire construct.

```js
try {
  nonExistentFunction();
} catch (error) {
  console.error(error);
}

// ReferenceError: nonExistentFunction is not defined
```

### `finally`
Statements that are executed before control flow exits the try...catch...finally construct. These statements execute regardless of whether an exception was thrown or caught.

The finally block contains statements to execute after the try block and catch block(s) execute, but before the statements following the try...catch...finally block. Control flow will always enter the finally block, which can proceed in one of the following ways:

Immediately before the try block finishes execution normally (and no exceptions were thrown);
Immediately before the catch block finishes execution normally;
Immediately before a control-flow statement (return, throw, break, continue) is executed in the try block or catch block.
If an exception is thrown from the try block, even when there's no catch block to handle the exception, the finally block still executes, in which case the exception is still thrown immediately after the finally block finishes executing.

The following example shows one use case for the finally block. The code opens a file and then executes statements that use the file; the finally block makes sure the file always closes after it is used even if an exception was thrown.

```js
openMyFile();

try {
  writeMyFile(theData); // tie up a resource
} finally {
  closeMyFile(); // always close the resource
}
```

[`try`/`catch`: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)

# Variable Declarations


# Functions

# Classes

# Iterations

# Miscellaneous


----
# Resources
- [Statements: MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)
- [Statement (computer science): Wikipedia](https://en.wikipedia.org/wiki/Statement_(computer_science))