## Add library to Python Code 
For example, you can use ctypes module.

```python3
from ctypes import *

library = CDLL("/path/to/library.so")
library.hello_world(arg1, arg2)
```
