# Uncommon CSS `calc()` Errors and Debugging

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS, along with their solutions.

## Bugs:

* **Incorrect Unit Usage:** Missing units in `calc()` expressions.
* **Order of Operations:** Incorrect use of parentheses leading to unexpected results.
* **Nested `calc()` expressions:**  Deeply nested `calc()` expressions are difficult to read and debug.
* **Browser Inconsistencies:** Minor differences in how browsers handle `calc()` expressions.
* **Incompatible Units:** Attempting calculations using incompatible units (e.g., pixels and ems directly). 

## Solutions:

The `bugSolution.css` file shows the corrected CSS code and explains how to avoid these errors.  Make sure to use proper units, correctly manage order of operations with parentheses, and keep nested expressions simple.  Also, perform thorough cross-browser testing.