# Mural de Avisos
Criação de API e integração com o front-end para um Mural de Avisos

Pequena API em Node.js com front-end estático para um Mural de Avisos. Projeto usa Express, CORS e body-parser; os dados ficam em memória (arquivo de modelo).

## Requisitos
- Node.js (recomendado >= 18)
- npm

## Instalação
1. Clone ou copie o projeto para sua máquina.
2. Instale dependências:
```sh
npm install
```

## Executando
Inicie o servidor:
```sh
node index.js
```

## Endpoints principais
- GET /api/all — retorna todos os posts

- POST /api/new — adiciona novo post  
  ```json
  {
    "title": "Título",
    "description": "Descrição"
  }
  ```
