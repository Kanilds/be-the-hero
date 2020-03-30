# Be The Hero

A Semana OmniStack é um workshop online produzido pela Rocketseat. Esta é a versão 11, onde o [Diego Fernandes](https://github.com/diego3g) ensina a desenvolver uma aplicação desde o backend até o frontend e mobile com uma única linguagem, o Javascript. Nome dado a aplicação desenvolvida foi Be The Hero, uma aplicação para cadastro de ONGs e casos cadastrados por elas para que outras pessoas possam ajudar financeiramente.


## :rocket: TECNOLOGIAS
- [Node.js](https://nodejs.org/en/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [React](https://pt-br.reactjs.org/)


# Back-End

Api desenvolvida em NodeJS com acesso a banco de dados relacional = SQLite. Esta api faz uso do Knex.

As rotas para acessar a API estão no arquivo [routes.js](https://github.com/Kanilds/be-the-hero/blob/master/Backend/src/routes.js). Você pode testar as rotas antes de usar o frontend com o software Insomnia. Você só precisa baixar e instalar o Insomnia na sua máquina, e acessar as rotas da aplicação.

# Front-End (Web e Mobile)

Frontend web, desenvolvido em ReactJS. Nesta parte da aplicação, é possível entender diversos conceitos do React e do desenvolvimento web em geral. 

Além disso, é muito importante entender como a página web normalmente se comunica com a API por meio de requisições http, as quais retornam para o frontend como um objeto json. Neste caso, foi utilizado "axios" para realizar a comunicação com a api.


Com isso, a página da aplicação Be The Hero será aberta. Nela, uma ong poderá se cadastrar e cadastrar seus incidentes. A ong também poderá entrar em contato com outras ONGs para poder ajudar nos incidentes delas.

# Mobile

Desenvolvido com o framework React Native e com o Expo para Android/iOS.