# Chapter #2:-

## Variables:-
A variable is a named storage location in memory used to hold data.

## #Creating Variables:-
- Python has no command for declaring a variable.
- A variable is created the moment you first assign a value to it.
- Assignment uses the = operator.

*PYTHON*
```Python
x = 18
y = “John”
```
 
## #Get Type:-
You can get the data type of a variable with the type() function.

*PYTHON*
```Python
print(type(x))  # Outputs: <class ‘int’>
print(type(y))  # Outputs: <class ‘str’>
```
 
## #Casting:-
Casting specifies or converts the data type of a variable using contractor function.

*PYTHON*
```Python
x = str(3)  # x will be ‘3’
y = int(3)  # y will be 3
z = float(3)  # z will be 3.0 
```
 
## #Single or Double Quotes:-
String variables can be declared either by using single or double quotes. They work exactly the same way.

*PYTHON*
```Python
name = “John”
name = ‘John’  # Both are identical
```
 
## #Case-Sensitive:-
Variable names are case-sensitive. a and A are two different variables.

*PYTHON*
```Python
a = 4
A = “Sally”  # A will not overwrite a.
```
 
## Data Types:-
In programming, data type is an important concept. Variables can store data of different types, and different types can do different things. Python has the following data types built-in by default.
- Text Type: str
- Numeric Types: int, float, complex
- Sequences Types: list, tuple, range
- Mapping Type: dict
- Set Types: set, frozenset
- Boolean Type: bool
- Binary Types: bytes, bytearray, memoryview
- None Type: NoneType

## #Getting the Data Type:-
Print the data type of any object by using the type() function.

*PYTHON*
```Python
x = 5
print(type(x))
```
 
## #Setting  the Data Type:-
The data type is set automatically when you assign a value to a variable.

| Example: | Data Type: |
| :------- | :--------- |
| `x = “Hello World”` | str |
| `x = 20` | int |
| `x = 20.5` | float |
| `x = 1j` | complex |
| `x = [ “apple”, ”banana”, “cherry” ]` | list |
| `x = ( “apple”, “banana”, “cherry” )` | tuple |
| `x = range(6)` | range |
| `x = { “name” : “John”, “age” : 36 }` | dict |
| `x = { “apple”, “banana”, “cherry” }` | set |
| `x = frozenset({ “apple”, “banana”, “cherry” })` | frozenset |
| `x = True` | bool |
| `x = b”Hello”` | bytes |
| `x = bytearray(5)` |bytearray |
| `x = memoryview(bytes(5))` |memoryview |
| `x = None` |NoneType |

## #Setting The Specific Data Type:-
If you want to specify the data type, you can use the respective constructor functions.

| Example: |
| :------- |
| `x = str( “Hello World” )` |
| `x = int( 20 )` |
| `x = float( 20.5 )` |
| `x = complex( 1j )` |
| `x = list(( “apple”, “banana”, “cherry” ))` |
| `x = tuple(( “apple”, “banana”, “cherry” ))` |
| `x = range(6)` |
| `x = dict( name = “John”, age = 36 )` |
| `x = set(( “apple”, “banana”, “cherry” ))` |
| `x = frozenset(( “apple”, “banana”, “cherry” ))` |
| `x = bool(5)` |
| `x = bytes(5)` |
| `x = bytearray(5)` |
| `x = memoryview(bytes(5))` |
 
## Variable Naming Rules:-
Python has strict rules and conversion for creating variable names. Legal names ensure code execution, while standard naming conventions improve code readability.

## #Legal Rules:-
- Start character: Must begin with a letter or an underscore ( _ ).
- Invalid starts: Cannot start with a number.
- Character limits: Can only contain alphanumeric characters and underscores ( A-z, 0-9, and _ ).
- Reserved Words: Cannot use Python keywords ( like if, class, import ) as variable names.
- Case Sensitivity: Names are case-sensitive ( age, Age, and AGE are three different variables).

*PYTHON*
```Python
# Legal names
myvar = “John”
my_var = “John”
_my_var = “John”
myVar = “John”
MYVAR = “John”
myvar2 = “John”

# Illegal names
2myvar = “John”  # starts with a number
my-var = “John”  # Contains a hyphen
my var = “John”  # Contains a space
```
 
## #Multi-Word Conventions:-
- Camel Case: Every word , except the first, starts with a capital letter ( myVariableName ).
- Pascal Case: Every word starts with a capital letter ( MyVariableName ).
- Snake Case: Words are separated by an underscore ( my_variable_name ). Note: This is the standard style conversion for Python variables.

## #All Python Operators:-
Operators are used to perform operations on variables and values. Python divides operators into seven distinct groups.

### 1. Arithmetic operators:
Used with numeric values to perform common mathematical operations.

| Operator | Name | Example |
| :------- | :--- | :------ |
| + | Addition | x+y |
| - | Subtraction | x-y |
| * | Multiplication | x*y |
| / | Division | x/y |
| % | Modulus ( Remainder ) | x%y |
| ** | Exponentiation | x**y |
| // | Floor Division ( Rounds down ) | x//y |
 
### 2. Assignment Operators:
Used to assign values to variables, often combining assignment with  an arithmetic operation.

| Operator | Equivalent to |
| :------- | :------------ |
| `=` | `x = 5` |
| `+=` | `x = x + 3` |
| `-=` | `x = x - 3` |
| `*=` | `x = x * 3` |
| `/=` | `x = x / 3` |
| `%=` | `x = x % 3` |
| `//=` | `x = x // 3` |
| `**=` | `x = x ** 3` |
| `&=` | `x = x & 3` |
| `\|=` | `x = x \| 3` |
| `^=` | `x = x ^ 3` |
| `>>=` | `x = x >> 3` |
| `<<=` | `x = x << 3` |
| `:=` | Walrus Operator ( assigns inside expressions ). |
 
### 3. Comparison Operators:
Used to compare two values returning a Boolean ( True or False ):

| Operator | Name | Example |
| :------- | :--- | :------ |
| == | Equal | `x == y` |
| != | Not equal | `x != y` |
| > | Greater than | `x > y` |
| < | Less than | `x < y` |
| >= | Greater than or Equal to | `x >= y` |
| <= | Less than or equal to | `x <= y` |

### 4. Logical Operators:
Used to combine conditional statements:
- and →  Returns True if both statements are true ( x < 5 and x <10 ).
- or → Returns True if at least one statement is true ( x < 5 or x < 4 ).
- not → Reverses the result, returning False if the result is True ( not(x<5)).

### 5. Identity Operators:
Used to compare objects, checking if they are actually the same object in memory, not just if they have the same value:
- is → Returns True if both variables point to the same object ( x is y ).
- is not → Returns True if both variables do not point to the same object ( x is not y ).

### 6. Membership Operators:
Used to test if a sequence ( like string, list, or tuple ) is present in an object.
- in → Returns True if a sequence with specified value is present ( x in y ).
- not in → Returns True if a sequence with the specified value is not present ( x not in y ).

### 7. Bitwise Operators: Used to compare binary numbers:

| Operator | Name | Description |
| :------- | :--- | :---------- |
| `&` | AND | Sets each bit to 1 if both bits are 1. |
| `\|` | OR | Sets each bit to 1 if one of two bits is 1. |
| `^` | XOR | Sets each bit to if only one of two bits is 1. |
| `~` | NOT | Inverts all the bits. |
| `<<` | Zero fill left shift | Shift left by pushing zeros in from the right. |
| `>>` | Signed right shift | Shift right by pushing copies of the leftmost bit in from the left. |




