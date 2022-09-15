---
description: Practice makes permanent
---

# Question Set 3

### 1. What is the output of the following?

```python
x = int(1)
y = int(2.1292)
z = bool('Hello World')

print(x + y + z)
```

```
A. An error
B. 1
C. 4
D. '3.1292Hello World'
```

### 2. What is the output of the following?

```python
x = y = 3
y **= 2
y //= 2
print(y)
```

```
A. 3
B. 4
C. 1
D. 2
```

### 3. What is the output of the following?

```python
def add_list(nums):
    for n in nums:
        n += 1

nums = [1,2,3,4]
add_list(nums)
print(nums)
```

```
A. An error
B. [1,2,3,4]
C. [2,3,4,5]
D. []
```

### 4. Dictionaries can use duplicate keys if they are created correctly.

```
A. True
B. False
```

### 5. The following Python code produces an error message.

```python
a = 1,
b = a + (2,)
print(b)
```

```
A. True
B. False
```

### 6. What is the output of the following code?

```python
counter = 1
while True:
    if counter <= 10:
        break
    else:
        counter += 1
    print(counter)
        
```

```
A. Nothing
B. An infinite loop
C. A horizontal list of numbers 1 through 10
D. A vertical list of numbers 1 through 10
```

### 7. What is the output of the following code?

```python
nums = [1,2,3]
nums_copy = []
for n in nums:
    if n == nums[1]:
        continue
    nums_copy.append(n)
print(nums_copy)
```

```
A. [1,2,3]
B. [1,3]
C. [1]
D. [2]
```

### 8. What is the output of the following code?

<pre class="language-python"><code class="lang-python">def do_something(x, y=1):
    return x + y
    
y = 5
<strong>print(do_something(1))</strong></code></pre>

```
A. 6
B. 5
C. 2
D. 1
```

### 9. The format method allows you to change the font and color of Python strings.

```
A. True
B. False
```

### 10. Dictionaries written with curly brackets.

```
A. True
B. False
```

### Answers

1. C
2. B
3. B
4. B
5. B
6. A
7. D
8. C
9. B
10. A
