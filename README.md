Criando projeto do zero

yarn create react-app modulo05
apagar o arquivo README.md
deletar do package.json:
"eslintConfig": {
"extends": "react-app"
},
Dentro da pasta public:
index.html => apagar os comentários e <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />

Deletar o arquivo c:\public\manifest.json

yarn start

Deletar da pasta src:
-App.css
-App.test.js
-index.css
-logo.svg
-serviceWorker.js

ESLint, Prettier & EditorConfig
Generate.editorconfig
trim_trailing_whitespace = true
insert_final_newline = true
indent_style = lf

yarn add eslint -D
yarn eslint --init
yarn add prettier eslint-config-prettier
yarn add eslint-plugin-prettier babel-eslint -D

yarn add react-router-dom

yarn add styled-components

yarn add react-icons

yarn add polished

yarn add json-server

yarn add axios

json-server server.json -p 3333
"scripts": {
"api:server": "json-server server.json -p 3333"
}

yarn add redux react-redux

yarn add reactotron-react-js reactotron-redux

yarn add immer

yarn add redux-saga
