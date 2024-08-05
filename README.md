# Resolução dos desafios 2

Em uma carreira de desenvolvimento de software, a prática consistente da lógica de programação desempenha um papel fundamental na construção de bases sólidas. A lógica de programação não apenas permite a criação de algoritmos eficientes e soluções elegantes, mas também desenvolve a capacidade de pensar de forma estruturada e analítica. Essa habilidade é essencial para enfrentar desafios complexos e transformar problemas abstratos em implementações tangíveis. 

#### Sugestões de respostas

1) Criar uma função que exibe "Olá, mundo!" no console.

```js 
function mostrarMensagem() {
  console.log("Olá, mundo!");
}

mostrarMensagem();
```

2) Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

```js
function mostrarNome(nome) {
  console.log(`Olá, ${nome}!`);
}

mostrarNome("Danni");
```


3) Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

```js 
function calcularDobro(numero) {
  return numero * 2;
}

let resultadoDobro = calcularDobro(4);
console.log(resultadoDobro);
```

4) Criar uma função que recebe três números como parâmetros e retorna a média deles.

```js
function calcularMedia(a, b, c) {
  return (a + b + c) / 3;
}

let media = calcularMedia(2, 5, 8);
console.log(media);
```

5) Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

```js 
function encontrarMaior(a, b) {
  return a > b ? a : b;
}

let maiorNumero = encontrarMaior(25, 10);
console.log(maiorNumero);
```

6) Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo.

```js 
function quadrado(numero) {
  return numero * numero;
}

let resultado = quadrado(2);
console.log(resultado); 
```
