---
Title: "bool()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Methods"
  - "Strings"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Converts a value to a Boolean `True` or `False` value.

Standard truth testing procedures are applied to values to determine their Boolean value. Statements are `True` if they do not meet one or more of these criteria:

- If a `False` boolean value is passed.
- If `None` is passed.
- If a quantitative zero is passed, such as `0` or `0.0`.
- If an empty sequence or mapping is passed, such as `()`, `[]`, or `{}`.
- If Objects of Classes having `bool()` or `len()` method, returning 0 or False are passed.

## Syntax

```py
bool(object)
```

## Example 1

Use `bool()` to return the boolean expression of the string `'True'`:

```codebyte/python
print(bool('True'))
```

## Example 2

Use `bool()` to return the boolean expression of the string `'False'`:

```codebyte/python
print(bool('False'))
```

## Example 3

Use `bool()` to return the boolean expression of the integer `0`:

```codebyte/python
print(bool(0))
```