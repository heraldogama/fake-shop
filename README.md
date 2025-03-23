# Fake Shop

Esta aplicação tem por objetivo a prática nos processos de criação e deploy em Cloud. Utilizando técnicas de DevOps com as tecnologias: Docker, Kubernetes e CI/CD; Usando o Github Actions.

- Declaramos o arquivo Dockerfile em nosso projeto para criarmos uma imagem no DockerHub;
- Criamos nosso manifesto YAML para a ação de criação do nosso cluster Kubernetes, onde utilizamos a Digital Ocean como host;
- Por fim criamos nosso processo de integração contínua no GitHub.

## Variável de Ambiente

DB_HOST => Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD => Senha do usuário do banco de dados PostgreSQL.

DB_NAME => Nome do banco de dados PostgreSQL.

DB_PORT => Porta de conexão com o banco de dados PostgreSQL.
