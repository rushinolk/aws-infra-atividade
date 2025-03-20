# aws-infra-atividade.
Atividade de AWS
Primeiro criei as chaves de segurança da instancia e do RDS com o acesso limitado ao SG do ssh
Depois criei uma instancia Amazon linux com 15gb HD e a SG com SSH
Em seguida criei um banco via RDS e configurei com a SG criada anteriomente
Criei um novo compose para fazer a conexão com o servidor
Configurei o compose com as informações para acessar o banco Via RDS com o endpoint
Subi para a criação do contanier e testado com 'docker logs aws_api'