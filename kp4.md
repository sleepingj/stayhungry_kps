### 让数组的值作为联合类型

```js
const COLOR = ["red", "green", "blue"] as const;
type ColorType = typeof COLOR[number]; // "red" | "green" | "blue"
```