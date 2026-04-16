## Types of string


## Quick Summary

| Prefix | Meaning |
|--------|---------|
| f | formatted string |
| r | raw string |
| b | byte string |
| u | unicode (legacy) |
| fr | formatted + raw |
| br | byte + raw |

### f — Formatted string (f-string)

Used for embedding variables/expressions inside strings.

```python
name = "John"
print(f"Hello {name}")
```

### r — Raw string

Ignores escape sequences (\n, \t, etc.).

```python
print(r"C:\new_folder\test")
```

`Output: C:\new_folder\test`

### b — Byte string

Creates a bytes object (used in binary data).

```python
data = b"Hello"
print(data)
```

`Output: b'Hello'`

### u — Unicode string (mostly for Python 2 compatibility)

In Python 3, all strings are Unicode by default.
    
```python
text = u"Hello"
```

### fr / rf — Formatted raw string

Combines f and r.

```python
name = "John"
print(fr"Path: C:\Users\{name}")
```

### br / rb — Raw byte string

Combination of bytes + raw.

```python
data = br"\x41"
print(data)
```

`Output: b'A'`
