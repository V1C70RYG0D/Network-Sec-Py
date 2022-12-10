// utils.py

This is a utility file that defines a timefunc function. This function is a decorator, which means that it takes another function as input and returns a modified version of that function.

The timefunc decorator takes a function as input, and returns a new function that behaves exactly the same as the original function, but also prints the amount of time it took to run the function. The time is measured using the timeit module's default_timer function, which provides a high-precision timer that can be used to measure the time taken to run a piece of code.

Here's an example of how you might use this decorator to time a function:
``` @timefunc
def my_slow_function():
    # Do some time-consuming computation here
    return result

my_slow_function()
# Output:
# my_slow_function took 3.4 seconds
```

This code would apply the timefunc decorator to the my_slow_function function, so that when you call my_slow_function, it will not only return the result of the computation, but it will also print the time it took to run.
