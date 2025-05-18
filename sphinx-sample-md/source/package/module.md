# Module

This module contains a class that displays a given value.


```python
class MyClass:

    def __init__(self, value):
        self.value = value

    def display(self):
        return self.value
```


**Example**

This is an example of how to use the module.

```python
from package import module

my_class = module.MyClass(value=123)
my_class.display()
```