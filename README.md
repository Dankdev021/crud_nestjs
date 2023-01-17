# crud_nestjs

Install

- npm install

Testes
http://localhost:3000/users (Método POST) - CREATE
Exemplo Json: 
{
    "nome": "Daniel",
    "idade": 20
}

============================================================================================================

http://localhost:3000/users/1 (Método PATCH) - UPDATE
Exemplo Json: 
{
    "nome": "Daniel",
    "idade": 21
}

=============================================================================================================

http://localhost:3000/users (Método GET) - Listagem de todos os usuários

OBS: Para buscar um usuário específico, basta adicionar o ID do usuário após /users
Ex: user/2

=============================================================================================================

http://localhost:3000/users/1 (Método DELETE) - Deleta um usuário





