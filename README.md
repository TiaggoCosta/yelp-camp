# Yelp Camp

Projeto do curso The Web Developer Bootcamp - Udemy

## Descrição

Yelp Camp é uma aplicação web que permite aos usuários visualizar, criar e revisar acampamentos. O projeto foi desenvolvido como parte do curso "The Web Developer Bootcamp" da Udemy, ministrado por Colt Steele.

## Funcionalidades

- Cadastro e login de usuários
- Criação, edição e exclusão de acampamentos
- Adição de comentários aos acampamentos
- Pesquisa de acampamentos por localização
- Upload de imagens para os acampamentos

## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Mongoose
- Passport.js (autenticação)
- EJS (template engine)
- Bootstrap (estilização)

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/TiaggoCosta/yelp-camp.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd yelp-camp
    ```
3. Instale as dependências:
    ```bash
    npm install
    ```
4. Configure as variáveis de ambiente:
    - Crie um arquivo `.env` na raiz do projeto e adicione as seguintes variáveis:
        ```properties
        CLOUDINARY_CLOUD_NAME=your_cloud_name
        CLOUDINARY_KEY=your_cloudinary_key
        CLOUDINARY_SECRET=your_cloudinary_secret
        DB_URL=your_mongodb_url
        MAPBOX_TOKEN=your_mapbox_token
        SECRET=your_secret_key
        PORT=3000
        ```

## Uso

1. Inicie o servidor:
    ```bash
    npm start
    ```
2. Abra o navegador e acesse `http://localhost:3000`

## Licença

Este projeto está licenciado sob a licença MIT.
