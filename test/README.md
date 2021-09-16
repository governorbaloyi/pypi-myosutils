# Unit Tests

Write unit tests for the library functions.

## Usage

Create test files that correspond to library files. Write all test cases for each library function. For example:

```python
# test_<file>.py
from libname import say_hello

def test_say_hello_with_no_params():
	assert say_hello() == 'Hello, World!'

def test_say_hello_with_params():
	assert say_hello('Everybody') == 'Hello, Everybody!
```
## Running Tests

Use command `$ pytest` to run all tests