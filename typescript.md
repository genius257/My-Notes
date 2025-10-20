
```ts
Record<Keys, Type>
```
https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type


```ts
type Prettify<T> = {
  [K in keyof T]: T[K];
} & {};
```
https://www.totaltypescript.com/concepts/the-prettify-helper
