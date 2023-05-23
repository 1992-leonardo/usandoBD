# usandoBD

Aqui em baixo eu vou colocar a query de criacao de database. 
-> create database constasMensal;

logo abaixo eu vou colocar a query para criacao da minha tabela. 
  CREATE TABLE contasDoMes (
    mes INT PRIMARY KEY AUTO_INCREMENT,
    agua DECIMAL(10, 2),
    internet DECIMAL(10, 2),
    luz DECIMAL(10, 2),
    cartaoCredito DECIMAL(10, 2)
  );

logo abaixo estou colocando um alter table, caso na hora da digitacao tenha ido alguma letra a mais ou a menos.
  alter table constasDoMes RENAME COLUMN coluna que quero alterar o nome TO novo nome da coluna; 
  
Aqui em baixo eu vou colocar o insert, comando que serve para dar valores as minhas colunas. Existem duas várias formas de se fazer o insert, e eu vou colocar logo abaixo duas formas de se fazer. 
1.  insert into (mes, agua, internet, luz, cartaoCredito) VALUES (5, 50.00, 50.00, 50.00, 50.00);
2.  insert into VALUES (5, 50.00, 50.00, 50.00, 50.00);

A segunda opcao so eh valida, caso queira preencher todas as colunas de uma tabela. 
