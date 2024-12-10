Projeto Synapse

INFORMAÇÃO IMPORTANTE PARA PRIMEIRO USO DO PROJETO:
- Ao baixar o projeto pela primeira vez, lembre-se de utilizar em seu workbench o código sql (arquivo sql.sql localizado na pasta com.mycompany.SQL).
- Após isto, lembre-se de alterar as informações de conexão com o banco de dados no arquivo ConnectionFactory (localizado em com.mycompany.DAO).

EXEMPLO:

    private String usuario = "root";
    
    private String senha = "root";
    
    private String host = "localhost";
    
    private String porta = "3306";
    
    private String bd = "synapse";"
    
Altere usuário e senha conforme necessário.

OBSERVAÇÃO: O código SQL insere automáticamente um usuário administrador no banco de dados, este usuário será responsável para ter o primeiro acesso a parte de administração do projeto.

Para acessar a parte de administração pela primeira vez utilize na tela de login:

Usuario: *admin.synapse*

Senha: *admin.synapse123*

Após isto você pode inserir novos administradores no banco de dados seguindo os seguintes passos:
Cadastrar > Usuários > Preencha as informações necessárias > Selecione "Cadastrar usuario como admin?" > Cadastrar;

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Membros do grupo:

- Márcio Almeida Barrocal

- Patrick de Melo Freitas Santos
  
- Gabriela Danielly Nascimento
  
- Max Maya Monteiro Pereira
 
- Mateus José Rodrigues Dias

  

