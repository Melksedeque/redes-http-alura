# Curso de HTTP usando AluraBooks

Este projeto foi desenvolvido como parte do aprendizado sobre HTTP e protocolos web, utilizando o AluraBooks como modelo. O objetivo foi explorar conceitos fundamentais de comunicação entre cliente e servidor, autenticação, consumo de APIs e integração entre frontend e backend.

## Estrutura do Projeto

O projeto é dividido em duas partes principais:

### Backend: `api-alurabooks`

O backend foi implementado utilizando o `json-server` para simular uma API RESTful e o `jsonwebtoken` para autenticação via JWT. Ele fornece endpoints para operações como registro de usuários, login, e acesso a dados de livros, autores e categorias.

#### Principais funcionalidades:

- **Registro de usuários**: Endpoint para criar novos usuários.
- **Autenticação**: Login com geração de token JWT para autenticar requisições subsequentes.
- **Endpoints públicos**: Dados de lançamentos e mais vendidos disponíveis sem autenticação.
- **Proteção de rotas**: Endpoints protegidos exigem um token válido no cabeçalho da requisição.

#### Como executar:

1. Instale as dependências com `npm install`.
2. Inicie o servidor com `npm run start-auth`.
3. A API estará disponível em `http://localhost:8000`.

### Frontend: `curso-react-alurabooks`

O frontend foi desenvolvido em React com TypeScript, utilizando bibliotecas como `react-router-dom` para navegação e `ds-alurabooks` para componentes estilizados. Ele consome a API fornecida pelo backend para exibir informações de livros, categorias e realizar autenticação.

#### Principais funcionalidades:

- **Página inicial**: Exibe lançamentos, livros mais vendidos e categorias mais buscadas.
- **Busca**: Campo para pesquisar livros.
- **Autenticação**: Integração com a API para login e registro de usuários.
- **Componentização**: Uso de componentes reutilizáveis como banners, botões e modais.

#### Como executar:

1. Instale as dependências com `npm install`.
2. Inicie o projeto com `npm start`.
3. Acesse o frontend em `http://localhost:3000`.

## Tecnologias Utilizadas

- **Backend**: `json-server`, `jsonwebtoken`, `body-parser`.
- **Frontend**: `React`, `TypeScript`, `react-router-dom`, `ds-alurabooks`.

Este projeto foi essencial para consolidar conhecimentos sobre HTTP, integração entre frontend e backend, e boas práticas no desenvolvimento de aplicações web.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](https://github.com/Melksedeque/organo-alura-reactjs?tab=MIT-1-ov-file) para mais detalhes.

## Autor

O Front-end e o Back-end foram criados pela Alura para fins de aprendizado.

- GitHub - [Melksedeque Silva](https://github.com/Melksedeque/)
- FrontEndMentor - [@Melksedeque](https://www.frontendmentor.io/profile/Melksedeque)
- Twitter / X - [@SouzaMelk](https://x.com/SouzaMelk)
- LinkedIn - [Melksedeque Silva](https://www.linkedin.com/in/melksedeque-silva/)
