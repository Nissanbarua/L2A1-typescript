##  What are some differences between interfaces and types in TypeScript?

In TypeScript, both `interface` and `type` are used to describe the shape of data. They’re very similar — but have some key differences and best-use scenarios.

```ts
interface User {
  name: string;
  age: number;
}

type User = {
  name: string;
  age: number;
};


## What is type inference in TypeScript? Why is it helpful?

TypeScript is smart — sometimes *you don’t even need to tell it what type you’re using*. That’s because of **type inference**.


Type inference means **TypeScript figures out the type for you**, based on how you write your code.

###  Example:

```ts
let name = "Alice";  // TypeScript automatically knows this is a string
// name: string

let age = 25;        // TypeScript knows this is a number
// age: number
