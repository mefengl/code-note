# code-note

seperate code by ui is much more easier than by logic

extract component is much more easier than extract hook

array + function is better than object

```javascript
const peoples = [
  {name: 'a', age: 1},
  {name: 'b', age: 2},
  {name: 'c', age: 3},
]

const peoples = [
  ['a', 1],
  ['b', 2],
  ['c', 3],
].map(([name, age]) => ({name, age}))
```
