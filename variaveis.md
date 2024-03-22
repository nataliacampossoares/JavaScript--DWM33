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