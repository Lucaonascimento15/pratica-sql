# Prática de SQL
Anotações de atividades práticas de SQL

-- Exemplo 01  - selecionar tabelas

select * from clientes;

<img width="908" height="431" alt="image" src="https://github.com/user-attachments/assets/124c86f3-4970-4927-a6fd-1a842a93536d" />

-- Exemplo 02 - selecionar colunas específicas

select nome, sobrenome, email from clientes;

<img width="894" height="316" alt="image" src="https://github.com/user-attachments/assets/f388cfca-ab54-415a-9289-9a94cca1273e" />

-- Exemplo 03 - Dar um apelido para a coluna e exibir ele na tabela

select nome as 'Nome', sobrenome as 'Sobrenome', email as 'E-mail' from clientes;

<img width="818" height="222" alt="image" src="https://github.com/user-attachments/assets/72128aae-33bb-4feb-ac00-40cfe7c8b0aa" />

-- Exemplo 04 - colocar um limite na visualização

select * from pedidos limit 10;

<img width="886" height="336" alt="image" src="https://github.com/user-attachments/assets/7bf00072-9734-4782-b0c9-0af2f6fe4de3" />


-- Exemplo 05 - Ordenar colunas em ordem Des e asc

select * from clientes order by nome, sobrenome desc;

<img width="846" height="370" alt="image" src="https://github.com/user-attachments/assets/988f3d34-a366-4cc7-90d1-a656a2a7d693" />

