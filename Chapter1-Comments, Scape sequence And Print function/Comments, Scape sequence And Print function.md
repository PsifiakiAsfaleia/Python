# Chapter 1:-

## Comments:-
Comments are non-executable text lines used to explain code, which the Python interpreter completely ignores during execution.

## #Types of Comments:-  
### 1. Single-Line Comments: 
- Start with a hash symbol ( # ).
- Everything after the # on that line is ignored.
- Placed on a new line above the code.

*PYTHON*
```Python
#calculate the area of a circle
Radius = 5
Area = 3.14*( radius**2)
```

### 2. Inline Comments:
- Placed on the same line as a code statement.
- Separated by at least two spaces from the code.
- Used for quick, same-line context.

*PYTHON*
```Python
Border-width = 20  #Measured in pi.
```

### 3. Multi-Line Comments:
Python has no dedicated syntax for multi-line comments.
- **Method A:** Insert a # at the beginning of each consecutive line.
- **Method B:** Use unassigned triple quotes ( “”” or ‘’’ ). Python ignores literal strings if they are not assigned to a variable.

*PYTHON*
```Python
#Method A: Standard way
#This script processes user logs
#and exports them to a CSV file.
 
“””
Method B: Multi-Line string way
Often used for longer explanations
Or temporarily hiding large code blocks.
“””
```
 
## Escape Sequence Characters:-
An escape sequence is a combination of characters starting with a backslash    (  \  ) that tells the interpreter to treat the subsequent text as a special instruction rather than a literal string.

## #Common Escape Sequences:-

 1. \n → Inserts a new line.

| Eg | Code | Output |
| :--- | :--- | :--- |
| -> | `print("Hello\nWorld")` | Hello<br>World |
 
2. \t → Inserts a horizontal tab.

| Eg | Code | Output |
| :--- | :--- | :--- |
| -> | `print(“A\tB”)` | A B |
 
3. \\ → Inserts a literal backslash.

| Eg | Code | Output |
| :--- | :--- | :--- |
| -> | `print(“C:\\Users”)` | C:\Users |

4. \’ → Inserts a single quote.

| Eg | Code | Output |
| :--- | :--- | :--- |
| -> | `print(“It\’s code”)` | It’s code |

5. \” → Inserts a double quote.

| Eg | Code | Output |
| :--- | :--- | :--- |
| -> | `print(“She said \”Hi\”.”)` | She said “Hi”. |

## Print() Function:-

```python
print( value1, value2, …, sep = ‘ ‘, end = ‘\n’, file = sys.stdout, flush = False )
```
 
## #Parameters & Its Default Value:-

| Parameters | Default |
| :--------- | :------ |
| *values -> Objects you want to print. | None |
| sep -> Specify how to separate the objects. | ‘ ‘ → ( a single space ) |
| end -> Specify what to print at the end. | ‘\n’ → ( a new line ) |
| file -> Redirects the output to an object like a file instead of screen. | sys.stdout |
| flush -> Forces Python to clear the output buffer and display the text immediately. | False |

Parameters 2 to 5 are optional.

 

