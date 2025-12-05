# API_POO

Sistema de Pedidos Online (API)

Projeto desenvolvido em Java com Spring Boot, JPA, MySQL e Swagger.


Funcionalidades:

	- CRUD de Clientes  
	- CRUD de Produtos  
	- CRUD de Pedidos (pedido → 1 cliente, 1 produto)

Estrutura do Projeto:

	src/main/java/com/vendas
	├── controller
	├── service
	├── repository
	├── model
	└── Main.java

Como rodar o projeto:

	1. Configure o MySQL
	2. Ajuste `application.properties`
	3. Rode a classe `Main` via Spring Boot

Swagger:

	- Após executar:
		http://localhost:8080/swagger-ui.html
	
Script SQL:
	disponível na pasta `/database`
