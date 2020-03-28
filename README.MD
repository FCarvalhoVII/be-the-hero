![](/frontend-react/src/assets/logo.svg)
## Projeto FullStack realizado na **Semana OmniStack da Rocketseat**

### Tecnologias utilizadas na aplicação

O projeto possui backend em **NodeJS**, frontend em **ReactJS** e o mobile em **React Native**. Está sendo utilizado banco de dados SQL para o backend da aplicação, mais especificamente o banco SQLite com o *QueryBuilder* Knex.

Foi utilizado o *framework* Expo na aplicação mobile, para gerar aplicativos nativos tanto para *Android* como para *iOS* usando apenas *JavaScript* e o próprio *React Native*.

Para consumir a API do backend foi utilizado o *Axios*.

### Descrição

Trata-se de uma plataforma integrada baseada em doações, onde uma instituição se cadastra na aplicação (versão web) e pode registrar diversos casos a fim de arrecadar doações para sua causa. No aplicativo mobile os usuários terão acesso aos casos listados pela instituição e poderão por meio do aplicativo entrar em contato com a intituição via *e-mail* ou *WhatsApp* e ajudar ma causa.

### Build

Para rodar a aplicação basta clonar este repositório em sua máquina.
#### Backend - Iniciando o servidor
Entre na pasta ```backend``` e rode o comando ```npm start``` o server estará rodando na porta ```3333``` de sua máquina, com isso você terá acesso ao banco de dados da aplicação.
#### Frontend
Para inicializar o frontend basta utilizar o comando ```npm start``` na pasta ```frontend-react```, a aplicação estará na porta padrão do ReactJS ```3000```. Ao cadastrar uma instituição você receberá um ID (guarde-o), esse ID será usado para fazer o login na aplicação para registrar casos.
#### Mobile
O aplicativo mobile será inicializado com o comando ```npm start``` na pasta ```mobile```, você poderá rodar o app em algum emulador Android ou iOS, no seu próprio celular baixando o aplicativo da Expo e usando o QR Code gerado ao iniciar a aplicação ou até mesmo em seu navegador em [Expo Snack](https://snack.expo.io/).

### Testes

O *framework* escolhido para fazer a realização de testes no backend foi o **Jest**, por sua simplicidade e facilidade de uso. Os testes estão escritos no caminho ```./backend/tests``` onde você encontrará os testes unitários (```/unit```) e de integração (```/integration```).
Para rodar os testes basta utilizar o comando ```npm test``` em seu terminal na pasta ```backend```.