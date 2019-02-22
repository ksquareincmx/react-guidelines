# KSquare React Guidelines

## Functions
1. Favor `arrow functions` expressions over function declarations or named expressions
```js
// good
const isEven = number => number % 2 === 0;

// bad
function isEven(number) {
  return number % 2 === 0;
}

const isEven = function (number) {
  return number % 2 === 0;
}
```

## Modules

1. Favor `named exports` over `export default`
```js
// good
export const Card = () => {
  // ..
}

// bad
const Card = () => {
  // ..
}

export default Card
```
