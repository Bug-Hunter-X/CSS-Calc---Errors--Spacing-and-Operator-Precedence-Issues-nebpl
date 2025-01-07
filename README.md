# CSS Calc() Errors: Spacing and Operator Precedence Issues

This repository demonstrates common errors encountered when using the `calc()` function in CSS.  The `bug.css` file contains examples of incorrect usage, leading to unexpected results.  The `bugSolution.css` file provides corrected versions.

**Issues:**

* **Spacing:** Missing spaces around operators can lead to incorrect calculations.
* **Operator Precedence:**  `calc()` follows standard mathematical operator precedence, but errors can arise from unintended order of operations.
* **Negative Values:**  Incorrect handling of negative values within `calc()` can result in incorrect layout or styling.

**Solutions:**

* Ensure proper spacing around all operators within the `calc()` function.
* Use parentheses to explicitly control the order of operations.
* Always wrap negative values in parentheses within the `calc()` function.

This example helps illustrate best practices and highlights the importance of careful syntax when using CSS's `calc()` feature.  It is crucial for producing consistent and predictable results.