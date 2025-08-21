# Projeto 

# Conceitos abordados

• Sistemas web e recursos </br>
• Cliente/servidor, HTTP, JSON </br>
• Padrão Rest para API web </br>
• Estruturação de projeto Spring Rest • Entidades e ORM </br>
• Database seeding </br>
• Padrão camadas </br>
• Controller, service, repository </br>
• Padrão DTO </br>
• Relacionamentos N-N </br>
• Classe de associação, embedded id </br>
• Consultas SQL no Spring Data JPA </br>
• Projections </br>
• Ambiente local com Docker Compose </br>
• Processo de homologação local • Processo de deploy com CI/CD </br>
• Configuração de CORS </br>

# Modelagem do banco
![preview](./src/main/resources/Images/modelo_de_banco.png)

# Rodando o projeto 

# Ambientes  
```
Altere de ambiente em application.properties

spring.profiles.active=${APP_PROFILE:test}
spring.profiles.active=${APP_PROFILE:dev}
spring.profiles.active=${APP_PROFILE:prod}
```
# Container Dockker (Postgres)
```
acessa a pasta dslist e na raiz rode o comando no terminal
docker-compose up -id 

```

# Consulta banco de dados de teste
http://localhost:8080/h2-console/
spring.datasource.url=jdbc:h2:mem:testdb

# Consulta banco de dados desenvolvimento 
http://localhost:5050/
```
Obs: Apos gerar o arquivo .sql basta rodar o script no postgres 
```
