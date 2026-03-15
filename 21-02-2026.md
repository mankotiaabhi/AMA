#  21/02/2026

## AMA Session -- Questions & Answers

------------------------------------------------------------------------

##  What is List?

A **List** in Python is an ordered, mutable collection that can store
multiple values of different data types.

Example:

``` python
nums = [1, 2, 3, "hello"]
```

-   Ordered
-   Mutable
-   Allows duplicates

------------------------------------------------------------------------

## Grep in CLI

`grep` is a command-line tool used to search text patterns inside files.

Example:

``` bash
grep "error" file.txt
```

------------------------------------------------------------------------

## Extend in List

`extend()` adds multiple elements from another iterable to a list.

``` python
a = [1, 2]
a.extend([3, 4])
```

------------------------------------------------------------------------

## What is Git?

Git is a version control system used to track changes in code and
collaborate with others.

------------------------------------------------------------------------

## pop() and remove()

-   `pop()` → removes element by index and returns it\
-   `remove()` → removes element by value

------------------------------------------------------------------------

## Type Casting

Type casting means converting one data type into another.

Example:

``` python
int("10")
```

------------------------------------------------------------------------

## **init** Method

`__init__` is a constructor method in Python classes.\
It runs automatically when an object is created.

------------------------------------------------------------------------

## Lambda Function

A lambda function is an anonymous (no-name) function.

Example:

``` python
square = lambda x: x * x
```

------------------------------------------------------------------------

##  Mutable and Immutable

-   Mutable → can change after creation (list, dict, set)\
-   Immutable → cannot change (int, string, tuple)

------------------------------------------------------------------------

## Data Types

Basic Python data types:

-   int
-   float
-   str
-   bool
-   list
-   tuple
-   set
-   dict

------------------------------------------------------------------------

## Inheritance

Inheritance allows one class to use properties of another class.

------------------------------------------------------------------------

## S in SOLID

S stands for Single Responsibility Principle.\
A class should have only one responsibility.

------------------------------------------------------------------------

## Branch Creation in Git

``` bash
git branch branch_name
git checkout branch_name
```

Or:

``` bash
git checkout -b branch_name
```

------------------------------------------------------------------------

## SED in CLI

`sed` is a stream editor used to modify text in files.

Example:

``` bash
sed 's/old/new/g' file.txt
```

------------------------------------------------------------------------

## Error Handling

Error handling prevents program crashes using `try` and `except`.

``` python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
```