# Flyway + Spring Boot — end-to-end demo

A tiny "library" app whose **schema is owned entirely by Flyway SQL migrations**.
Hibernate is set to `ddl-auto=validate`, so it only checks that the JPA entities
match the schema the migrations produced — it never creates or alters tables.

Spring Boot 4.1.0 · Java 17 · H2 (zero setup) · Flyway.

## Run it
