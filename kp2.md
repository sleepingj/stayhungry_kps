### 让对象的 key 值为联合类型

```js
type ColorType = "red" | "green" | "blue";
type colorsCall = {
  [color in ColorType]: string;
};
```