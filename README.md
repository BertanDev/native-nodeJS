# 👾 Native API 👾

Api criada usando apenas funcionalidades nativas no nodeJS e JavaScript, sem o uso de qualquer framework back-end

## ▶️ Testar aplicação
A aplicação não possui nenhuma dependência externa, então basta executar:
```
npm run dev
```
na raiz do projeto

>**Warning**   
> O código foi criado utilizando a versão 18.13.0 do Node, uma versão anterior pode não conter todos os recursos utilizados

## Funcionalidades
A aplicação se resume em um simples CRUD, que realiza operações em um banco de dados físico .json.

Rotas:
- GET```/users``` Lista todos os usuários
- POST```/users``` Cria um novo usuário
- DELETE```/users/:id``` Deleta um usuário
- PUT```/users/:id``` Atualiza as informações do usuário
