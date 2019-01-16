# pineapple

## Dependências

O projeto possui as seguintes dependências:

- Node
- Yarn

## Instalação das dependências

### Node

É altamente recomendado instalar o Node pelo Nvm, pela sua facilidade de instalação e troca de versão. Para instalar o NVM, siga as instruções da página: https://github.com/creationix/nvm

Uma vez instalado, basta rodar o comando:

`nvm install --lts`

### Yarn

O Yarn tem como dependencia o Node, por isso é necessário que o Node esteja instalado.

Para instalar o yarn, basta rodar o comando:

`npm install -g yarn`

## Baixar as dependencias

Antes de rodar o projeto é necessário baixar as dependencias do mesmo. Para isso basta rodar o comando:

`yarn`

no diretório raiz da aplicação.

## Execução do projeto

### Desenvolvimento

Para a primeira execução do projeto:

`react-native run-android`

A partir da segunda execução do projeto, pode-se utilizar o comando:

`yarn dev`

E para executar o mock da api (sem necessidade de acesso ao backend), em outro terminal, execute:

`yarn api`
