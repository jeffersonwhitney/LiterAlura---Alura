# LiterAlura---Alura
Sua biblioteca digital na palma da mão!  Busque livros por título, autor e mais (Gutendex API). Armazene seus favoritos em um banco de dados seguro. Execute no prompt de comando (ideal para desenvolvedores). Comece sua jornada literária agora!


Atualizando o README do Projeto Literalura
Integração com Gutenberg

O README foi atualizado para refletir a API utilizada no projeto Literalura:

API: A API utilizada para buscar informações sobre livros é a Gutendex, uma plataforma online que oferece acesso gratuito a milhares de obras literárias em domínio público, hospedada em https://gutendex.com/.
Instruções de Execução

Para executar o projeto Literalura, siga estas etapas:

1. Clonagem do Repositório:

Clone o repositório do projeto em seu diretório local:
Bash
git clone https://github.com/SEU_USUARIO/Literalura.git

2. Configuração do Banco de Dados:

Acesse o arquivo application.properties e altere as configurações de conexão com o banco de dados PostgreSQL:
Properties
spring.datasource.url=jdbc:postgresql://localhost:5432/Literalura
spring.datasource.username=postgres
spring.datasource.password=${DB_PASSWORD}

Substitua localhost:5432 pelo endereço e porta do seu servidor PostgreSQL.
Substitua postgres pelo nome de usuário do seu banco de dados.
Defina a variável de ambiente DB_PASSWORD com a senha de acesso ao seu banco de dados.

3. Execução do Aplicativo:

Execute o seguinte comando para iniciar a aplicação:
Bash
mvn spring-boot:run

Observações:

Certifique-se de ter o PostgreSQL instalado e configurado em seu sistema.
