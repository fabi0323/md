# markdown

**kekw**

*kekw*

[click here](https://www.youtube.com/watch?v=dQw4w9WgXcQ)



|h1|h2|h3|
|---|---|---|
|c1|c2|c3|
|cc1|cc2|cc3|

![](https://user-images.githubusercontent.com/77541325/183598889-e7b9cf1b-a7b8-4626-a5d5-0ecc4711e13e.jpg)


```python
import matplotlib.pyplot as plt
import numpy as np

amount = 20

lst = np.random.randint(0, 100, amount)
x = np.arange(0, amount, 1)

n = len(lst)
for i in range(n):
    for j in range(0, n-i-1):
        plt.bar(x, lst)
        plt.pause(0.000000000000000000000001)
        plt.clf()
        if lst[j] > lst[j+1]:
            lst[j], lst[j+1] = lst[j+1], lst[j]
plt.show()

```
