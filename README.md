# Atividades-JS---1

### 📚 Atividade de JavaScript

# Praticar os conhecimentos sobre:

- Tipos de saída
- Declarações e sintaxe
- Comentários
- Variáveis
- Operadores

## Tipos de Saída

1 - O que é um tipo de saída em JavaScript?

Uma saída em JavaScript é uma forma de exibir uma informação para o usuário/desenvolvedor.

2 - Cite e explique 3 tipos de saída diferentes em JS (por exemplo: `console.log`, `alert`, `document.write`)

- **`console.log`:** é uma de exibir algum valor de qualquer tipo (inclusive elementos) no console de desenvolvimento do navegador. Também existe variações como `console.warn` para adiciona a semântica de aviso e `console.error` que registra um erro. Exemplo:

```js
console.log("Hello World!");
let x = 10;
console.log(x);
```

- **`alert`:** exibe uma notificação através de uma janela nativa do navegador com uma mensagem textual. Também é possível utilizar o `confirm` que também exibe uma notificação, porém com um botão de confirmar ou cancelar, e retorna um valor de `true` ou `false` dependendo da escolha do usuário. Exemplo:

```js
alert("Sua ação foi registrada com sucesso.");
confirm("Você tem certeza?");
```

- **`innerHTML`:** adiciona um conteúdo HTML válido dentro de um elemento. Exemplo:

```html
<p id="mensagem"></p>

<script>
  const elemento = document.getElementById("mensagem");
  elemento.innerHTML = "Texto inserido pelo JavaScript!";
</script>
```

3 - Crie um arquivo saida.js e exiba as seguintes mensagens:

“Olá, mundo!” no console.

Uma mensagem de alerta no navegador com seu nome.

Uma mensagem na página HTML dizendo: "Você completou a Parte 1!"

## Declarações, Sintaxe e Comentários

1 - Explique o que significa uma declaração em JavaScript.

Uma declaração é um bloco de código que executa uma instrução. Em JavaScript, um declaração pode ser delimitada por uma quebra de linha ou um ponto e vírugla `;`.

2 - Qual a importância dos comentários no código?

Comentários no código servem para indicar coisas não-óbvias, facilitando o entendimento, cooperação com outros desenvolvedores e a manutenabilidade do código.

3 - Reescreva o código abaixo, adicionando comentários explicativos para cada linha:

```js
let idade = 25; // cria uma variável com o identificador 'idade' e atribui o valor de 25.

console.log(idade); // imprime o valor atual da variável 'idade' no console.
```

4 - Corrija os erros de sintaxe no trecho abaixo:

```js
let nome = "Ana";
console.log(nome);
```

## Variáveis

1 - Qual a diferença entre `let`, `const` e `var`?

- **`let`:** é uma variável de escopo local, somente existindo durante a execução do bloco de código em que ela foi declarada.

- **`const`:** é uma 'variável' com valor constante, não podendo ser modificada após sua declaração. Objetos declarados como constantes ainda podem ter seus atributos modificados, mas não é possível atribuir outro objeto inteiro. Vetores podem ter elementos modificados, adicionados ou expluídos, mas não é possível redefiní-lo.

- **`var`:** é uma variável de escopo de função ou global (não respeita blocos de código), podendo ser reatribuída e redeclarada livremente, e é inicializada com o valor `undefined`.

2 - Quando usar cada uma dessas declarações?

Por convenção, é recomendado utilizar apenas `const` para todas as variáveis, pois protege o valor contra reatribuições acidentais e deixa o código mais seguro. A excessão é justamente quando se o valor da variável precisar ser modificado durante a execução, nesses casos, devemos utilizar `let`. O uso de `var` não é recomendado atualmente em nenhum caso, mas pode ser encontrado em sistemas legados.

3 - Crie variáveis para armazenar:

- Nome completo:

```js
const nomeCompleto = "Adriano Araújo Domingos dos Santos";
```

- Idade:

```js
const idade = 24;
```

- Cidade onde mora:

```js
const cidade = "Belo Horizonte";
```

4 - Exiba todos os valores no console com mensagens claras:

```js
console.log("Nome completo: ", nomeCompleto);
console.log("Idade: ", idade);
console.log("Cidade onde mora: ", cidade);
```

## Operadores

1 - O que são operadores aritméticos? Dê 3 exemplos.

Operadores aritméticos são formas de realizar operações (matemáticas ou gramáticais) utilizando duas variáveis. O seu comportamento depende dos tipos das variáveis utilizadas, de modo que alguns operadores (como `+`) são sobrecarregados. Exemplos:

- **`var1 + var2`:**
  - `1 + 2`: retorna `3`, que corresponde ao valor da soma de `1` e `2`.
  - `"abc" + "def"`: retorna `abcdef`, que corresponde a concatenação das strings `abc` e `def`.

- **`var1 - var2`:**
  - `5 - 3`: retorna `2`, que corresponde a subtração de `5` por `3`.

- **`var1 * var2`:**
  - `4 * 3`: retorna `12`, que corresponde ao produto entre `4` e `3`.

2 - O que são operadores de comparação? Explique com exemplos.

Operadores de comparação servem para fazer operações booleanas, sempre retornando um valor de alguma parte das expressões (normalmente `true` ou `false`). Esse operadores normalmente utilizam duas expressões que também são booleanas. O JavaScript sempre tenta converter uma variável em um valor booleano, mas isso pode causar comportamentos inesperados.

- **`==`:** compara o se duas expressões tem valores iguais.
- **`===`:** compara se duas expressões tem valores e tipos iguais.
- **`!==`:** compara se duas expressões tem valores e tipos diferentes.
- **`||`:** funciona como um 'OU' lógico, verificando se uma das expressões é verdadeira, retornando o valor da primeira expressão caso ela seja verdadeira ou retornando o valor da segunda caso contrário.
- **`&&`:** funciona como um 'E' lógico, verificando se ambas expressões são verdadeiras, retornando o valor da segunda expressão caso sejam ou retornando `false` caso contrário.
- **`>`:** compara se o valor da primeira expressão é maior que o da segunda, retornando `true` caso seja e `false` caso contrário.
- **`<=`:** compara se o valor da primeira expressão é menor ou igual ao segunda, retornando `true` caso seja e `false` caso contrário.

3 - Usando variáveis numéricas, calcule e exiba:

- Soma:

```js
const a = 7;
const b = 5;
console.log(a + b); // imprime 13
```

- Subtração:

```js
const a = 7;
const a = 5;
console.log(a - b); // imprime 2
```

- Multiplicação:

```js
const a = 7;
const a = 5;
console.log(a * b); // imprime 30
```

- Divisão:

```js
const a = 7;
const a = 5;
console.log(a / b); // imprime 1
```

- Resto da divisão:

```js
const a = 7;
const a = 5;
console.log(a % b); // imprime 2
```

4 - Compare duas variáveis e exiba no console se elas são iguais ou diferentes.

```js
const a = 7;
const a = 5;
console.log(a === b); // imprime false
```

5 - Use operadores lógicos para:

- Verificar se um número é maior que 10 e menor que 50.

```js
const numero = 7;
console.log(numero > 10 && numero < 50); // imprime false
```

- Verificar se um número é menor que 5 ou maior que 20.

```js
const numero = 7;
console.log(numero < 5 || numero > 20); // imprime false
```
