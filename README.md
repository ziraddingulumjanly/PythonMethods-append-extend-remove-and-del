
## **Project Overview**
This Python script (`list_operations.ipynb`) is designed to demonstrate the key operations and methods used to manipulate lists in Python, including **`append()`**, **`extend()`**, **`remove()`**, and **`del`**. The script includes comprehensive comments and examples to highlight the differences and appropriate use cases for each operation.

## **Features**
- **`append()`**: Adds a single element to the end of the list.
- **`extend()`**: Extends the list by adding multiple elements from another iterable.
- **`remove()`**: Removes the first occurrence of a specified value from the list.
- **`del`**: Deletes elements by index or slices a portion of the list.

## **Differences Between Methods**
1. **`append()` vs `extend()`**:
   - `append()` adds a single element as a single entry.
   - `extend()` adds multiple elements individually to the list.

2. **`remove()` vs `del`**:
   - `remove()` deletes the first occurrence of a specified value.
   - `del` deletes elements based on index positions or slices of elements.

## **Error Handling**
The script also demonstrates how to handle common errors that occur when performing these operations:

- **`ValueError`**:
  - Triggered when `remove()` is called with a value that does not exist in the list.
  - Example: `my_list.remove("NonExistentItem")` will raise a `ValueError`.

- **`IndexError`**:
  - Triggered when `del` is used with an out-of-range index.
  - Example: `del my_list[10]` when the list has fewer than 10 items will raise an `IndexError`.


##ZIRADDINGULUMJANLI2024
