---
description: Practice makes permanent
---

# Question Set 5

### 1. What is the output of the following code?

```python
def my_function(a, b=2, c=3):
    return a + b + c
    
my_function(1, 2)
print(my_function(1, c=2))
```

```
A. An error
B. 3
C. 5
D. 6
```

### 2. What is the output of the following code?

```python
string1 = 'Hello, World!'
string2 = 'hello, worLD!'
print(string1 == string2.capitalize())
```

```
A. True
B. False
```

### 3. What is the output of the following code?

```python
nums = [4,2,5,3,1]
nums.sort(reverse=True)
print(nums)
```

```
A. [5,4,3,2,1]
B. [1,2,3,4,5]
C. []
D. An error
```

### 4. What is the output of the following code?

```python
equipment = 'gloves',
print(type(equipment))
```

```
A. <class 'list'>
B. <class 'tuple'>
C. <class 'str'>
D. An error
```

### 5. What is the output of the following code?

```python
nums = [x for x in range(5)]
print(nums)
```

```
A. [1,2,3,4,5]
B. [0,1,2,3,4]
C. [5]
D. (5)
```

### 6. What is the output of the following code?

```python
def plus_two(num):
    global x
    x = num + 2

plus_two(4)
print(x)
```

```
A. An error
B. 2
C. 4
D. 6
```

### 7. Which statement is incorrect?

```
A. 0x2A is a hexademical number
B. 0o12 is an octal number
C. bin() will convert a binary to a decimial number
D. 0b110 is a binary number
```

### 8. Who is the creator of Python?

```
A. Guido van Rossum
B. Monty Python
C. Hayao Miyazaki
D. Peter Gibbons
```

### 9. Which of the following is the extension for Python files?

```
A. .python
B. .pi
C. .py
D. .ppt
```

### 10. How many asterisks with the following code output?

```python
i = 1
while i <= 10:
    i += 3
    print('*')
    if i == 6:
        break
```

```
A. 1
B. 2
C. 3
D. 4
```

### Answers

1. C
2. B
3. A
4. B
5. B
6. D
7. C
8. A
9. C
10. D
