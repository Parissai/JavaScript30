### What was new

Ways to clone an array : 
1. `array.slice()`
2. `[].concat(array)`
3. `[...array]`
4. `Array.from(array)`
---
Ways to clone an object only 1 level:
1. `Object.assign({}, object)`
2. `{...object}`
---
Ways to deep clone an object :
1. [npm](https://www.npmjs.com/package/clone-deep)
2. `JSON.parse(JSON.stringify(object))` //not recommended


