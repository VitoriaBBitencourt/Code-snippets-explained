# Python Classes Explained

## Code Example

```python
class Greeter:
    def __init__(self, greeting):
        self.greeting = greeting

    def greet(self, who):
        print(f"{self.greeting}, {who}!")```

---

## Explanation

This example shows how to define and use a simple class in Python.

- class Greeter: defines a new class called Greeter

- __init__ is a special method that runs when a new object is created

- greeting is a parameter passed during object creation

- self.greeting stores the value inside the object

The method greet:

- receives a parameter who

- prints a formatted message using the stored greeting

---

## How it works

1. Greeter("Hello") creates a new object

2. he __init__ method stores "Hello" in self.greeting

3. gr.greet("world") calls the method

4. The message is printed using both values

---

## Expected Output

```
Hello, world!
```
---

## Common Mistakes

- Forgetting to use self in methods

- Not understanding that __init__ runs automatically

- Trying to access greeting without self.

---