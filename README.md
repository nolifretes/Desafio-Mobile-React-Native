# React-Native

## Projeto

A proposta deste projeto é criar um app bem simples utilizando React-Native, consumindo a API do GitHub.

**Dependências do projeto:**

* **react-native**: em caso de dúvidas, utilize a documentação oficial https://facebook.github.io/react-native/docs/getting-started
* **react-native-navigation** ou **react-navigation** : em caso de dúvidas, utilize as documentações: https://github.com/wix/react-native-navigation / https://reactnavigation.org/docs/getting-started
* [Axios](https://github.com/axios/axios) - Módulo utilizado para realizar as requisições na API.


* Sinta-se livre para criar a interface.

## Funcionalidades básicas

### Tela inicial

- possuir um campo de busca, para que seja possível digitar um texto aberto. Este valor precisa ser repassado para o endpoint API.
- exibir resultados da consulta da api, mostrando os dados do usuário digitado e listando seus repositórios.
- lista de repositórios deve redirecionar para a tela de detalhes com o clique em um item da lista.

### Tela de Detalhes

- página deve mostrar os detalhes do repositório clicado.
- contendo no mínimo os seguintes dados: nome, descrição, nome do dono e linguagem.

## API GitHub

- endpoint consumidos:
`http://api.github.com/users/{USUARIO}`
`http://api.github.com/users/{USUARIO}/repos`


## Entrega

 Ao terminar a prova, envie um email para `desenvolvimento@nolifretes.com.br` com o titulo - DEV-REACT-TESTE contendo o link do github. 
