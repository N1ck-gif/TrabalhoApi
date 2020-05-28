Projeto sobre o consumo de uma API - SENAI 2020

Ao estudar a API OmdbApi, criei um layout para receber e exibir as informações retiradas de tal api.

API Utilizada - Omdb API;

Layout: O layout criado foi um layout simples, onde o usuário pesquisa um filme indicando o nome e caso queira indica o ano do lançamento, também. Ao realizar a pesquisa, um card desce com as informações do filme pesquisado.

Informações retiradas: As informações retiradas da api foram: Título, Ano, Lançamento, Duração, Gênero, País e Atores. Todas as informações foram retornadas da api em formato JSON.

Funções: Para realizar a api, utilizei uma função assíncrona, onde resgatei o link da api, transformei em uma promisse usando o método fetch() e depois transformei para o formato Json para a retirada e a exibição dos dados.


