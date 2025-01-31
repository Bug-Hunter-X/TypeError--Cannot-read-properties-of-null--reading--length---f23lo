# JavaScript Bug: Handling Null and Undefined in Length Checks

This repository demonstrates a common JavaScript error: attempting to access the `length` property of a null or undefined value.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version.

**Bug:**
The original code fails to handle cases where the input `x` is null or undefined, leading to a `TypeError: Cannot read properties of null (reading 'length')`.

**Solution:**
The corrected code includes explicit checks for null and undefined values before accessing the `length` property.  This prevents the error and ensures the function behaves correctly in all scenarios.

**How to run:**
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run each file to observe the bug and the solution.