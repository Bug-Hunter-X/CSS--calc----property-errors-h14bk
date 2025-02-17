# CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function.  The `bug.css` file contains examples of these errors, while `bugSolution.css` shows the corrected versions.

**Common Errors:**

1. **Undefined Parent Widths:**  `calc()` can produce unexpected behavior if the parent container doesn't have an explicit width.  This frequently happens with percentages.
2. **Unit Mismatches:** Combining different units (e.g., pixels and ems) within a single `calc()` expression can lead to inconsistent or unpredictable outcomes. 

Refer to the `bug.css` and `bugSolution.css` files for code examples illustrating these problems and their solutions.