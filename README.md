<span>Configurações de ambiente para projetos React/ReactNative</span>

<h1>Configuração padrão do VsCode(settings.json)</h1>

```json
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

<h3>yarn add prettier eslint-config-prettier e
slint-plugin-prettier babel-eslint -D </h3>

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

<h3>yarn add prettier eslint-config-prettier e
slint-plugin-prettier babel-eslint -D </h3>

<h3>Adicionar o arquivo .prettierrc e .eslintrc à raiz do projeto.</h3>

<h3>Adicionar o .editorConfig</h3>