# Trailing Comma

O _Trailing comma_ trás a habilidade para o compilador não retornar um (_SyntaxError_) quando for adicionado uma vírgula no final de uma lista de parâmetros, na invocação de uma função, após o último elemento de um array ou de um atributo ou método de uma função.

```javascript
function f(p) {}

(p) => {};

const a = ["1", "2"];

const a = {
  first: 1,
  second: 2,
};
```
