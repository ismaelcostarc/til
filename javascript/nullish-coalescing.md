# Nullish Coalescing

O *nullish coalescing operator* (??) é um operador lógico que retorna o conteúdo do lado direito sempre que o conteúdo do lado esquerdo for *null* ou *undefined*, caso contrário, retorna o conteúdo do lado esquerdo da operação.

Exemplo:
```javascript
const foo = null ?? 'default string';
console.log(foo);
// expected output: "default string"

const baz = 0 ?? 42;
console.log(baz);
// expected output: 0

```