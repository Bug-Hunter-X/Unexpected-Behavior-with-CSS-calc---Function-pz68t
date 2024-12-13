# Unexpected Behavior with CSS calc() Function

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The `calc()` function is powerful but requires careful attention to detail to avoid unexpected results.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides a corrected version.  The readme outlines the problem, solution, and best practices for using `calc()`.

**Problem:** Inconsistent unit usage, incorrect nesting, or lack of defined parent element width can cause unexpected results when using `calc()`. 

**Solution:** Ensure consistent units, avoid excessively nested calculations, verify parent element dimensions, and use developer tools to debug.