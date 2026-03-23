# Python Conditionals Explained

## Code Example

```python
score = 85  # example value

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Grade: F")

---

##Explanation

This example demonstrates how conditional statements work in Python.

if checks the first condition

elif (else if) checks additional conditions if previous ones are false

else runs when none of the conditions are true

The conditions are evaluated from top to bottom.

---

##How it works

Python evaluates each condition in order.

For score = 85:

- score >= 90 → False

- score >= 80 → True

Since the second condition is true, the program executes:
```
Grade: B
```
After that, the remaining conditions are ignored.

##Expected Output

```
Grade: B
```

##Common Mistakes

- Forgetting that conditions are checked in order.

- Using multiple if statements instead of elif.

- Not understanding that only the first true condition is executed.