# LibraryName

This library contains functions and classes

## Usage

Create files with functions or classes. For example:

```python
# <file>.py
def say_hello(name=None):
	if name is None:
		return 'Hello, World!'
	else:
		return f'Hello, {name}!'
```

Export Functions in `__init__.py` file. For example:

```python
from <file> import say_hello
```
