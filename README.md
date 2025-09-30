# 🥊 Rinha Backend 2025 - Java + Spring Boot

Bem-vindo ao backend da **Rinha de Clientes**!  
Este projeto simula o gerenciamento de transações financeiras de clientes, com crédito, débito e extrato, implementado em **Java + Spring Boot**, pronto para rodar com **PostgreSQL e Docker**.


## 🔥 Tecnologias
![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Ready-blue)
![Docker](https://img.shields.io/badge/Docker-Ready-lightgrey)

- Java 17  
- Spring Boot 3  
- PostgreSQL  
- Docker + Docker Compose  
- JPA / Hibernate  


## 🎯 Funcionalidades
- `POST /clientes/{id}/transacoes`  
  - Registra **crédito (c)** ou **débito (d)** para um cliente.  
  - Valida saldo e limite de crédito.  
  - Descrição da transação com até **10 caracteres**.  
  - Retorna **saldo e limite atualizados**.

- `GET /clientes/{id}/extrato`  
  - Retorna saldo atual, limite e **últimas 10 transações**.  

## 🛠 Como rodar
Clone o repositório:
```bash
git clone https://github.com/Carlosspjr/Rinha-BackEnd-2025.git
cd Rinha-BackEnd-2025
