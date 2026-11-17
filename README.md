# Park API: Spring Boot (em desenvolvimento)

API REST para gerenciar um estacionamento, desenvolvida em **Spring Boot** acompanhando um curso.

## Status
🚧 **Em andamento.** Já tem a entidade `Usuario` (com perfis `ADMIN`/`CLIENTE` e campos de auditoria), a configuração do JPA com MySQL e o fuso horário.

Próximos passos:
- [ ] CRUD de usuários
- [ ] Autenticação com Spring Security + JWT
- [ ] Cadastro de clientes e vagas
- [ ] Check-in e check-out de veículos
- [ ] Documentação com Swagger

## Tecnologias
Java · Spring Boot · Spring Data JPA · MySQL · Lombok · Maven

## Como rodar
1. Crie o banco `demo_park` no MySQL.
2. Defina as variáveis de ambiente `DB_USERNAME` (padrão: `root`) e `DB_PASSWORD`.
3. Execute:
```bash
./mvnw spring-boot:run
```
