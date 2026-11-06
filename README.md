# Sistema de Vendas – ETEC

## Sobre o projeto

Este projeto foi desenvolvido como atividade prática da disciplina de Banco de Dados II, da ETEC – Centro Paula Souza.

O sistema utiliza PHP e MySQL para realizar a conexão com o banco de dados e exibir uma lista de produtos cadastrados.

## Tecnologias utilizadas

- PHP
- MySQL 8
- HTML5
- CSS3
- MySQLi

## Estrutura do projeto

```text
Sistema-de-Vendas/
│
├── fisico.sql
├── conexao.php
├── index.php
└── README.md
```

## Banco de dados

Nome do banco: `db_sistema_vendas`

O banco possui as seguintes tabelas:

- `tbl_clientes`: armazena os dados dos clientes.
- `tbl_vendedores`: armazena os vendedores e suas comissões.
- `tbl_produtos`: armazena os produtos, preços e quantidades.
- `tbl_pedidos`: armazena os pedidos realizados.
- `tbl_categorias`: armazena as categorias dos produtos.

## Funcionalidades

- Conexão com o banco de dados MySQL.
- Consulta de produtos utilizando SELECT.
- Relacionamento entre produtos e categorias utilizando INNER JOIN.
- Exibição do código, nome, categoria, preço e quantidade dos produtos.
- Organização dos produtos pelo ID.

## Como executar o projeto

1. Instale o XAMPP.
2. Inicie o Apache e o MySQL.
3. Acesse o phpMyAdmin.
4. Importe o arquivo `fisico.sql`.
5. Coloque os arquivos PHP na pasta `htdocs`.
6. Confira as configurações de conexão no arquivo `conexao.php`.
7. Abra o navegador e acesse:

```text
http://localhost/Sistema-de-Vendas/
```

## Objetivo

Aplicar na prática os conhecimentos de banco de dados, comandos SQL, relacionamentos entre tabelas e integração entre PHP e MySQL.

## Instituição

ETEC – Centro Paula Souza

**Disciplina:** Banco de Dados II

**Projeto:** Sistema de Vendas
