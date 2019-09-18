# Generator-Python

This project aims to show how to use generators in python.

# What is generator?

Generators are objects to create iterable objects and don`t occupy memory.

Generators are a simple way of creating iterators.

Generator is a function that return an object(iterator) and it only return one value at a time.


## Generators in Python: 

    -Use the yield keyword
    -can contain more yield statement.
    -Returns an iterator which means methods like __iter__() and __next__() are implemented automatically.
    -When the function ends,StopIteration is raise an error on further calls(not shown in this example)

## Differences between Generator function and a Normal function

    -Genetors use yield statement instead of return statement.
    -Return statement terminates a function entirely 
     but yield statement only gives a value when a function calls.
