🛒 Central de Compras - Trabalho Interdisciplinar (UNESC)

Este projeto foi desenvolvido como parte do Trabalho Interdisciplinar do curso de Ciência da Computação da UNESC. Trata-se de um ecossistema completo para gestão de compras, conectando lojistas, fornecedores e administradores em uma plataforma centralizada.

A aplicação é dividida em uma arquitetura moderna de microserviços, composta por esta API (Backend) e uma interface de usuário (Frontend).
🚀 Sobre o Projeto

O sistema simula uma central de compras onde:

    Lojistas podem visualizar catálogos e realizar pedidos.

    Fornecedores gerenciam seus produtos, campanhas e condições comerciais.

    Administradores possuem controle total sobre os usuários, categorias e auditoria do sistema.

🛠️ Tecnologias Utilizadas
Backend

    Linguagem: Java 21

    Framework: Spring Boot 3.x

    Segurança: Spring Security + JWT (JSON Web Token) para autenticação.

    Banco de Dados: PostgreSQL (Persistência de dados).

    Mapeamento: MapStruct (para conversão eficiente entre Entidades e DTOs).

    Ferramentas de Build: Maven.

    Containerização: Docker & Docker Compose.

Funcionalidades Principais (API)

    Autenticação Robusta: Login seguro e controle de acesso baseado em perfis (Roles).

    Gestão de Pedidos: Fluxo completo desde a criação até a atualização de status.

    Campanhas de Venda: Sistema para fornecedores criarem condições especiais e campanhas sazonais.

    Catálogo Dinâmico: Organização de produtos por categorias e fornecedores.

📂 Estrutura do Código

A API segue as melhores práticas de desenvolvimento, utilizando:

    Controllers: Endpoints REST organizados por domínio.

    Services: Camada de lógica de negócio isolada.

    Repositories: Interface com o banco de dados via Spring Data JPA.

    DTOs (Data Transfer Objects): Para garantir a segurança e integridade dos dados trafegados na rede.

⚙️ Como Executar
Pré-requisitos

    Java 21

    Maven

    PostgreSQL ou Docker

Passos

    Clone o repositório:
    Bash

git clone https://github.com/seu-usuario/trabalho-interdisciplinar-backend.git
cd trabalho-interdisciplinar-backend/server

Configure o banco de dados: Edite o arquivo src/main/resources/application.properties com as suas credenciais do PostgreSQL.

Rode a aplicação via Maven:
Bash

mvn spring-boot:run

Via Docker (Opcional):
Bash

    docker-compose up --build

💻 Frontend

Este projeto possui uma interface completa desenvolvida em Next.js/React, que se comunica com esta API para oferecer uma experiência de usuário fluida e responsiva.

Você pode encontrar o repositório do Frontend aqui: 👉 https://github.com/Rafaelzzzx/TrabalhoFront

Desenvolvido como projeto acadêmico - UNESC 2024/2025.
