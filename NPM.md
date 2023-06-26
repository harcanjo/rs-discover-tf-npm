# NPM - Node Package Manager

__Glossary: Dependencies, Packages, Modules__

- [x] Verificar se temos o npm instalado `npm -v`
- [x] Criar nosso próprio pacote
- [x] O que é o arquivo package.json
- [x] Utilizar módulos de terceiros
  `npm install cfonts`
  `npm i cfonts -D`
  `npm i cfonts opn require`
  `npm update`
- [x] O que é o diretório node_modules
- [x] O que é o arquivo package-lock.json
- [x] Criar scripts para rodar com o npm
  `npm run start`

  ```json
    "scripts: {
      "start": "node index.js"
    }"
  ```

  `npm run start`
  `npm start`
  `npm run dev`

- [x] Instalar pacote de maneira global
  `npm i opn -g`

- [x] Desisntalar pacotes
  `npm uninstall opn -g`
  `npm uninstall moment`

- [x] Mudar versão de pacotes
  `npm i moment@1.5.1`
  `npm i moment@latest`
  `npm outdated`
  `npm upgrade`

  :"^2.29.1"
  :"~2.29.1"
  :"2.29.1"
  :"*"

