
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


```ts
declare const __opaque__type__: unique symbol;

type OpaqueType<BaseType, TagName> = BaseType & {
  readonly [__opaque__type__]: TagName;
};
```
https://blog.beraliv.dev/2021-05-07-opaque-type-in-typescript
