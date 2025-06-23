# 🛠️ Sistema de Manutenção Corretiva e Preventiva

## 👨‍💻 Desenvolvedor

- **Nome:** Lucas Vitali Manenis  
- **Curso:** Engenharia de Software – 3ª fase  
- **Instituição:** [SATC - Sociedade Assistência aos Trabalhadores do Carvão]  
- **Período:** 2025

- **Nome:** Luiz Fillipy Vefago Binatti
- **Curso:** Engenharia de Software – 3ª fase  
- **Instituição:** [SATC - Sociedade Assistência aos Trabalhadores do Carvão]
- **Período:** 2025 

## 📋 Escopo do Projeto

Este projeto tem como objetivo o desenvolvimento de um banco de dados relacional para um sistema de gestão de manutenções em equipamentos industriais. O sistema contempla tanto manutenções **corretivas** quanto **preventivas**, além de registrar falhas, orçamentos, peças utilizadas e o histórico técnico dos serviços.

O banco de dados permite:
- Cadastro e gerenciamento de **equipamentos** e **técnicos**.
- Registro de **manutenções**, **falhas**, **orçamentos** e **peças**.
- Consulta de **histórico preventivo** de cada equipamento.
- Associação com **fornecedores** de peças e serviços.

## ⚙️ Tecnologias Utilizadas

- **pgAdmin 4** – Sistema de gerenciamento de banco de dados relacional.
- **SQL** – Linguagem para criação de tabelas, relacionamentos e scripts de manipulação de dados.
- **PgAdmin 4** – Interface gráfica para administração do banco de dados.
- **Java** – Para construção do CRUD de interação.
- **Insomnia** - Utilizado para realizar as requisições.
 
## 📌 Estrutura do Projeto

- Diagrama do Modelo Físico (ER → Físico).
- Script de Criação do Banco de Dados.
- Script de Inserção de Dados (mínimo 10 registros por tabela).
- 3 Functions/Procedures, 1 Trigger, 3 Views e Índices otimizados.
- Justificativa técnica para os objetos do banco.
- CRUD de interação com as tabelas principais.
- Arquivo com presset de requisições.

## 🗃️ Entidades do Sistema

- `equipamento`
- `manutencao`
- `tecnico`
- `peca`
- `registro_falha`
- `historico_preventivo`
- `fornecedor`
- `orcamento`
