### 可以使用 is 来判定值的类型

```js
function isFooError (err: any): err is FooError {
  return err
}
if (isFooError(err)) {
  // err handle
}
```