# Javascript

Estado do JS (https://2020.stateofjs.com/en-US/technologies/)
Onde é executado
Omnipresente na web
App híbridos
Aplicação de ponta-a-ponta: banco de dados, back-end / front-end
Interagir com DOM (api-web)
Requisições dinâmicas
IoT (Internet das Coisas): o JS está presente em tudo
ECMAScript

## Fundamentos JS
Fundamentos do JavaScript são essenciais para avançar no desenvolvimento de aplicações modernas, é a base de diversos frameworks
Neste curso evoluímos da base para o topo
É melhor que começar na frente e precisar retornar a base

## Metodologia
Método progressivo e integrado
Todo arranha céu só é erguido depois de ter uma fundação robusta e segura
Neste curso apresentamos conceitos de modo progressivo, seguindo uma linha de evolução
Começa fácil e vai aumentando a complexidade
Além da especialização, aprendemos a integrar com diversas possibilidades

## Lógica de Programação
Computador:
Máquina que extrai dados
Processar: realizar operações nos dados de entrada
Dado: é o que pode ser processado
Informação: resultado do processamento
Processamento de dados: Entrada (dados) > Processamento > Saída (informação)
E a lógica?
Lógica é aquilo que faz sentido

### Como escrever um programa?
Aplicar a lógica para descrever os passos para resolver um problema em ordem de execução

### A lógica de programação
É a técnica de sequenciar pensamentos, passos, fluxo de dados para atingir um objetivo: a informação
A sequencia de passos, instruções que o computador deve seguir é conhecida como ALGORITMO

### Algoritmo
Sequência lógica e finita de intruções que resolvem um problema

Exemplo: receita de bolo, manual de instrução
Nem todo algoritmo é um programa de computador, mas todo programa de computador é algoritmo
Quem viabiliza o funcionamento dos algoritmos nos computadores: linguagens de programação

### Algoritmo para calcular a média de 3 números
Inicio;
Receber o primeiro número: entrada 1;
Receber o segundo número: entrada 2;
Receber o terceiro número: entrada 3;
PROCESSAMENTO: Somar os 3 números recebidos e dividir por três: (entrada 1 + entrada 2 + entrada 3) / 3;
Exibir o resultado: print, echo, console.log ;
Fim;

### Torre de Hanoi
Mover todos os discos para a direita, com o menor número de movimentos possível, sem colocar um disco em cima de um disco menor: https://www.somatematica.com.br/jogos/hanoi/
Jogos: https://www.somatematica.com.br/jogos.php

## Funcionalidades gerais
Criar algoritmos e programas para executar no navegador: client side

Manipular o DOM: elementos HTML, eventos (clique, submit), estilos CSS

Node.js: framework JS para back-end / runtime em JS

Mongo.db / GraphQL: banco de dados em JS

React / Vue.js / Angular: frameworks JS para desenvolvimento web / mobile

React Native: framework JS para desenvolvimento mobile

rebece e manipular dados

tomar decisões baseados na lógica computacional

loop e interações

condições de saída

## Executar o JS
Console browsers
Editores: Sublime, Visual Studio Code
JS Fiddle https://jsfiddle.net/

## Instalação do Node.js
Para a gente conseguir executar scripts JS no terminal de comando, precisamos utilizar o Node.js
Instalação: https://nodejs.org/pt-br/download/package-manager/
Windows: Primeiro instalar o Chocolatey
Precisa executar o PowerShell como administrator
se tudo der certo na instalação do Chocolatey, rodar: choco install nvs
nvs add lts
$ nvs use lts PATH -= %LOCALAPPDATA%\nvs\default PATH += %LOCALAPPDATA%\nvs\node\14.17.0\x64
MacOs: Primeiro intalar o Homebrew
se tudo der certo na instalação do Homebrew, rodar: brew install node
Após concluir a instalação
Rodar em um novo terminal: node -v

## Variáveis
São utilizadas para referenciar espaço na memória

var
const (fica com valor imutável)
let
string (tipo de variável para conjunto de caracteres)
tipagem: número ou string
array: conjunto de valores