# Interview Questions
Uses a few resources:
* https://hackernoon.com/160-data-science-interview-questions-415s3y2a
* http://theprofessionalspoint.blogspot.com/2019/01/100-basic-machine-learning-interview.html
* ...Leetcode

## A section

**A question?**

An answer.

## Data Structures and Algorithms - Arrays

## Python

**What is the difference between dictionaries, lists, tuples and sets - provide examples**

Dictionaries:

Dictionaries use key value pairs to store references to data, much like a real life dictionary. 

```
dictionary = {"this is a book name":00001, "this is a different book":00003}
```

Lists:

Lists are simply lists. These aren't arrays, as arrays need to be declared, but they are very similar.

```
list = ["an item", "another item"]
```

Tuples:

Tuples are a list of data assigned to a variable, like a list. However, unlike a list, tuples are immutable, meaning that once the contents have been set they cannot be changed.

```
tuple = ('an item', 'another item', 'immutable', 'an item')
```

Sets:

Unordered and unindexed storage of data. The set iself is mutable (you can add and remove), but the values themselves are immutable. Does not allow duplication.

```
set = {"a", "set"}
```

**Explain list comprehension.**

**Write and explain a lambda function.**

**Explain how you stick to PEP8**

Using Pylint is a good start.
