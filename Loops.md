# Python Loops Explained

## Code Example

```
this_list = ["apple", "banana", "cherry"]

for i in range(len(this_list)):
    print(f"Item at index {i} is {this_list[i]}")```

---

##Explanation

This example demonstrates how a for loop works in Python using a list.

- this_list is a list containing three items

- range(len(this_list)) generates numbers from 0 to the length of the list minus one

- i represents the current index

- this_list[i] accesses each element using its index

---

##How it works

For this list:

```

["apple", "banana", "cherry"]

```

The loop runs three times:

- i = 0 → apple

- i = 1 → banana

- i = 2 → cherry

---

##Expected Output

```
Item at index 0 is apple
Item at index 1 is banana
Item at index 2 is cherry
```

---

##Alternative Approach

In Python, it is more common to iterate directly over the items:

```
for item in this_list:
    print(item)
```

Or to get both index and value:

```
for i, item in enumerate(this_list):
    print(i, item)
```

---

##Common Mistakes

- Forgetting that list indexes start at 0

- Using incorrect index values

- Not understanding the difference between index and value