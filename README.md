⏱️ Cronômetro em Java

Um cronômetro desenvolvido em Java com conexão a MySQL, criado como parte de um trabalho acadêmico focado em orientação a objetos e banco de dados.

🌟 Funcionalidades
Marcação de tempo com precisão em minutos, segundos e milissegundos.
Armazenamento de registros de tempo no banco de dados MySQL.
🛠️ Tecnologias Utilizadas
Java
MySQL com WampServer
Conector JDBC ( mysql -connector -j -8.3.0 .jar )
🚀 Como Executar o Projeto
Pré-requisitos
Kit de desenvolvimento Java (JDK)
MySQL com WampServer
Conector JDBC (mysql-connector-j-8.3.0.jar)
Passo a Passo
Clonar ou repositório:
bater

Copiar código
git clone https://github.com/eduardoreise/Cronometro.git
Importe o projeto em seu IDE Java de preferência.
Adicione o conector JDBC como JAR externo no projeto.
Configure o banco de dados MySQL com as credenciais corretas e inicie o WampServer.
Execute o projeto diretamente da IDE.
📂 Estrutura do Projeto
texto simples

Copiar código
Cronometro/
├── src/
│   ├── Conectar.java    # Classe para conexão ao banco de dados
│   └── Tela.java        # Interface gráfica do cronômetro
├── lib/
│   └── mysql-connector-j-8.3.0.jar # Dependência JDBC
└── README.md            # Documentação do projeto
📝 Licença
Este projeto está licenciado sob licença MIT.

