Projeto desenvolvido utilizando MySQL para praticar conceitos de banco de dados relacionais.

## Tecnologias

- MySQL
- SQL
- MySQL Workbench

## Funcionalidades

- Criação de banco de dados
- Criação de tabela
- Inserção de registros
- Consulta de dados
- Exclusão de registros
- Aplicação de restrições (PRIMARY KEY, NOT NULL e UNIQUE)

## Estrutura da Tabela

| Campo | Tipo | Restrição |
|---------|---------|---------|
| id | INT | PRIMARY KEY AUTO_INCREMENT |
| Nome | VARCHAR(100) | NOT NULL |
| Idade | INT | NOT NULL |
| Sexo | CHAR(1) | NOT NULL |
| Cpf | VARCHAR(14) | UNIQUE NOT NULL |
| Cidade | VARCHAR(100) | NOT NULL |
| Estado | CHAR(2) | NOT NULL |
| Profissao | VARCHAR(100) | NULL |

## Como executar

1. Execute o script `01_create_sistema_cadastro.sql`
2. Execute o script `02_insert_sistema_cadastro.sql`
3. Execute os scripts de consulta ou exclusão conforme necessário

## Autor

Helton Junior
