# Experiment 4: Study of Set in Python

## Aim
* To study the concept of **Set and Frozen Set** in Python.
* To understand and apply **basic set operations**.

---

## Theory

### 1. Introduction to Set
* A **Set** in Python is a built-in data type used to store a collection of values.
* It allows storing **multiple elements in a single variable**.
* Sets are mainly used when **unique values** are required.

---

### 2. Characteristics of Set
* Sets are **unordered**, so elements do not have a fixed position.
* Sets are **mutable**, meaning elements can be added or removed.
* Sets **do not allow duplicate elements**.
* Elements of a set must be **immutable data types** such as integers, floats, strings, or tuples.

---

### 3. Creating a Set
* A set is created using **curly braces `{}`** or the `set()` function.
* If duplicate elements are provided, Python automatically removes them.
* Boolean value `True` and integer `1` are treated as the same element in a set.

---

### 4. Accessing and Checking Elements
* Since sets are unordered, elements cannot be accessed using indexing.
* Membership of an element can be checked using the **`in` keyword**.
* Membership checking in sets is faster compared to lists.

---

### 5. Modifying a Set
* New elements can be added using the **`add()` method**.
* Existing elements can be removed using **`remove()`** or **`discard()`**.
* The `remove()` method raises an error if the element is not present.
* The `discard()` method does not raise an error if the element is missing.

---

### 6. Set Operations
* Python provides powerful operations to compare sets:
  * **Union**: Combines elements from all sets without duplication.
  * **Intersection**: Returns only common elements.
  * **Difference**: Returns elements present in one set but not in another.
  * **Symmetric Difference**: Returns elements present in either set but not in both.
* These operations are commonly used in data comparison tasks.

---

### 7. Frozen Set
* A **Frozen Set** is an immutable version of a set.
* Once created, elements of a frozen set **cannot be added or removed**.
* Frozen sets are useful when data should remain constant.
* They can be used as keys in dictionaries.

---

### 8. Applications of Set
* Removing duplicate entries from data.
* Finding common or unique elements.
* Managing student lists, course selections, and survey responses.
* Performing mathematical set operations efficiently.

---

## Algorithm
1. Start the program.
2. Create a set with multiple elements.
3. Observe the removal of duplicate values.
4. Check membership of an element in the set.
5. Add and remove elements from the set.
6. Perform set operations such as union and intersection.
7. Create a Frozen Set and observe its immutability.
8. Apply sets to practical examples.
9. Stop the program.

---

## Conclusion
* Sets provide an efficient way to store **unique elements**.
* They support various operations for data comparison.
* Frozen sets ensure data integrity by preventing modification.
* Sets are widely used in real-world programming and data analysis.
