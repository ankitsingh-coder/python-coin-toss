# Python Coin Toss

A beginner-friendly Python mini project that simulates a coin toss using Python’s random module.

## Code
```python
import random

coin_side = random.randint(0, 1)

if coin_side == 0:
    print("TAIL")
else:
    print("HEAD")
