# TIL - Today I Learned

## 2020

### May

#### Day 04

- `Element.getBoundingClientRect()` aprendi que posso usá-lo para recuperar a posição e o tamanho de um elemento dentro do **viewport**, [link para documentação](https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect).

- Aprendi como atachar eventos **globais** no angular ex.:

```html
  // o evento click será disparado no clique sobre a div
  // e também no clique sobre o document
  <div (document:click)="doSomething()"></div>
```
