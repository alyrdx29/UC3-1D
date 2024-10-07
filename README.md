# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico

Fundamentos do javascript, JavaScript é uma linguagem de __tipagem dinâmica__.
Isso significa que você não necessita declarar o tipo de uma variável antes de sua atribuição.
O tipo será automaticamente determinado quando o programa for processado.
Isso também significa que você pode reatribuir uma mesma variável com um tipo diferente.

Uma variável faz referencia a um espaço na memória do computador.
São utilizadas para guardar informações que serão usadas nos programas.

Criamos a variável nome e atribuimos o valor string de 'natalya' a ela.
em seguida acessamos a variavel e a mostramos na tela.

ex: 
const nome = "alycia"
console.log (alycia)
let batata = 'pure'
batata = 'batata-frita'
## var

É  mais antiga forma de definir variáveis no javascript, ela pode ser reatribuída e redeclarada. 
Diferentemente da const e da let ela não tem escopo de bloco.

## let

A let junto com a const vieram no es6 (atualização de 2015).
Ela também pode ter o seu valor reatribuido mas não pode ser redeclarado.

## const

A const (constante) não pode ter seu valor reatribuído nem redeclarado.
Diferentemente da let e da var. E assim com a let ela também tem escopo de bloco.

const numero = 10;                // Declara uma constante com valor numérico
const saudacao = "Olá, mundo!";  // Declara uma constante com uma string
const frutas = ["maçã", "banana", "laranja"]; // Declara uma constante com um array
const pessoa = { nome: "João", idade: 30 };  // Declara uma constante com um objeto

// Mostrando os valores das constantes
console.log("Número:", numero);
console.log("Saudação:", saudacao);
console.log("Frutas:", frutas);
console.log("Pessoa:", pessoa);

// Modificando o conteúdo do array e objeto (é permitido)
frutas.push("uva"); // Adiciona "uva" ao array
pessoa.idade = 31;  // Atualiza a idade da pessoa

// Mostrando os valores atualizados
console.log("Frutas atualizadas:", frutas);
console.log("Pessoa atualizada:", pessoa);


## CONSOLE.LOG
O console.log é uma função usada em JavaScript para exibir mensagens no console do navegador ou ambiente de execução, como o Node.js. Ele é frequentemente utilizado para depuração (debugging), permitindo que o desenvolvedor veja o valor de variáveis ou mensagens personalizadas em tempo real durante a execução do código.

## console.log(mensagem);

let nome = "João";
console.log(nome); // Saída: João

let idade = 25;
console.log(nome, idade); // Saída: João 25


## PROMPT
Como Funciona o prompt Exibição da Caixa de Diálogo: Quando prompt é chamado, ele exibe uma caixa de diálogo modal com um campo de entrada e uma mensagem opcional. O usuário pode digitar um valor ou cancelar a ação.

// Exibindo o prompt e armazenando a entrada do usuário
let nome = prompt("Qual é o seu nome?", "Nome padrão");

// Verificando se o usuário clicou em Cancelar
if (nome !== null) {
  // Mostrando uma mensagem de boas-vindas
  alert("Olá, " + nome + "!");
} else {
  // Mensagem se o usuário clicar em Cancelar
  alert("Você cancelou a operação.");
}

prompt("Qual é o seu nome?", "Nome padrão"):

## STRING
Em JavaScript, strings são um tipo de dado primitivo usado para representar texto. Strings são sequências de caracteres que podem incluir letras, números, espaços e símbolos. Elas são fundamentais para manipulação e apresentação de dados textuais em um programa. Strings podem ser criadas usando aspas simples ('), aspas duplas (") ou crase (`) para template literals.

 let string1 = 'Olá, mundo!';
let string2 = "Bem-vindo ao JavaScript!";
let string3 = `Você tem ${25} anos.`;
VARIAVEIS
Em JavaScript, variáveis são usadas para armazenar dados que podem ser manipulados e referenciados em diferentes partes do código. Elas atuam como "recipientes" para valores e permitem que esses valores sejam usados e alterados conforme necessário.

## IF ELSE
Em JavaScript, if e else são estruturas de controle de fluxo usadas para executar blocos de código com base em condições. Elas permitem que o programa tome decisões e execute diferentes seções de código dependendo se uma condição é verdadeira ou falsa.

if (condição) {
  // Código a ser executado se a condição for verdadeira
} else {
  // Código a ser executado se a condição for falsa
}
## NUMBER
Em JavaScript, Number é um tipo de dado primitivo usado para representar valores numéricos. O tipo Number pode armazenar tanto números inteiros quanto números de ponto flutuante (decimais). A seguir, estão algumas das principais características e operações associadas ao tipo Number em JavaScript.

let inteiro = 42;
let decimal = 3.14;

## switch

switch (new Date().getDay()) {
  case 6:
    text = "Today is Saturday";
    break;
  case 0:
    text = "Today is Sunday";
    break;
  default:
    text = "Looking forward to the Weekend";
}

## Atividades desenvolvidas
- [javascript](https://codepen.io/alyrdx29/pen/YzoEPNy)
- [javascript](https://codepen.io/alyrdx29/pen/WNqXvrY)
- [javascript](https://codepen.io/alyrdx29/pen/wvLyYJr)
- [javascript](https://codepen.io/alyrdx29/pen/OJervQe)
- [javascript](https://codepen.io/alyrdx29/pen/KKjypoP)
- [javascript](https://codepen.io/alyrdx29/pen/WNqYbLK)
- [javascript](https://codepen.io/alyrdx29/pen/BagYqWd)
- [javascript](https://codepen.io/alyrdx29/pen/YzoYdeK)
- [javascript](https://codepen.io/alyrdx29/pen/rNEYdVj)
- [javascript](https://codepen.io/alyrdx29/pen/gONXoZR)
