# Spring Cloud config server

Centralizando a configuração dos microserviços.

## Visão geral
Na inicialização do microserviço, antes do registro no Eureka server, é feita uma consulta ao servidor de configuração e ao receber os dados de configuração o serviço termina a inicialização registrando-se no Eureka server.

### Dependências
- [Spring Cloud config server](https://cloud.spring.io/spring-cloud-config/reference/html/)

### Conectando microserviços ao servidor de configuração
1. Adicionar a dependência Spring Cloud Config > Config Client
2. Configurar a conexão com o servidor de configuração.
	- No microserviço deve ser criado um arquivo src/main/resources/bootstrap.properties

