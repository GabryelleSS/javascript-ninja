# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma(numb1, numb2) {
  return numb1 + numb2;
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var invocacao = soma(2, 3) + 5;

// Qual o valor atualizado dessa variável?
10;

// Declare uma nova variável, sem valor.
var variavel;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function addValor() {
  variavel = 32;
  return "O valor da variável agora é " + variavel;
}

// Invoque a função criada acima.
addValor();

// Qual o retorno da função? (Use comentários de bloco).
/* O valor da variável agora é 32 */

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function multiplicacao(a, b, c) {
  if ((a === undefined, b === undefined, c === undefined)) {
    return "Preencha todos os valores corretamente!";
  }

  return a * b * c + 2;
}

// Invoque a função criada acima, passando só dois números como argumento.
multiplicacao(1, 2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// Preencha todos os valores corretamente!

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
multiplicacao(1, 2, 10);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// 22

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function funcao(a, b, c) {
  if (arg1 !== undefined && arg2 === undefined && arg3 === undefined) {
    return console.log(arg1);
  } else if (arg1 !== undefined && arg2 !== undefined && arg3 === undefined) {
    return console.log(arg1 + arg2);
  } else if (arg1 !== undefined && arg2 !== undefined && arg3 !== undefined) {
    return console.log((arg1 + arg2) / arg3);
  } else if (arg1 === undefined && arg2 === undefined && arg3 === undefined) {
    return console.log(false);
  } else {
    return console.log(null);
  }
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
somaEProduto();
// false
somaEProduto(2);
// 2
somaEProduto(2, 5);
// 2
somaEProduto(2, 51, 2);
// 26.5
```
