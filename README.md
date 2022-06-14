Baixe o arquivo zipado e descompacta os arquivos e basta acessalos e startar eles após as dicas abaixo.

# Como rodar o Front-End

Basta estar dentro na pasta e no terminal do VSCode dar o comando "npm start"

## Como rodar o Back-End

O back-end esta usando a ORM "Sequelize" para fazer a conexão com o banco e criar as tabelas e registrar, atualizar, listar e editar os dados 

Basta estar denrtro na pasta e no terminal do vsCode dar o comando "npm start"

`Segue abaixo as configurações ultilizadas para a ORM estabelercer as devidas conexões`

Dentro da pasta (Models) acesse o arquivo "db.js"

as configurações são: 
const sequelize = new Sequelize('deckcafe', 'root', '123456', {
    host: 'localhost',
    dialect:'mysql'
  });

  Sendo "deckcafe" o nome do banco
  Sendo "root" o usuário que  irá acessar o banco
  sendo "123456" a senha de acesso ao banco
  sendo "mysql" o banco que estará sendo usado
  sendo "localhost" onde se encontra o banco


*OBS => As models e tabelas deverãos ser criadaa sozinhaa ao startar o back-end, caso elas não seja criada sozinho basta executar no comando node do terminal o arquivo "participantes.js" que se encontra na pasta dentro da pasta (Models)  

