# Code samples

Some code samples to test dark theme with syntax highlighting

## Python

```python
def fib(n):
    a, b = 0, 1
    while a < n:
        print(a, end=' ')
        a, b = b, a+b
    print()

fib(1000)
```

## JS

```js
import Vue from "vue"
import router from "./router"
import store from "./store"

new Vue({
    el: "#app",
    store,
    router
})
```