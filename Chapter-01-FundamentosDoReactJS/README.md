# Inicializando projeto
- yarn init -y
- yarn add react
- yarn add react-dom
- yarn add @babel/core @babel/cli @babel/preset-env -D
- Rodando um arquivo js com babel
  - yarn babel src/index.js --out-file dist/bundle.js

# Convertendo jsx do react com babel para que o browser possa entender react
- yarn add @babel/preset-react -D

# Configurando Webpack para que o browser ententenda pacotes como scss, html in js
- yarn add webpack webpack-cli -D
- yarn add babel-loader -D
- yarn add html-webpack-plugin -D
- yarn add webpack-dev-server -D
- Executando Webpacks
  - yarn webpack serve

# Utilizando variaveis de ambiente trabalhando com cross-env
- yarn add cross-env -D

# Instalando recursos para o webpack entender css
- yarn add style-loader css-loader -D

# Trabalhando com SASS
- yarn add sass-loader -D
- yarn add node-sass -D

# Trabalhando com react-refresh
- yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh

# Trabalhando com TypeScript
- yarn add typescript -D
- tsc --init
- yarn add @babel/preset-typescript -D
- yarn add @types/react-dom -D
- yarn add @types/react -D
