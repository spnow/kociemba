# kociemba
This is a Python implementation of Kociemba's two-phase algorithm for solving Rubik's Cube.
Original Java implementation can be found here: http://kociemba.org/download.htm.

This port is pretty straightforward (not to say dumb) and most probably can be optimized.
I would recommend running it with PyPy, because it is too slow under CPython.

## Testing
In the root directory you can find a test script that contains some tests, generated by the original Java implementation. Run it like this:

```$ pypy test.py```

There is also a bigger test file called javares.txt. You can feed it to the test.py:

```$ pypy test.py javares.txt```
