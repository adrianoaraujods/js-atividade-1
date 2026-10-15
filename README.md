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
2 - Quando usar cada uma dessas declarações?
3 - Crie variáveis para armazenar:

- Nome completo
- Idade
- Cidade onde mora

4 - Exiba todos os valores no console com mensagens claras, por exemplo:

```js
console.log("Nome:", nomeCompleto);
```

## Operadores

1 - O que são operadores aritméticos? Dê 3 exemplos.
2 - O que são operadores de comparação? Explique com exemplos.
3 - Usando variáveis numéricas, calcule e exiba:

- Soma
- Subtração
- Multiplicação
- Divisão
- Resto da divisão

4 - Compare duas variáveis e exiba no console se elas são iguais ou diferentes.
5 - Use operadores lógicos para:

- Verificar se um número é maior que 10 e menor que 50.
- Verificar se um número é menor que 5 ou maior que 20.
