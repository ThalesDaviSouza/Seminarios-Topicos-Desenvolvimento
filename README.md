# Seminários: Ferramentas de Desenvolvimento
## Grupo VueJS

**Data: 24/11**

**Valor: 10 pontos**

**Grupo: 5 alunos**
- Arthur Henrique
- Caio César
- Eduardo Santos Birchal
- Gabrielle Maia
- Thales Davi


# Roteiro
## Introdução
VueJs começou a ser desenvolvido por Evan You em 2013 com o objetivo de criar um novo framework front-end que extraisse os aspectos positivos do AngularJs (tecnologia que Evan utilizava em seu trabalho) e que fosse relativamente mais simples de se aprender e de utilizar. Dessa maneira, o proposito do Vue no momento de sua criação era de permitir a criação de interfaces para a aplicativos web de forma mais fácil, intuitiva e prática do que outras tecnologias como o já citado Angular JS. 

O VueJs é utilizado para a criação de Single Page Applications (SPA's) dinâmicas. Uma SPA é um site que carrega um único documento e substitui a página existente por novos dados de um servidor web, em vez de recarregar as páginas individualmente do zero. Como resultado, o conteúdo da página é atualizado em tempo real com base nas ações do usuário, com transições rápidas e sem atualização.

Para alcançar seu objetivo, permitir a criação de SPAs dinâmicas, o VueJs, em sua versão 3, conta com uma série de recursos para isso. Dentre eles, os recursos mais relevantes que iremos abordar serão: variáveis reativas, ligação de dados (data, class and style binding), manipulação de enventos (event handling), renderização condicional (condicional rendering), componentização, criação de eventos personalizados, declaração de propriedades e watchers. Na seção Getting Started iremos nos aprofundar um pouco nesses tópicos.

## Instalação e configuração
O VueJs, no momento de escrita deste documento, apresenta duas formas de ser inserido em um projeto, através da CDN (que utiliza o [unpk](https://www.unpkg.com)) ou por meio da instalação do pacote por meio da npm. A seguir iremos abordar as duas formas de instalação.

#### Vue CDN
Para instalar o VueJs no seu projeto basta colocar o seguinte script no início do código. 
```html
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
```
Através dessa tag o Vue 3 (versão mais atual no momento) será importado em sua versão mais nova e já poderá ser utilizado. 

#### Vue NPM
Utilizar o Vue por meio da NPM exige como pré-requisitos o nodeJs em sua versão 16.0 ou superior. Com isso já dito, para instalar o Vue no seu projeto por meio da NPM basta utilizar o seguinte comando no console do node:

```node
npm create vue@latest
```
No próprio console será solicitado o nome do projeto e então serão feitas algumas perguntas sobre se você deseja instalar dependencias de algumas tecnologias que você usará no projeto, se caso a tecnologia for ser usada no projeto, selecione "Yes" e pressione "Enter", se caso não for ser utilizada, escolha "No".

Após isso, basta seguir a seguinte sequência de comandos para instalar completamente o Vue e iniciar o projeto.
```Node
cd <nome-do-projeto>
npm install
npm run dev
```

Seguir esse passo a passo irá criar um projeto novo com o vue já instalado e configurado para ser utilizado.

## Getting Started

## Ferramentas similares
- React
- Angular
