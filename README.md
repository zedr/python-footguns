# python-footguns

A collection of guns that I've incautiously discharged.

- implicit relative imports
- mutable default keyword arguments
- mutable objects in the module namespace
- mutable objects as values of class attributes
- oops I've uploaded my home directory to PyPI
- forgot to add an `__init__.py` (PEP 420)
- `pathlib.Path` is not JSON serializable
- `collections.defaultdict` doesn't quack like a duck
- string interpolation may had side effects
- global < classes < nonlocal
- `assert` is AFK
- `[{}] * 3` not the same as `[{} for i in range(3)]`
- wide try excepts
- ...more TBD
