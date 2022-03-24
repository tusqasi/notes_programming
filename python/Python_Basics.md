## Data types
Data is stored in memory, to make it easier for us to work with that data we make different types of data.
Basic variables in python
	- [x] int             (all integers -ve, +ve, zero)
	- [x] float         (fraction / decimal)
	- [x] string       (text)
	- [x] list            (list of stuff)
	- [ ] dict          (like a dictionary word and meaning)
	- [x] tuple        (list which we can't change)
	- [x] boolean   (true or false) 
## Variables
Variables are just names for data in memory
Variable names cannot be reserved words in python.
Like `print` is reserved in python and should not be used as a variable name
Some reserved names
	- Functions
		- `max`,`min`, `range`, `list` , `int`, `tuple` ...
	- Keywords
		- `def`, `if`, `class`...
Variable names cannot start with: 
	- numbers(`1name, 3apples, 6balls`) 
	- or special symbols(`(, [ , -, #, @`)
## Conditions and Loops
We can conditionally run code with conditionals
	- `if` \ `elif` \ `else`
And with loops we can run some logic in a loop 
	- `while`
	- `for`
	- `continue` \ `break`

## Common operations
Some operations on data 
meaning of these operators differ with data types

```py
# For numbers + , -, *, / will work as math
x = 69
y = 420
z = x + y
print(z)
---
>>> print(z)
489
```

---
```py
name_first = "Baldimir"
name_last  = "Getin"
print( name_first + name_last)
---
>>> print( name_first + name_last)
BaldimirGetin
```
- Assignment `=` 
	- LHS `=` RHS
	- Evaluate RHS and put it in LHS
- Arithmetic 
		- `+`, `-`, `*` `/`, `//` 
		-  `%` (modulus)
		-  `==`, `!=`, `!`, `>`, `<`

## Functions
Functions are a block/lines of code with a name.
When we call (run a function) a function it runs the lines of code for it
Some basics for functions
	- `def` keyword
	- arguments
	- return

## Classes
Basics of classes
- `class` keyword
- method vs function
- `__init__` method
- 