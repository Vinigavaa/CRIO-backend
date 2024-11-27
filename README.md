# CRIO Backend

## Descrição:
O **CRIO** é um sistema de gerenciamento de agendamento de eventos e publicação de conteúdos. O backend da aplicação é desenvolvido em **Spring (Java)** e fornece uma API RESTful para gerenciar eventos, usuários, e entidades parceiras, além de permitir a publicação de novidades em um sistema de blog.

## Funcionalidades:
- **Gerenciamento de Eventos**: Cadastro, edição e exclusão de eventos com validação de conflitos de horários.
- **Notificações**: Envio de notificações por e-mail sobre eventos futuros.
- **Sistema de Blog**: Publicação de novidades e conteúdos.
- **Gerenciamento de Usuários**: Controle de acesso e gerenciamento de usuários do sistema.
- **Cadastro de Entidades Parceiras**: Registro e gestão de entidades parceiras.

## Tecnologias Utilizadas:
- **Spring Boot**: Framework Java para construção da API.
- **H2 Database**: Banco de dados relacional em memória para desenvolvimento.
- **Maven**: Gerenciador de dependências do Java.

## Pré-requisitos:
- **Java** >= 17
- **Maven**
- **Postman** (opcional, para testes de API)

## Instalação:
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/crio-backend.git
   cd crio-backend
