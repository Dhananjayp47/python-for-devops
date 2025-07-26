# 📌 Python Built-in Functions

Python comes with a set of **built-in functions** that are always available. These do not require any import and are globally accessible. They're useful for input/output, data conversion, math operations, and working with iterables.

| Function       | Description                                      | Example Usage              |
|----------------|--------------------------------------------------|----------------------------|
| `print()`      | Prints output to the console                    | `print("Hello")`          |
| `len()`        | Returns length of an object                     | `len([1, 2, 3])`           |
| `type()`       | Returns type of an object                       | `type("abc")`             |
| `int()`        | Converts value to integer                       | `int("42")`               |
| `str()`        | Converts value to string                        | `str(123)`                 |
| `input()`      | Takes user input as string                     | `input("Enter name: ")`   |
| `sum()`        | Sums elements of iterable                      | `sum([1, 2, 3])`           |
| `max()`        | Returns maximum element                        | `max([1, 4, 2])`           |
| `min()`        | Returns minimum element                        | `min([1, 4, 2])`           |
| `abs()`        | Absolute value                                 | `abs(-5)`                  |
| `round()`      | Rounds a number                                | `round(3.1415, 2)`         |
| `sorted()`     | Returns sorted list                            | `sorted([3, 1, 2])`        |
| `range()`      | Returns a range object                         | `range(5)`                 |
| `enumerate()`  | Returns index and value pair in iterable      | `enumerate(["a", "b"])`   |
| `zip()`        | Zips multiple iterables                        | `zip([1,2],["a","b"])`    |
| `dir()`        | Lists attributes of object                     | `dir(str)`                 |
| `help()`       | Provides help documentation                    | `help(str)`                |
| `open()`       | Opens a file                                   | `open("file.txt")`        |

---

# 📦 String Methods (`str`)

String methods are functions that operate on string objects. They're useful for formatting, searching, modifying, or analyzing text.

| Method         | Description                          | Example                      |
|----------------|--------------------------------------|------------------------------|
| `upper()`      | Converts to uppercase                | `"abc".upper()` → `"ABC"`    |
| `lower()`      | Converts to lowercase                | `"ABC".lower()` → `"abc"`    |
| `strip()`      | Removes leading/trailing whitespace | `" abc ".strip()` → `"abc"`  |
| `replace()`    | Replaces substring                  | `"abc".replace("a", "z")`   |
| `split()`      | Splits into list                    | `"a,b".split(",")`          |
| `join()`       | Joins elements with separator       | `"-".join(["a", "b"])`      |
| `find()`       | Finds index of substring            | `"abc".find("b")` → `1`      |
| `startswith()` | Checks if starts with substring     | `"abc".startswith("a")`      |
| `endswith()`   | Checks if ends with substring       | `"abc".endswith("c")`        |
| `isdigit()`    | Checks if all characters are digits | `"123".isdigit()` → `True`   |

---

# 📋 List Methods (`list`)

List methods allow you to modify or access list elements. Lists are mutable and support a variety of operations like adding, removing, and sorting.

| Method       | Description                            | Example                      |
|--------------|----------------------------------------|------------------------------|
| `append()`   | Adds element to end                    | `[1, 2].append(3)`           |
| `extend()`   | Adds elements from another iterable    | `[1, 2].extend([3, 4])`      |
| `insert()`   | Inserts element at index              | `[1, 2].insert(1, 100)`      |
| `remove()`   | Removes first match                   | `[1, 2, 3].remove(2)`        |
| `pop()`      | Removes and returns item at index     | `[1, 2, 3].pop()`            |
| `clear()`    | Removes all items                     | `[1, 2, 3].clear()`          |
| `sort()`     | Sorts the list in place               | `[3, 1, 2].sort()`           |
| `reverse()`  | Reverses the list                     | `[1, 2, 3].reverse()`        |
| `count()`    | Counts occurrences of element         | `[1, 2, 1].count(1)`         |
| `copy()`     | Returns a copy                        | `copy_list = lst.copy()`     |

---

# 📚 Dictionary Methods (`dict`)

Dictionaries store key-value pairs and are great for structured data. These methods help with accessing, updating, and iterating over keys and values.

| Method         | Description                            | Example                          |
|----------------|----------------------------------------|----------------------------------|
| `get()`        | Returns value for key or default       | `d.get("key", "default")`       |
| `keys()`       | Returns all keys                      | `d.keys()`                       |
| `values()`     | Returns all values                    | `d.values()`                     |
| `items()`      | Returns key-value pairs               | `d.items()`                      |
| `update()`     | Updates with another dict             | `d.update({"k": 1})`             |
| `pop()`        | Removes specified key                 | `d.pop("key")`                  |
| `popitem()`    | Removes last inserted item            | `d.popitem()`                    |
| `clear()`      | Clears all items                      | `d.clear()`                      |
| `setdefault()` | Returns key value, sets if missing    | `d.setdefault("k", 0)`          |
| `copy()`       | Returns a copy                        | `new_d = d.copy()`               |

---

# 🔢 Set Methods (`set`)

Sets are collections of unique elements. These methods help with adding, removing, and performing operations like union and intersection.

| Method         | Description                            | Example                          |
|----------------|----------------------------------------|----------------------------------|
| `add()`        | Adds an element                        | `s.add(5)`                       |
| `remove()`     | Removes item, KeyError if not present | `s.remove(5)`                    |
| `discard()`    | Removes item, does nothing if missing | `s.discard(5)`                   |
| `pop()`        | Removes and returns arbitrary item     | `s.pop()`                        |
| `clear()`      | Removes all elements                  | `s.clear()`                      |
| `union()`      | Returns union of sets                 | `s1.union(s2)`                   |
| `intersection()`| Common elements                      | `s1.intersection(s2)`            |
| `difference()` | Difference between sets               | `s1.difference(s2)`              |
| `update()`     | Updates set with elements from another| `s.update(s2)`                   |
