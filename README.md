<a href="/desafio.pdf" target="_blank">Desafio WorkSquad</a>

## Projeto JSON
Arquivo ``Hunter API.postman_collection.json``

## Observações
- Na nova versão do Postman não é mais possível testar de minuto em minuto na conta free, apenas de hora em hora. 

- A API Hunter só tem um ambiente, com uma URL padrão. Então, tanto ambiente de Desenvolvimento quanto de Testes, utilizam a mesma URL. 

- A integração Postman API agora também é paga.

- A pasta Dados contém arquivos para testes com dados externos.

## Autenticação
https://hunter.io/api-documentation/v2#authentication

## Link da Documentação
https://documenter.getpostman.com/view/12428293/TzeUmoSb#19485ca9-67e9-4a89-8c2f-90c9a779a470

## Para instalar o Newman HTML Reporter Extra
``npm install -g newman-reporter-htmlextra``

## Para rodar o Newman HTML Reporter Extra
``newman run caminho_da_coleção -r htmlextra``
