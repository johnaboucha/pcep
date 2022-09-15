---
description: Practice makes permanent
---

# Question Set 4

### 1. What is the output of the following code?

```python
counter = 0
name = 'Batman'
for n in name:
    if n == 't':
        break
    counter += 1
else:
    counter += 1
    
print(counter)
```

```
A. 4
B. 3
C. 2
D. 1
```

### 2. What does the range(3) function return?

```
A. A sequence of numbers, starting at 1
B. A sequence of numbers, starting at 0
C. An error
D. Nothing
```

### 3. What is the output of the following code?

```python
age = string(3)
num = 2
print(age * num)
```

```
A. 6
B. 33
C. 22
D. An error
```

### 4. What is the output of the following code?

```python
a = 2
print(a << 2)
```

```
A. 2
B. 4
C. 8
D. An error
```

### 5. What is the output of the following code?

```python
a = 4
b = 3
a -= b
print(not a)
```

```
A. 1
B. True
C. False
D. An error
```

### 6. The global keyword should always be used when creating variables inside of functions.

```
A. True
B. False
```

### 7. Attempting to assign a value to a keyword results in an error.

```
A. True
B. False
```

### 8. What is the output of the following code?

```python
city = 'Las Vegas'
state = 'Nevada'
print(city, state, end=' ')
```

```
A. Las Vegas Nevada
B. Las Vegas Nevada end
C. LasVegasNevada
D. An error
```

### 9. What is the output of the following code?

```python
cascadia = ('Oregon', 'California', 'Washington', 'British Columbia')
cascadia = sorted(cascadia)
print(cascadia)
```

```
A. ['Oregon', 'California', 'Washington', 'British Columbia']
B. ['Washington', 'Oregon', 'California', 'Brisith Columbia']
C. ['British Columbia', 'California', 'Oregon', 'Washington']
D. An error
```

### 10. What is the output of the following code?

```python
count = 0
for i in range(2):
    for j in range(2):
        count += 1
print(count)
```

```
A. 0
B. 4
C. 2
D. 8
```

### Answers

1. A
2. B
3. D
4. C
5. C
6. B
7. A
8. A
9. C
10. B
