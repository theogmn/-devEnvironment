<span>Configurações de ambiente para projetos React/ReactNative</span>

<h1>Configuração padrão do VsCode(settings.json)</h1>

```
"[javascript]": {
"editor.codeActionsOnSave": {
"source.fixAll.eslint": true
}
},
"[javascriptreact]": {
"editor.codeActionsOnSave": {
"source.fixAll.eslint": true
}
},

Editar o .eslintrc.js:
rules: {
"class-methods-use-this": "off",
"no-param-reassign": "off",
"camelcase": "off",
"no-unused-vars": ["error", { "argsIgnorePattern": "next" }]
},


5.2.1-Prettier
Utilizado para realizar correções no código que o ESLint não faz.

5.2.2-Adicionar Prettier
yarn add prettier eslint-config-prettier eslint-plugin-prettier -D

5.2.3-Configurar Prettier
Adicionar ao .eslintrc.js:
extends: [
'airbnb-base',
'prettier'
],
plugins:[
'prettier'
],

rules: {
"prettier/prettier": "error",
"class-methods-use-this": "off",
"no-param-reassign": "off",
"camelcase": "off",
"no-unused-vars": ["error", { "argsIgnorePattern": "next" }]
},

```

<h1>NodeJS</h1>
<ol>
  <li>yarn add eslint -D</li>
  <li>yarn eslint --init</li>
  <li>selecionar: "To check syntax, find problem, and enforce code style."</li>
  <li>selecionar: "JavaScript modules"</li>
  <li>selecionar: "None of those"</li>
  <li>selecionar: "Node"</li>
  <li>selecionar: "Use a popular style guide"/ "AirBnb"</li>
  <li>selecionar: "JavaScript"</li>
</ol>

<h3>Remover o package-lock.json e rodar o yarn.(Isso ocorre pois ele instala as dependências do airbnb pelo npm).</h3>

<h3>Adicionar o arquivo .prettierrc e .eslintrc à raiz do projeto.</h3>

<h3>Adicionar o .editorConfig</h3>


<h1>React/React Native</h1>
<ol>
  <li>yarn add eslint -D</li>
  <li>yarn eslint --init</li>
  <li>selecionar: "To check syntax, find problem, and enforce code style."</li>
  <li>selecionar: "JavaScript modules"</li>
  <li>selecionar: "None of those"</li>
  <li>selecionar: "nenhuma das opções"</li>
  <li>selecionar: "Use a popular style guide"/ "AirBnb"</li>
  <li>selecionar: "JavaScript"</li>
</ol>

<h3>Remover o package-lock.json e rodar o yarn.(Isso ocorre pois ele instala as dependências do airbnb pelo npm).</h3>

<h3>Adicionar o arquivo .prettierrc e .eslintrc à raiz do projeto.</h3>

<h3>Adicionar o .editorConfig</h3>