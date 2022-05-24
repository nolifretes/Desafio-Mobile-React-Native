# React-Native

## Projeto

A proposta deste projeto é criar um app bem simples utilizando React-Native, consumindo a API do GitHub.

**Dependências do projeto:**

* **react-native**: em caso de dúvidas, utilize a documentação oficial https://facebook.github.io/react-native/docs/getting-started
* **react-native-navigation** ou **react-navigation** : em caso de dúvidas, utilize as documentações: https://github.com/wix/react-native-navigation / https://reactnavigation.org/docs/getting-started
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para criar a interface, e implementar demais funcionalidades.

## Funcionalidades básicas (obrigarório)

### Tela inicial

- Possuir um campo de busca, para que seja possível digitar o nome de um usuário. Este valor precisa ser repassado para o endpoint API.
- Exibir resultados da consulta da api, mostrando os dados do usuário digitado e listando seus repositórios.
- Ao clicar em um repositório na lista, a aplicação deverá redirecionar para a página de detalhes.

### Tela de Detalhes

- Página deverá mostrar os detalhes do repositório clicado.
- Exibir ao mnenos os seguintes dados: nome, descrição, owner login, avatar url, issues, linguagem.
- Na página de detalhes, ao clicar sobre uma issue, deverá abrir (uma página aba do navegador fora do app ou uma webview) para a página oficial da issue no GitHub.

## API GitHub

- Endpoints que podem auxiliar na tarefa:
`http://api.github.com/users/{user}/repos`
`http://api.github.com/repos/{owner}/{repo}`
`https://api.github.com/repos/${repo}/issues`


## Entrega

 Ao terminar a prova, envie um email para `desenvolvimento@nolifretes.com.br` com o titulo - DEV-RN-DESAFIO contendo o link do github. 
