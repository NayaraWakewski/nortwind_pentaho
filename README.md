# Data Warehouse para Análise de Vendas da Northwind

## Visão Geral

Este projeto envolve a construção de um Data Warehouse (DW) para a Northwind Traders, uma empresa fictícia de comércio de alimentos e bebidas. Utilizando o Pentaho Data Integration (PDI) para processos ETL (Extract, Transform, Load) e consultas SQL para análises, o projeto visa oferecer insights detalhados sobre as operações de vendas da empresa, incluindo análises de vendas por produto, cliente, região e tendências ao longo do tempo.

## Estrutura do Projeto

O DW é modelado usando um esquema estrela, com tabelas de fato e dimensão projetadas para otimizar consultas analíticas. As principais tabelas incluem:

- **Fato_Orders**: Registra transações de vendas, incluindo informações sobre produtos vendidos, quantidades, preços e descontos.
- **Dim_Cliente**: Detalha informações dos clientes.
- **Dim_Produto**: Inclui informações sobre os produtos.
- **Dim_Regiao**: Armazena dados geográficos relevantes.
- **Dim_Data**: Fornece dimensões de tempo para análise temporal.

## Processo ETL

O processo ETL é realizado através do PDI, envolvendo as seguintes etapas:

1. **Extração**: Dados são extraídos de várias fontes, incluindo bases de dados operacionais da Northwind.
2. **Transformação**: Dados são limpos, transformados e consolidados. Isso inclui a remoção de duplicatas, conversão de tipos de dados e a agregação de informações.
3. **Carga**: Dados transformados são carregados no DW nas tabelas de fato e dimensão apropriadas.

## Análises Realizadas

Foram realizadas várias análises SQL sobre o DW, incluindo:

- Vendas totais por cliente.
- Desempenho de vendas por produto.
- Quantidade de pedidos por funcionário.

Cada análise visa oferecer insights sobre diferentes aspectos das operações de vendas da Northwind, permitindo à empresa tomar decisões informadas para otimizar suas estratégias de negócio.

## Como Usar

Instruções detalhadas sobre como configurar o ambiente, executar o processo ETL no PDI e realizar consultas SQL para análises estão disponíveis nos arquivos do projeto.

## Tecnologias Utilizadas

- Pentaho Data Integration (PDI)
- PostgreSQL
- SQL

