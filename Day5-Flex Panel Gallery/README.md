### What was new

- Difference between `toggleOpen` and `toggleOpen()`: the latter runs after pageload, the first one is a reference to the function
- [`Element.classList.toggle()`](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)
- Multiple transitions :
```
transition: font-size 0.7s cubic-bezier(0.61, -0.19, 0.7, -0.11),
            flex 0.7s cubic-bezier(0.61, -0.19, 0.7, -0.11),
            background 0.2s;
```