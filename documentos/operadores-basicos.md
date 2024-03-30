# Operadores Básicos
Em JavaScript, os operadores básicos incluem operadores aritméticos, de atribuição, de comparação, lógicos e de incremento/decremento.

- **Aritméticos**: são usados para realizar operações matemáticas básicas.
```JavaScript
let a = 5;
let b = 2;
let soma = a + b; // soma
let subtracao = a - b; // subtracao
let multiplicacao = a * b; // multiplicacao
let divisao = a / b; // divisao
let resto = a % b; // resto
let potencia = a ** b; // potencia
```
- **De comparação**: são usados para comparar dois valores.
```JavaScript
let idade = 18;
let outraIdade = "18";
console.log(idade == outraIdade); // true (compara apenas o valor)
console.log(idade === outraIdade); // false (compara valor e tipo)
console.log(idade != outraIdade); // false (compara apenas o valor)
console.log(idade !== outraIdade); // true (compara valor e tipo)
```

- **Lógicos**: são usados para combinar expressões condicionais.
- && (E lógico, retorna verdadeiro se ambas as expressões forem verdadeiras)
- || (OU lógico, retorna verdadeiro se pelo menos uma das expressões for verdadeira)
- ! (NÃO lógico, inverte o valor de uma expressão)
```JavaScript
let sol = true;
let chuva = false;
console.log(sol && chuva); // false (E lógico)
console.log(sol || chuva); // true (OU lógico)
console.log(!chuva); // true (NÃO lógico)
```

- **Typeof**: retorna "object" para arrays e objetos, pois em JavaScript, arrays são considerados objetos. Apenas as funções têm um tipo específico, que é "function".
```JavaScript
let x = 10;
console.log(typeof x); // "number"

let notANumber = NaN;
console.log(typeof notANumber); // "number", notANumber is a number :D 

let y = "Olá, mundo!";
console.log(typeof y); // "string"

let z = true;
console.log(typeof z); // "boolean"

let w;
console.log(typeof w); // "undefined"

let obj = { nome: "Alice", idade: 30 };
console.log(typeof obj); // "object"

let arr = [1, 2, 3, 4, 5];
console.log(typeof arr); // "object"

let func = function() { console.log("Função!"); };
console.log(typeof func); // "function"
```
