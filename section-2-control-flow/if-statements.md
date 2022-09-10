---
description: Make decisions and branch the flow with the if instruction
---

# If Statements

The **if statement** tests whether a condition is True and if so, executes a block of code that follows. The code block must be indented.

```python
a = 4
b = 5

if a < b:
    print('a is less than b')
```

The **elif statement** tests whether another condition is True if the first one is False.

```python
a = 6
b = 5

if a < b:
    print('a is less than b')
elif a < b:
    print('a is not less than b')
```

The **else statement** executes if all the preceding if statements are False.

```python
a = 5
b = 5

if a < b:
    print('a is less than b')
elif a < b:
    print('a is not less than b')
else:
    print('a must be equal to b')
```

### Multiple Conditional Statements

Multiple condition statements can be strung together with boolean operators _and_ and _or_. Parentheses can add more specific, and more complex, conditional testing.

```python
a = 2
b = 3

if a > 0 and a < 10:
    print('a is a positive number that\'s less than 10')
    
if (a > b or a > 0) and b * 4 > 10:
    print('success')
```

Make sure you are comfortable with multiple condition statements. There will likely be some on the PCEP exam.

### Nesting Conditional Statements

Condition statements can be nested within other condition statements. These are useful for when you want to test further condition statements after the first condition.

```python
age = 123

if age > 18: # is person an adult
    if age > 60:
        print('This is an old adult')
    elif age > 40:
        print('This is a middle-age adult')
    else:
        print('This is a young adult')
```
