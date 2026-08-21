# Python If/Elif/Else Syntax

In Python, conditional blocks use the keywords `if`{.python}, `elif`{.python} (short for "else if"), and `else`{.python}. The basic syntax is:

```python
if condition1:
    # code executed if condition1 is True
elif condition2:
    # code executed if condition2 is True (and condition1 was False)
elif condition3:
    # code executed if condition3 is True (and conditions 1 and 2 were False)
else:
    # code executed if none of the above conditions are True

# code after the block
```

Note that the condition is not inside parentheses, and that a colon follows the condition, or the word `else`{.python}

# Indentation

Python uses <strong>indentation</strong> (spaces or tabs at the beginning of lines) to define which code belongs inside the `if`{.python}/`elif`{.python}/`else`{.python} block. The code that should execute conditionally may span multiple lines and must be  indented the same amount. The first unindented line after the conditional block ends the block and will be executed when the block finishes executing.

```py-cell
x = 5

if x < 3:
    print("x is less than 3")
    print("x is small")
else:
    print("x is not less than 3")
    print("x is big")

print("This always prints")
```

# Example

Here's an example of an `if/elif/else`{.python} block that checks the value of a variable `a` and prints different messages based on its value:

```py-cell
a = 10

if a < 5:
    print("a is less than 5")
elif a < 15:
    print("a is between 5 and 15")
else:
    print("a is 15 or greater")
```

Feel free to modify the value of `a`{.python} in the code cell above to see how the output changes.