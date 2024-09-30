# Sistema de Gerenciamento de Propriedades Imobiliárias

## Descrição
Este projeto é um sistema para gerenciar propriedades imobiliárias, permitindo o gerenciamento de propriedades, clientes, agentes e transações. O sistema foi implementado utilizando SQL para criar e manipular um banco de dados.

## Estrutura do Banco de Dados
O banco de dados `ImobiliariaDB` contém as seguintes tabelas:
- **Propriedades**: Armazena informações sobre propriedades (endereço, tipo, valor, status).
- **Clientes**: Armazena detalhes dos clientes (nome, telefone, e-mail, tipo de interesse).
- **Agentes**: Armazena informações sobre agentes imobiliários (nome, telefone, e-mail).
- **Transações**: Registra transações de compra e aluguel, vinculando clientes, agentes e propriedades.

## Funcionalidades
- Criação do banco de dados e tabelas.
- Inserção de dados de exemplo.
- Consultas para listar propriedades disponíveis e transações.
- Atualizações de dados e exclusões.

## Instruções para Uso
1. Execute o script SQL localizado em `src/database.sql` para criar o banco de dados e tabelas.
2. Insira dados de exemplo e execute consultas conforme necessário.

## Tecnologias
- MySQL
