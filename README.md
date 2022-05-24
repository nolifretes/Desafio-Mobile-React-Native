# React-Native

## Projeto

A proposta deste projeto é criar um app bem simples utilizando React-Native, consumindo a API do GitHub.

**Dependências do projeto:**

* **react-native**: em caso de dúvidas, utilize a documentação oficial https://facebook.github.io/react-native/docs/getting-started
* **react-native-navigation** ou **react-navigation** : em caso de dúvidas, utilize as documentações: https://github.com/wix/react-native-navigation / https://reactnavigation.org/docs/getting-started
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para criar a interface e implementar novas funcionalidades, mas lembre, todo o projeto será avaliado.

## Funcionalidades básicas

### Página inicial - Funcionalidades básicas

- Possuir um campo de busca, para que seja possível digitar o nome de um usuário e um nome de repositório (ex: Facebook/React). Este valor precisa ser repassado para o endpoint API.
- Exibir os resultados da consulta da api, mostrando o repositório em uma lista.
- Ao clicar em um repositório na lista, a aplicação deverá redirecionar para a página de detalhes.


### Página de Detalhes - Funcionalidades básicas

- Página deverá mostrar os detalhes do repositório clicado.
- Exibir no mínimo os seguintes dados: nome, descrição, email, owner name, avatar url, forks, start, issues, linguagem.
- Na página de detalhes, ao clicar sobre uma issue, deverá abrir uma nova aba do navegador para a página oficial da issue no GitHub. 

## API GitHub

- endpoint consumidos:
`http://api.github.com/users/{USUARIO}`
`http://api.github.com/users/{USUARIO}/repos`


## Entrega

 Ao terminar a prova, envie um email para `desenvolvimento@nolifretes.com.br` com o titulo - DEV-REACT-NATIVE-TESTE contendo o link do github. 
