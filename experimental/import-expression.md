# [Dynamic Import Expression](https://github.com/domenic/proposal-dynamic-import)

## ImportExpression

```js
interface ImportExpression <: Expression {
    type: "ImportExpression";
    source: Expression;
}
```
