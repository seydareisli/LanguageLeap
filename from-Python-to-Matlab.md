# From Python to Matlab: A Quickstart Guide

Welcome to the Matlab guide tailored for Python wizards. I originally created this tutorial for one of my earlier trainees who is a CS major with Python skills who needed to dive into a project on Matlab. 

## Key Differences Between Python and Matlab Syntax:

1. **For-Loops**: 
    - **Matlab**: The "in" from Python is "=" in Matlab. Write "for a = 1:3".
    - **Python**: "for a in range(3)".

2. **Indentations**: 
    - **Matlab**: Doesn't mandate the use of indentations or new line initiations. String your statements together using a ";".
    - **Python**: Indentation is mandatory.

3. **Indexing**: 
    - **Matlab**: Begin counting from 1. To fetch the first element of an array, query for element #1.
    - **Python**: Begin counting from 0. The first element is accessed with index #0.

4. **Matrix Elements**: 
    - **Matlab**: Access using parentheses: `x(1)`. For the first three elements, `x(1:3)` is the format.
    - **Python**: Access using square brackets: `x[0]`. With a library like NumPy, `x[0:3]` gives the first three elements.

5. **Logical Operators**: 
    - **Matlab**: For "not equal", use "~=".
    - **Python**: For "not equal", use "!=".

6. **Control Statements**: 
    - **Matlab**: No need for ":" after if/loop statements. Use ";" or nothing.
    - **Python**: A colon (":") is mandatory after if/loop statements.

7. **Else Statements**: 
    - **Matlab**: Uses "else if".
    - **Python**: Uses "elif".

8. **Matrix Initialization**: 
    - **Matlab**: Built-in functions like `zeros(10,5)` for a 10x5 2D-matrix and `ones(3,4,5)` for a 3D-matrix of size 3x4x5.
    - **Python (with NumPy)**: Functions like `numpy.zeros((10,5))` or `numpy.ones((3,4,5))`.

9. **Array Dimensions**: 
    - **Matlab**: Use `size(x)`.
    - **Python (with NumPy)**: Use `x.shape`.

10. **Handling Missing Data**: 
    - **Matlab**: Use NaN and Inf.
    - **Python (with NumPy)**: Use "nan" or "inf".

11. **String Concatenation**: 
    - **Matlab**: `['name ','last name']`.
    - **Python**: `'name ' + 'last name'`.

Also;

- **Parentheses `()`**: In Matlab, you will primarily use these for function calls and indexing. 
- **Square Brackets `[]`**: These are used for defining matrices and for concatenating arrays.
- **Curly Braces `{}`**: These define cell arrays, which can store data of varying types and sizes.

---


Stay tuned, as I will be integrating more details on variables, plotting, and other essential features soon!

