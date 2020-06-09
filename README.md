<p align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="https://user-images.githubusercontent.com/63422556/83961265-c47f5b00-a867-11ea-8fe6-3349dbe7c5e1.png" width="160px" />
</p>
<p align="center">
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/marcelohaubrih/NLW-01-Ecoleta?style=plastic" />
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/marcelohaubrih/NLW-01-Ecoleta?color=brightgreen&style=plastic" />    
  <a href="https://www.linkedin.com/in/marcelo-haubrih-29ab9a1ab/">
    <img alt="By Marcelo Haubrih" src="https://img.shields.io/badge/%20by-mhcoyote-important?style=plastic">
  </a>
  <a href="https://github.com/marcelohaubrih/NLW-01-Ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/marcelohaubrih/NLW-01-Ecoleta?style=plastic">
  </a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=plastic">
</p>

![logo](https://user-images.githubusercontent.com/63422556/83961290-06a89c80-a868-11ea-91bb-09c8d9aa8fb4.png)

Projeto desenvolvido durante a primeira [NextLevelWeek](https://nextlevelweek.com/) da [Rocketseat](https://rocketseat.com.br) para aplicar os conceitos de `typescript`, `Node.js`, `ReactJS` e `React Native`.

Trata-se de uma aplicação completa (backend, frontend e mobile) para atender a demanda de logistica da coleta de resíduos. Em outras palavras , em homenagem à semana internacional do meio ambiente que coincidiu com o período da realização da Next Level Week 1.0.
  
  [Instalação](#instalação)&nbsp;&nbsp;|&nbsp;&nbsp;
  [Execução](#execução)&nbsp;&nbsp;|&nbsp;&nbsp;
  [Tecnologias](#tecnologias)&nbsp;&nbsp;|&nbsp;&nbsp;
  [Preview](#preview)&nbsp;&nbsp;|&nbsp;&nbsp;
  [Licença](#licença)  

### Pré Requisitos

* É necessário que você tenha o `Node.js` instalado em sua máquina. 
* Para a aplicação Mobile é necessário instalar o pacote `expo` em sua máquia

## Instalação

Clonando este repositório em sua máquina local e acessaando a pasta do projeto:

```bash
git clone https://github.com/marcelohaubrih/NLW-01-Ecoleta.git
cd nlw
```

### Backend
Instalando as dependências do backend da aplicação:

```bash
cd server
npm install
```
Veja os [detalhes de configuração](./server/README.md) do Backend para criar as variáveis de ambiente necessárias.

### Frontend

Instalando as dependências do frontend da aplicação:

```bash
cd ../web
npm install
```
Veja os [detalhes de configuração](./web/README.md) do Frontend para criar as variáveis de ambiente necessárias.

### Mobile

Instalando as dependências da aplicação mobile:

```bash
cd ../mobile
npm install
```
Veja os [detalhes de configuração](./mobile/README.md) da Aplicação Mobile para criar as variáveis de ambiente necessárias.

## Execução
Toda a aplicação pode ser inicializada em ambiente de desenvolvimento com facilidade, seguindo as instruções abaixo:

### Backend
A primeira parte que deve ser executada no ambiente de desenvolvimento é o servidor `node.js`. 

Certifique-se de que está dentro da pasta `server` do projeto em seu terminal e que você já configurou as [variáveis de ambiente](./server/README.md) corretamente, em seguida execute o comando abaixo para inicializá-lo:

```bash
npm run dev
```

### Frontend
Este é o site `ReactJS` onde os pontos de coleta são cadastrados. É necessário que o backend já esteja operacional. 

Certifique-se de que está dentro da pasta `web` do projeto em seu terminal e que você já configurou as [variáveis de ambiente](./web/README.md) corretamente, em seguida execute o comando abaixo para inicializá-lo:

```bash
npm start
```
### Mobile
Nesta parte você irá inicializar a aplicação mobile, escrita com `React Native` onde os pontos de coleta podem ser consultados por cidade. Esta parte funciona independente do Frontend, porém é necessário que o backend já esteja operacional. 

Certifique-se de que está dentro da pasta `mobile` do projeto em seu terminal e que você já configurou as [variáveis de ambiente](./mobile/README.md) corretamente, em seguida execute o comando abaixo para inicializá-lo:

```bash
npm start
```
Após o projeto mobile inicializar, será exibido um `QRCode` no terminal e uma aba dos eu navegador irá carregar o `Metro Bundler`. Neste momento você precisará instalar em seu dispositivo móvel, um aplicativoo chamado `Expo`.
Ele está disponível nas APP Stores:

- [Expo](https://play.google.com/store/apps/details?id=host.exp.exponent) na Google Play
- [Expo Client](https://apps.apple.com/br/app/expo-client/id982107779) na Apple Store

Abra em seu smartphone o aplicativo Expo e escaneie o código de barras exibido na inicialização do projeto.


## Tecnologias

* [Node.js](https://nodejs.org/) - Usado para construir o backend (webservice REST) do projeto
* [express](https://expressjs.com/) - Framework Web utilizado no backend
* [knex.js](http://knexjs.org/) - ORM usado no backend para auxiliar no versionamento do banco de dados
* [sqlite3](https://www.sqlite.org/) - Banco de dados utilisado no backend para peristência dos dados
* [React](https://reactjs.org/) - Usado para construir o frontend (website)
* [React Native](https://reactnative.dev/) - Usado para construir a aplicação Mobile multiplataforma
* [expo](https://expo.io/) - Usado para facilitar o desenvolvimento com `React Native`
* [typescript](https://www.typescriptlang.org/) - Usado para melhorar a integridade do código final e auxiliar o desenvolvimento em equipe

## Licença

Este projeto foi desenvovido sob a licença MIT. Veja o [LICENSE](./LICENSE) para detalhes.


By [Marcelo Haubrih](https://www.linkedin.com/in/marcelo-haubrih-29ab9a1ab/)
