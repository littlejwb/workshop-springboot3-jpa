# Projeto Spring Boot e JPA
Este é um projeto de Java que utiliza o framework Spring Boot e as tecnologias JPA/Hibernate, PostgreSQL e H2 para implementar um modelo de domínio completo, com camadas lógicas
de resource, service e repository.

### Visão geral
A aplicação trata de usuários, pedidos, itens de pedidos, produtos e suas categorias, e por último, o pagamento. Através da aplicação
é possível realizar operações CRUD (Create, Read, Update, Delete) nas entidades. O projeto também inclui tratamento de exceções, 
para garantir que a aplicação lide corretamente com situações inesperadas, e o uso de conceitos de relacionamentos one-to-one, one-to-many e many-to-many.

![image](https://user-images.githubusercontent.com/106450118/232925444-c5ade8b1-15a9-44c3-9aad-00065af4634e.png)

### Banco de dados
<p>O projeto utiliza dois bancos de dados: PostgreSQL e H2. </p>
<p>O PostgreSQL é usado para armazenar os dados permanentes, 
enquanto o H2 é utilizado para testes e desenvolvimento local. </p>

### Como executar o projeto
Para executar o projeto, você precisa ter o Java 8 ou superior instalado em seu sistema.
Também é necessário configurar as credenciais do banco de dados PostgreSQL em um arquivo application.properties na pasta src/main/resources.





