# Unexpected NaN Result Due to Loose Typing in JavaScript

This repository demonstrates a common JavaScript bug stemming from loose typing and the implicit coercion of `null` to a number during arithmetic operations.  The `foo` function, when passed `null`, returns `NaN`, which propagates through the `bar` function and causes an unexpected result.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution involving explicit type checking or using a default value to prevent `NaN` errors.

## How to Reproduce

1. Clone the repository.
2. Run `node bug.js` in your terminal.