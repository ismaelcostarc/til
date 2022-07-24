# Unary plus (+)

O operador de soma unário tenta converter o operando em um número, caso já não seja. É semelhante à função `parseInt()`, porém o operador de soma unário converte valores NaN em 0, e a função não.

```javascript
const x = 1;
const y = -1;

console.log(+x);
// expected output: 1

console.log(+y);
// expected output: -1

console.log(+'');
// expected output: 0

console.log(+true);
// expected output: 1

console.log(+false);
// expected output: 0

console.log(+'hello');
// expected output: NaN

```