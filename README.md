It fails:
```sh
$ poetry run python pythonisweird/foo/bar.py
Traceback (most recent call last):
  File "/Users/inomata137/Desktop/projects/pythonisweird/pythonisweird/foo/bar.py", line 1, in <module>
    from pythonisweird.lib import answer
ModuleNotFoundError: No module named 'pythonisweird'
```

It works, however:
```sh
$ poetry run python
Python 3.12.3 (main, Apr  9 2024, 08:09:14) [Clang 15.0.0 (clang-1500.3.9.4)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> from pythonisweird.lib import answer
>>> print(answer)
42
>>>
```
