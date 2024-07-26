---
created: 2024-07-26T10:08:32+02:00
modified: 2024-07-26T10:08:44+02:00
---

# MD test

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
