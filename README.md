# Microsserviços em Spring Boot


## Como rodar a aplicação (sem Docker)

1. rode `mvn clean verify -DskipTests` dentro da pasta da aplicação
2. rode `mvn spring-boot:run` dentro de cada pasta pra poder iniciar a aplicação

## Como iniciar a aplicação (com Docker)

1. rode `mvn clean package -DskipTests` pra construir a aplicação com a imagem do Docker localmente
2. rode `docker-compose up -d` pra iniciar a aplicação e PRONTO! :)


