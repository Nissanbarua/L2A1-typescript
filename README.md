##  What are some differences between interfaces and types in TypeScript?

In TypeScript, both `interface` and `type` are used to describe the shape of data. They’re very similar — but have some key differences and best-use scenarios.

```ts
interface User {
  name: string;
  age: number;
}
