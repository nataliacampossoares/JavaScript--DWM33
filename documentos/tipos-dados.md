# Tipos de dados

Em JavaScript, dados são valores que podem ser armazenados e manipulados durante a execução de um programa. 

## TIPOS PRIMITIVOS
-   **Number**:  Números, inteiros ou de ponto flutuante.
```JavaScript
//Código 7
let numero = 17
console.log(numero)
```
-   **Boolean**: Valores Booleanos, "True" ou "False".
```JavaScript
//Código 8
let booleano = true
console.log(booleano)
```
-   **String**: Sequências de caracteres.
```JavaScript
//Código 9
let texto = "Olá, mundo!"
console.log(texto)
```
-   **Null**:  Representa um valor nulo intencionalmente.
```JavaScript
//Código 10
let nulo = null
console.log(nulo)
```

-   **Undefined**: Representa um valor não definido.
```JavaScript
//Código 11
let indefinido
console.log(indefinido)
```
<br>

## OBJETO
Em JavaScript, um objeto é uma coleção de pares chave-valor, onde cada chave é uma string e o valor pode ser qualquer tipo de dado, incluindo números, strings, booleanos, arrays, outros objetos e até mesmo funções. Os objetos em JavaScript são usados para representar entidades do mundo real de forma estruturada e são uma parte fundamental da linguagem.
```JavaScript
//Código 12
let pessoa = {
  nome: "João",
  idade: 30,
  cidade: "São Paulo"
};
```
Nesse exemplo, "pessoa" é o objeto com três propriedades: "nome", "idade" e "cidade".
Para acessá-los, fazemos da seguinte forma:
```JavaScript
pessoa.nome
console.log(pessoa) //Retornará os atributos do objetos e seus nomes
console.log(pessoa.nome) // Retornará somente o nome do objeto
```

## ARRAY
Em JavaScript, um array é um tipo de objeto usado para armazenar múltiplos valores em uma única variável. Os elementos de um array podem ser de qualquer tipo de dado, como números, strings, objetos, funções e até mesmo outros arrays. Os arrays em JavaScript são dinâmicos, o que significa que eles podem crescer ou diminuir de tamanho dinamicamente, adicionando ou removendo elementos. É basicamente uma lista, igual ao Python.

```JavaScript
//Código 13
let array = [1, 2, 3, 4, 5];
```

- **Push**: Adiciona um ou mais elementos ao final do array e retorna o novo comprimento do array.
```JavaScript
//Código 14
let frutas = ['maçã', 'banana'];
let novoComprimento = frutas.push('laranja', 'morango');
console.log(frutas); // ['maçã', 'banana', 'laranja', 'morango']
console.log(novoComprimento); // 4

```
