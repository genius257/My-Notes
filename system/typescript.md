```ts
type Prettify<T> = {
  [K in keyof T]: T[K];
} & {};
```
https://www.totaltypescript.com/concepts/the-prettify-helper
