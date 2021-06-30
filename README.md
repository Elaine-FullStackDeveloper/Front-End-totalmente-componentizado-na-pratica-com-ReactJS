# Projeto Digital Innovation One

Criando um front-end totalmente componentizado na prática com ReactJS

Como resultado temos uma página, na qual podemos pesquisar por usuários do Github, usando apenas seu username.

## Requisitos para o projeto rodar:

###Instalação npm
$ sudo apt install nodejs

###Atualizar npm:
$ sudo npm install -g npm@latest

###Instalação React Native CLI
Com o NodeJS instalado, podemos instalar o CLI (Command Line Interface) do React Native:
$ sudo npm install -g react-native-cli

###Axios
Promise based HTTP client for the browser and node.js
$ npm install axios

###Instalação yarn

$ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
$ sudo apt update && sudo apt install yarn

$ yarn --version

###Criando um app React

npx create-react-app my-app
cd my-app
npm start

OU

$ yarn create react-app my-app

my-app.
├── README.md.
├── node_modules.
├── package.json.
├── .gitignore.
├── public.
│   ├── favicon.ico.
│   ├── index.html.
│   └── manifest.json.
└── src.
    ├── App.css.
    ├── App.js.
    ├── App.test.js.
    ├── index.css.
    ├── index.js.
    ├── logo.svg.
    └── serviceWorker.js.
    └── setupTests.js.

(https://github.com/facebook/create-react-app#creating-an-app)

###Executar o app:
$ npm start ou yarn start

Executa o aplicativo em modo de desenvolvimento.
Abra http: // localhost: 3000 para visualizá-lo no navegador.

###Para executar um projeto já criado sem a pasta node_modules, deve executar no terminal:
$ yarn install ou npm install



