# Quest-o-3
Questão 3 ProvaWEB2

1. npm install express
2. servidor disponivel em "http://localhost:3000".
3. dowload POSTMAN
4. Acesse o Postman:
   Abra o Postman e crie uma nova solicitação.

Rotas Disponíveis
  GET /usuarios
  Obtém todos os usuários.

  GET /usuarios/:id
  Obtém um usuário específico por ID.

  POST /usuarios
  Cria um novo usuário. 
  Envie um corpo JSON com os atributos id, nome, data_nascimento, e email.
  Exemplo:
   Escolha o método POST no menu suspenso ao lado da URL.
   Insira a URL http://localhost:3000/usuarios.
   No menu abaixo da URL, selecione a aba Body.
   Selecione raw e escolha JSON (application/json).
   insira o código a baixo para uma simulação:
  {
    "id": 3,
    "nome": "Novo Usuário",
    "data_nascimento": "10-05-1982",
    "email": "novo_usuario@email.com"
   }
   clique em SEND.
   
  PATCH /usuarios/:id
  Atualiza um usuário existente por ID. Envie um corpo JSON com os atributos que deseja atualizar.

  DELETE /usuarios/:id
  Exclui um usuário por ID.
