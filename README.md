# KSquare React Guidelines

## Modules
1. Favor `named exports` over `export default`
```js
// good
export funciton Card() {
  // ..
}

// bad
export default function Card () {
  // ..
}
```
