# 👾 Native API 👾

Api criada usando apenas funcionalidades nativas no nodeJS e JavaScript, sem o uso de qualquer framework ou biblioteca da linguagem

## ▶️ Testar aplicação
A aplicação não possui nenhuma dependência externa, então basta executar:
```
npm run dev
```
na raiz do projeto

>**Note**   
>A api irá utilizar a porta 3333

>**Warning**   
> O código foi criado utilizando a versão 18.13.0 do Node, versões anteriores podem não conter todos os recursos utilizados
   
<br />
<br />

## 💠 Funcionalidades
A aplicação se resume em um simples CRUD, que realiza operações em um banco de dados físico .json.

Rotas:
- GET ```/users``` Lista todos os usuários
- POST ```/users``` Cria um novo usuário
- DELETE ```/users/:id``` Deleta um usuário
- PUT ```/users/:id``` Atualiza as informações do usuário

> A rota de listagem, pode receber o queryParam ```search``` para filtrar usuários pela string passada na url
