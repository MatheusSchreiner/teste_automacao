# Teste de Avaliação Técnica

## Pré-requisitos

- Node.js instalado ([Download Node.js](https://nodejs.org/))
- Cypress (instalação via npm)
- Git

## Como começar

1. Faça um Fork deste projeto.
2. Clone o repositório forkado para o seu ambiente local.
3. Inicie o npm no seu projeto

```bash
npm init -y
```

4. Instale as dependências do Cypress:

```bash
npm install cypress --save-dev
```

## Caso de Teste

1. Executar a request GET https://reqres.in/api/users?page=2
2. Validar que o status code é igual a 200
3. Validar os dados do usuário 12

```json
   {
      "id": 12,
      "email": "rachel.howell@reqres.in",
      "first_name": "Rachel",
      "last_name": "Howell",
      "avatar": "https://reqres.in/img/faces/12-image.jpg"
    }
```

## O que será avaliado

* Lógica de programação
* Organização do código
* Utilização do git
* Domínio das ferramentas

Boa sorte!
