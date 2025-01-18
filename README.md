# Agenda de Contatos

Este projeto é uma aplicação web desenvolvida com **Java EE** que implementa uma agenda de contatos, permitindo realizar operações básicas de CRUD (Create, Read, Update e Delete). A aplicação utiliza um banco de dados MySQL e segue o padrão arquitetural **MVC (Model-View-Controller)**.

## Funcionalidades

- Cadastro de contatos
- Listagem de contatos
- Atualização de informações dos contatos
- Exclusão de contatos
- Geração de relatórios em PDF utilizando a biblioteca **iTextpdf**

## Tecnologias Utilizadas

- **Java EE**  
- **Servlets**  
- **JSP (Java Server Pages)**  
- **JDBC (Java Database Connectivity)**  
- **JavaBeans**  
- **DAO (Data Access Object)**  
- Banco de dados: **MySQL**  
- Servidor: **Apache Tomcat**  
- IDE: **Eclipse**  

## Pré-requisitos

- **Java JDK 8** ou superior  
- **MySQL** instalado e configurado  
- **Apache Tomcat 9** ou superior  
- IDE compatível, como o **Eclipse**  

## Configuração do Banco de Dados

1. Crie um banco de dados no MySQL para a aplicação.  
2. Importe o script SQL fornecido na pasta `/sql` para criar as tabelas necessárias.  
3. Configure as credenciais de acesso ao banco de dados no arquivo de configuração do projeto.

## Como Executar

1. Clone este repositório:  
   ```bash
   git clone <URL_DO_REPOSITORIO>
