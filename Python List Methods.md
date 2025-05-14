# Python-Basics
# Python List Methods Example

This repository contains an example of how various list methods work in Python. Below is a breakdown of each method applied to a list.

## List Methods and Their Usage

### 1. `append()`
- **Description:** Adds an element to the end of the list.
- **Example:**
  After using `append(6)` on the list `[1, 2, 3, 4, 5]`, the list becomes `[1, 2, 3, 4, 5, 6]`.

### 2. `clear()`
- **Description:** Removes all items from the list.
- **Example:**  
  After using `clear()` on the list `[1, 2, 3, 4, 5]`, the list becomes `[]`.

### 3. `copy()`
- **Description:** Returns a shallow copy of the list.
- **Example:**  
  After using `copy()` on the list `[1, 2, 3, 4, 5]`, a new list `[1, 2, 3, 4, 5]` is created.

### 4. `count()`
- **Description:** Returns the number of times an element appears in the list.
- **Example:**  
  After using `count(3)` on the list `[1, 2, 3, 4, 5]`, the result is `1`, since the number `3` appears once.

### 5. `extend()`
- **Description:** Extends a list by appending elements from another iterable.
- **Example:**  
  After using `extend([6, 7])` on the list `[1, 2, 3, 4, 5]`, the list becomes `[1, 2, 3, 4, 5, 6, 7]`.

### 6. `index()`
- **Description:** Returns the index of the first occurrence of an element.
- **Example:**  
  After using `index(4)` on the list `[1, 2, 3, 4, 5]`, the result is `3`, as the number `4` is at index `3`.

### 7. `insert()`
- **Description:** Inserts an element at a specific position in the list.
- **Example:**  
  After using `insert(2, 10)` on the list `[1, 2, 3, 4, 5]`, the list becomes `[1, 2, 10, 3, 4, 5]`.

### 8. `pop()`
- **Description:** Removes and returns the item at the given position in the list.
- **Example:**  
  After using `pop(1)` on the list `[1, 2, 3, 4, 5]`, the list becomes `[1, 3, 4, 5]` and the returned item is `2`.

### 9. `remove()`
- **Description:** Removes the first occurrence of a specified element from the list.
- **Example:**  
  After using `remove(10)` on the list `[1, 2, 3, 4, 5, 10]`, the list becomes `[1, 2, 3, 4, 5]`.

### 10. `reverse()`
- **Description:** Reverses the elements of the list in place.
- **Example:**  
  After using `reverse()` on the list `[1, 2, 3, 4, 5]`, the list becomes `[5, 4, 3, 2, 1]`.

### 11. `sort()`
- **Description:** Sorts the elements of the list in place.
- **Example:**  
  After using `sort()` on the list `[5, 4, 3, 2, 1]`, the list becomes `[1, 2, 3, 4, 5]`.

## Example Code

```python
# Create a list
my_list = [1, 2, 3, 4, 5]

# 1. append() - Adds an element to the end of the list
my_list.append(6)

# 2. clear() - Removes all items from the list
my_list.clear()

# Re-create the list for the next methods
my_list = [1, 2, 3, 4, 5]

# 3. copy() - Returns a shallow copy of the list
my_list_copy = my_list.copy()

# 4. count() - Returns the number of times an element appears in the list
count_of_3 = my_list.count(3)

# 5. extend() - Extends a list by appending elements from another iterable
my_list.extend([6, 7])

# 6. index() - Returns the index of the first occurrence of an element
index_of_4 = my_list.index(4)

# 7. insert() - Inserts an element at a specific position in the list
my_list.insert(2, 10)

# 8. pop() - Removes and returns the item at the given position in the list
popped_item = my_list.pop(1)

# 9. remove() - Removes the first occurrence of a specified element from the list
my_list.remove(10)

# 10. reverse() - Reverses the elements of the list in place
my_list.reverse()

# 11. sort() - Sorts the elements of the list in place
my_list.sort()
