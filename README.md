# KSquare React Guidelines

## Functions
1. Favor `arrow functions` expressions over function declarations or named expressions
```js
// good
const isEven = (n: number): number => n % 2 === 0;

// bad
function isEven(n: number): number {
  return n % 2 === 0;
}

const isEven = function (n: number): number {
  return n % 2 === 0;
}
```

## Modules

1. Favor `named exports` over `export default`
```js
// good
export const Card: React.FC = () => {
  // ..
}

// bad
const Card: React.FC = () => {
  // ..
}

export default Card
```
