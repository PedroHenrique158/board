# 📋 Gerenciador de Board de Tarefas (Desafio DIO)

Sistema de gerenciamento de projetos no estilo Kanban, operado via linha de comando (CLI), desenvolvido como parte do desafio prático da DIO.

## 🛠️ Tecnologias Utilizadas
* **Java 17**: Linguagem base do projeto.
* **Gradle 8.5**: Gerenciador de builds e dependências.
* **MySQL**: Banco de dados relacional para persistência de boards e cards.
* **Liquibase**: Gerenciamento de migrações e estrutura do banco de dados.
* **Lombok**: Utilizado para reduzir a verbosidade do código Java.

## 🚀 Desafios e Aprendizados
Este projeto exigiu a resolução de problemas reais de configuração de ambiente, incluindo:
- **Configuração de Banco de Dados**: Ajuste da conexão JDBC para compatibilidade com ambiente XAMPP (usuário root).
- **Troubleshooting de Dependências**: Ajuste das versões do Gradle Wrapper para garantir a correta compilação com o JDK 17.
- **Regras de Negócio**: Implementação e teste de fluxo de estados de cards (Bloqueio, Movimentação e Finalização).

## 🖥️ Como rodar o projeto
1. Clone este repositório.
2. Certifique-se de ter o MySQL (XAMPP) rodando.
3. Configure as credenciais no arquivo `liquibase.properties` e `ConnectionConfig.java`.
4. Execute o comando `./gradlew run` no terminal.