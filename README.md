# sistema_estacionamento

# Sistema de Controle de Vagas de Estacionamento - WebService REST
Este é um projeto desenvolvido como atividade acadêmica para a disciplina de Programação Web, com foco em BackEnd. O objetivo principal é aplicar os conceitos de WebService REST, utilizando C# com ASP.NET Web API, integrado a um banco de dados relacional.

# Objetivo do Sistema
O sistema tem como finalidade controlar a quantidade de vagas disponíveis em estacionamentos, organizados por cidade, estado e empresa responsável.

# Estrutura do Projeto
O projeto trabalha com 5 entidades principais:
  - Vaga:Representa uma vaga individual dentro de um estacionamento.
  - Estacionamento: Agrupa as vagas e pertence a uma cidade.
  - Cidade: Local onde os estacionamentos estão situados.
  - Estado:Estado correspondente à cidade.
  - Empresa: Empresa responsável pelo gerenciamento do estacionamento.

# DTO (Data Transfer Object)
Para facilitar a comunicação entre o sistema e o cliente (API), o projeto utiliza DTOs que encapsulam os dados essenciais de cada entidade, evitando o acoplamento direto com as entidades do banco.
