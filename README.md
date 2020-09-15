<img src="https://user-images.githubusercontent.com/52006448/93210038-917d1b00-f724-11ea-8678-9e531db9b439.png">


<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>

```python
​
from dataclasses import dataclass
from typing import Tuple

@dataclass
class Stack:
    languages   : Tuple[str, ...] = ("Python", "Go", "Bash")
    databases   : Tuple[str, ...] = ("PostgreSQL", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")
​
```
</h3>
