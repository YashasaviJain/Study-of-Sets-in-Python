# Experiment 4: Study of Set in Python

## Aim
* To study the concept of **Set and Frozen Set** in Python.
* To understand and apply **basic set operations**.

---

## Theory
* A **Set** in Python is a collection used to store **multiple values in a single variable**.
* Sets are **unordered**, so elements do not have a fixed position or index.
* Sets are **mutable**, which means elements can be added or removed after creation.
* A set **does not allow duplicate elements**. If duplicate values are given, Python automatically removes them.
* Elements of a set must be of **immutable data types** such as numbers, strings, or tuples.
* In Python, boolean value `True` and integer `1` are considered equal in a set.
* Membership of an element in a set can be checked using the **`in` keyword**.
* Python provides built-in methods like `add()`, `remove()`, and `discard()` to modify sets.
* **Set operations** are used to compare two or more sets:
  * **Union** returns all unique elements from both sets.
  * **Intersection** returns common elements from all sets.
  * **Difference** returns elements present in one set but not in the other.
  * **Symmetric Difference** returns elements present in either set but not in both.
* A **Frozen Set** is an immutable version of a set.
* Once a frozen set is created, its elements **cannot be added, removed, or changed**.
* Frozen sets are useful when data needs to remain **constant and secure**.

---

## Algorithm
1. Start the program.
2. Create a set with multiple elements.
3. Observe that duplicate values are not stored.
4. Check membership of an element in the set.
5. Add a new element to the set.
6. Remove an element from the set.
7. Perform set operations:
   * Union
   * Intersection
   * Difference
   * Symmetric Difference
8. Create a Frozen Set and observe its immutability.
9. Apply set operations to solve practical problems.
10. Stop the program.

---

## Conclusion
* Sets in Python efficiently store **unique data**.
* They allow easy comparison of data using set operations.
* Frozen sets ensure that data remains **unchanged**.
* Sets are widely used in real-world applications such as student records, surveys, and data analysis.
