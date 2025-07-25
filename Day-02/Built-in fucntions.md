# 📘 Python Built-in Functions for DevOps

A curated list of Python built-in functions that are commonly used in DevOps automation, scripting, and system tasks.

---

## 🧰 Essential Built-in Functions

| Function        | Description |
|-----------------|-------------|
| `print()`       | Displays output to the console. Useful for logging. |
| `input()`       | Takes user input (useful in interactive scripts). |
| `len()`         | Returns the number of items in an object. |
| `type()`        | Returns the type of a variable (great for debugging). |
| `str()`, `int()`, `float()` | Converts data types between string, integer, and float. |
| `bool()`        | Converts a value to Boolean (`True`/`False`). |
| `list()`, `dict()`, `set()`, `tuple()` | Creates collections or converts types. |
| `range()`       | Generates a sequence of numbers, commonly used in loops. |
| `enumerate()`   | Adds a counter to an iterable in loops. |
| `zip()`         | Combines multiple iterables element-wise. |
| `map()`         | Applies a function to each item in an iterable. |
| `filter()`      | Filters elements based on a condition. |
| `sorted()`      | Returns a sorted list from any iterable. |
| `reversed()`    | Returns reversed iterator of a sequence. |
| `sum()`         | Sums items in an iterable. |
| `min()`, `max()`| Returns smallest/largest item in an iterable. |
| `all()`, `any()`| Checks if all/any elements are `True`. |
| `abs()`         | Returns the absolute value of a number. |
| `round()`       | Rounds a number to nearest integer or decimals. |
| `isinstance()`  | Checks if an object is of a specific type. |
| `id()`          | Returns memory address of an object. |
| `help()`        | Displays documentation for objects. |
| `open()`        | Opens a file (essential for reading logs/configs). |
| `eval()`        | Executes a string as Python code (⚠️ use with caution). |
| `exec()`        | Executes dynamically generated Python code. |
| `globals()`     | Returns the global symbol table. |
| `locals()`      | Returns the local symbol table. |
| `dir()`         | Lists all attributes and methods of an object. |
| `vars()`        | Returns the `__dict__` attribute of objects. |
| `format()`      | Formats strings (used in logs/templates). |
| `chr()`, `ord()`| Converts between characters and ASCII values. |
| `bin()`, `oct()`, `hex()` | Converts numbers to binary, octal, or hex. |

---

## 💡 DevOps Use Case Examples

| Task | Recommended Functions |
|------|------------------------|
| **Read/write config/log files** | `open()`, `read()`, `write()`, `with` |
| **Automation scripting** | `range()`, `map()`, `filter()`, `zip()` |
| **String manipulation** | `format()`, `str()`, `split()`, `join()` |
| **Monitoring & reports** | `sum()`, `min()`, `max()`, `sorted()` |
| **Debugging** | `type()`, `print()`, `dir()`, `vars()` |
| **Validation** | `isinstance()`, `all()`, `any()` |

---

## 🚀 Bonus: Recommended Modules for DevOps

- `os` – OS-level commands (env vars, files, directories)
- `subprocess` – Execute shell commands
- `json`, `yaml` – Parse and write configuration files
- `shutil` – File system utilities
- `logging` – Standardized logs
- `pathlib` – Modern file path handling

---

> ✨ Use these tools to write clean, efficient, and powerful Python scripts for automation and infrastructure management!
