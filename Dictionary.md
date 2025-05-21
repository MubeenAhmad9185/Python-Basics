# Python-Basics  
# Python Dictionary Methods Example

This file contains an example of how various dictionary methods work in Python. Below is a breakdown of each method applied to a dictionary.

## Dictionary Methods and Their Usage

### 1. `clear()`  
- **Description:** Removes all items from the dictionary.  
- **Example:** After using `clear()` on `{'a': 1, 'b': 2}`, it becomes `{}`.

### 2. `copy()`  
- **Description:** Returns a shallow copy of the dictionary.  
- **Example:** After using `copy()` on `{'a': 1, 'b': 2}`, a new dictionary `{'a': 1, 'b': 2}` is created.

### 3. `get()`  
- **Description:** Returns the value for a key if it exists, otherwise returns `None` or a specified default.  
- **Example:** `get('a')` on `{'a': 1, 'b': 2}` returns `1`.

### 4. `items()`  
- **Description:** Returns a view object of key-value pairs.  
- **Example:** `items()` on `{'a': 1, 'b': 2}` returns `dict_items([('a', 1), ('b', 2)])`.

### 5. `keys()`  
- **Description:** Returns a view object of keys.  
- **Example:** `keys()` on `{'a': 1, 'b': 2}` returns `dict_keys(['a', 'b'])`.

### 6. `pop()`  
- **Description:** Removes the specified key and returns the corresponding value.  
- **Example:** `pop('a')` on `{'a': 1, 'b': 2}` returns `1`, and dictionary becomes `{'b': 2}`.

### 7. `popitem()`  
- **Description:** Removes and returns the last inserted key-value pair.  
- **Example:** `popitem()` on `{'a': 1, 'b': 2}` might return `('b', 2)`.

### 8. `setdefault()`  
- **Description:** Returns the value of a key if it exists; otherwise inserts the key with a default value.  
- **Example:** `setdefault('c', 3)` on `{'a': 1, 'b': 2}` adds `'c': 3`.

### 9. `update()`  
- **Description:** Updates the dictionary with elements from another dictionary or iterable of key-value pairs.  
- **Example:** `update({'c': 3})` on `{'a': 1, 'b': 2}` becomes `{'a': 1, 'b': 2, 'c': 3}`.

### 10. `values()`  
- **Description:** Returns a view object of all values.  
- **Example:** `values()` on `{'a': 1, 'b': 2}` returns `dict_values([1, 2])`.

## Example Code

```python
# Create a dictionary
my_dict = {'a': 1, 'b': 2}

# 1. clear()
my_dict.clear()

# Re-create dictionary
my_dict = {'a': 1, 'b': 2}

# 2. copy()
dict_copy = my_dict.copy()

# 3. get()
value_a = my_dict.get('a')

# 4. items()
items = my_dict.items()

# 5. keys()
keys = my_dict.keys()

# 6. pop()
removed = my_dict.pop('a')

# 7. popitem()
last_item = my_dict.popitem()

# Re-create again
my_dict = {'a': 1, 'b': 2}

# 8. setdefault()
my_dict.setdefault('c', 3)

# 9. update()
my_dict.update({'d': 4})

# 10. values()
vals = my_dict.values()

