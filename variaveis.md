# Variáveis

## O SÃO VARIÁVEIS NO JAVASCRIPT?
As variáveis ​​são parte integrante de quase todas as linguagens de programação. Elas ​​podem ser usadas para armazenar dados em um programa, como strings, números, objetos JSON ou valores booleanos.

## DECLARAÇÃO DE VARIÁVEIS
Há três formas principais de como declarar variáveis no JavaScript: **var**, **const** e **let**.

 ### Var
  A var pode ser usada para declarar uma variável que é acessível em todo o programa e pode ser alterada.
  ```JavaScript
  var nome = "Natália Campos" ;
  console.log(nome)
  ```

  ### Const
  O const possui um valor fixo, inalterável. É usado dentro do bloco onde foi declarada.
  ```JavaScript
  var nome = "Natália Campos"
  console.log(nome)
  ```

### Let
   O let permite declaração de variáveis limitadas ao escopo de bloco. Isso significa que a variável declarada com let só é acessível dentro do bloco onde foi declarada.
   ```JavaScript
   let nome = "Natália Campos"
   console.log(nome)
   ```
## ESCOPO
O escopo refere-se à acessibilidade e visibilidade das variáveis em diferentes partes do código durante a execução do programa. O escopo determina onde as variáveis e funções são declaradas e onde podem ser acessadas.

Há três tipos de escopos: Global, Função e Bloco.

### Escopo Global
 Variáveis declaradas fora de qualquer função ou bloco de código têm escopo global e podem ser acessadas de qualquer lugar no código, a menos que sejam sombreadas por variáveis locais dentro de funções ou blocos.

 ```JavaScript
 var nome = "Natália Campos"
 function ola() {
    console.log("Olá, " + nome)
 }
ola()
 ```

 ### Escopo de Função
  Variáveis declaradas dentro de uma função têm escopo local e só podem ser acessadas dentro da própria função. Variáveis declaradas com let e const também têm escopo local de bloco.

```JavaScript
function ola() {
    let nome = "Natália Campos"
    console.log("Olá, " + nome)
}
ola()
```

### Escopo de Bloco
O escopo de bloco em JavaScript se refere à visibilidade e acessibilidade de variáveis dentro de um bloco de código delimitado por chaves {}. Um bloco de código pode ser uma estrutura condicional if, um loop for, uma função, ou simplesmente um bloco isolado.
```JavaScript
function exemplo() {
    if (true) {
        let mensagem = "Olá, mundo!"
        console.log(mensagem)
    }
}
```
<br>

# Dados

Em JavaScript, dados são valores que podem ser armazenados e manipulados durante a execução de um programa. 

## TIPOS PRIMITIVOS
-   **Number**:  Números, inteiros ou de ponto flutuante.
```JavaScript
let numero = 17
console.log(numero)
```
-   **Boolean**: Valores Booleanos, "True" ou "False".
```JavaScript
let booleano = true
console.log(booleano)
```
-   **String**: Sequências de caracteres.
```JavaScript
let texto = "Olá, mundo!"
console.log(texto)
```
-   **Null**:  Representa um valor nulo intencionalmente.
```JavaScript
let nulo = null
console.log(nulo)
```

-   **Undefined**: Representa um valor não definido.
```JavaScript
let indefinido
console.log(indefinido)
```
<br>

## OBJETO
Em JavaScript, um objeto é uma coleção de pares chave-valor, onde cada chave é uma string e o valor pode ser qualquer tipo de dado, incluindo números, strings, booleanos, arrays, outros objetos e até mesmo funções. Os objetos em JavaScript são usados para representar entidades do mundo real de forma estruturada e são uma parte fundamental da linguagem.
```JavaScript
let pessoa = {
  nome: "João",
  idade: 30,
  cidade: "São Paulo"
};
```
Nesse exemplo, "pessoa" é o objeto com três propriedades: "nome", "idade" e "cidade".
