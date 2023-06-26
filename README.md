# Projeto Recipes App

Este é um projeto frontend desenvolvido em JavaScript utilizando React.js, React Router Dom e Redux. A aplicação web tem como finalidade montar uma plataforma de receitas, na qual os usuários podem fazer login utilizando email e senha, visualizar receitas disponíveis, filtrar receitas por tipo e bebidas, e acessar o modo de preparo das receitas.

O projeto foi desenvolvido por uma equipe de 4 pessoas e tem como objetivo fornecer uma experiência intuitiva e interativa para os usuários explorarem diferentes receitas e aprimorarem suas habilidades culinárias.

## Dependências

Este projeto possui as seguintes dependências:

```json
"dependencies": {
    "bootstrap": "^5.2.0",
    "clipboard-copy": "^4.0.1",
    "prop-types": "^15.8.1",
    "react": "^18.2.0",
    "react-bootstrap": "^2.5.0",
    "react-dom": "^18.2.0",
    "react-redux": "^8.0.4",
    "react-router-dom": "^5.3.3",
    "react-scripts": "^5.0.1",
    "redux": "^4.2.0",
    "redux-devtools-extension": "^2.13.9",
    "redux-thunk": "^2.4.1"
  }
```

Além disso, o projeto possui as seguintes dependências de desenvolvimento:

```json
"devDependencies": {
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.3.0",
    "@testing-library/user-event": "^13.5.0",
    "clipboardy": "^2.1.0",
    "cypress": "^10.4.0",
    "cypress-multi-reporters": "^1.6.1",
    "eslint-config-trybe-frontend": "1.3.1",
    "fs-extra": "^10.1.0",
    "mocha": "^10.0.0",
    "mochawesome": "^7.1.3",
    "mochawesome-merge": "^4.2.1",
    "mochawesome-report-generator": "^6.2.0",
    "stylelint": "^14.10.0",
    "stylelint-order": "^5.0.0"
  }
```

## Scripts

O projeto inclui os seguintes scripts:

```json
"scripts": {
    "cy": "env CY_CLI=true cypress run",
    "cy:open": "cypress open --e2e --browser chrome",
    "start": "env ESLINT_NO_DEV_ERRORS=true react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "test-coverage": "react-scripts test --coverage --watchAll=false",
    "eject": "react-scripts eject",
    "lint": "eslint --no-inline-config --no-error-on-unmatched-pattern -c .eslintrc.json . --ext .js,.jsx",
    "lint:styles": "npx stylelint '**/*.css'"
  }
```

## Como Executar o Projeto

1. Certifique-se de ter o Node.js instalado em sua máquina.

2. Clone este repositório:

   ```
   git clone <URL do repositório>
   ```

3. Navegue até o diretório do projeto:

   ```
   cd project-RecipesApp
   ```

4. Instale as dependências:

   ```
   npm install
   ```



5. Inicie a aplicação em modo de desenvolvimento:

   ```
   npm start
   ```

   A aplicação estará disponível em `http://localhost:3000`.

6. Para gerar uma build de produção:

   ```
   npm run build
   ```

   Os arquivos da build serão gerados no diretório `build/`.

7. Para executar os testes da aplicação:

   ```
   npm test
   ```

   Isso executará os testes e exibirá os resultados no terminal.

## Contribuidores

Este projeto foi desenvolvido por uma equipe de 5 pessoas:

- [Antônio Santana](https://github.com/AntonioSsantana)
- [Italo Lacerda](https://github.com/ItaloLacerda)
- [Ayanara Nathane](https://github.com/ayanara)
- [Renan Storrer](https://github.com/Renan-Storrer)
- [João Marcelo](https://github.com/JohnnyNWT)