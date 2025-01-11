# Types of Loops in Python

Loops in Python are constructs that allow you to repeat a block of code multiple times, making it easier to handle repetitive tasks efficiently. Python supports two main types of loops: for loops and while loops.

---

## 1. **For Loop**
The `for` loop iterates over a sequence (e.g., a list, tuple, string, or range) and executes a block of code for each item in the sequence.

### **Syntax**
```python
for item in sequence:
    # Code block
```
```python
students = ["Alice", "Bob", "Charlie"]
for student in students:
    print(f"Hello, {student}!")
```

### Using range():

```python

for i in range(5):
    print(i)
```
## 2. while Loop
The while loop repeats a block of code as long as the condition is True. It is typically used when the number of iterations is not known beforehand.

## Syntax:
```python

while condition:
```

```python
count = 0
while count < 5:
    print(count)
    count += 1  
```
## 3. break and continue Statements
**break:** Exits the loop immediately.
**continue:** Skips the current iteration and moves to the next.
Examples:
break in a loop:

```python
for i in range(5):
    if i == 3:
        break
    print(i)
```
### continue in a loop:

```python

for i in range(5):
    if i == 3:
        continue
    print(i)
```
# When to Use Which Loop?
Use a for loop when you know the number of iterations or are iterating over a sequence.
Use a while loop when the number of iterations depends on a condition.

## Why Are Constructs Important?
Constructs provide structure and clarity to code, making it easier to read, debug, and maintain. They also help programmers solve complex problems by breaking them into manageable parts.

In simple terms, a construct is like a tool or a framework that you use to build your programs. 

