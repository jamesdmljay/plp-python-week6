# PLP Python Week 6 - Error Handling

This assignment practices handling errors in Python using `try` and `except`.

* `safe_tools.py` - Contains safe functions for division, number conversion, and dictionary field lookup.
* `unbreakable.py` - Demonstrates handling errors so that a program can continue running instead of crashing.

An `if` check cannot catch `"abc"` on its own because the problem occurs when Python tries to convert the text to an integer using `int()`. The `ValueError` is raised during the conversion, so `try` and `except` are needed to catch it safely.
