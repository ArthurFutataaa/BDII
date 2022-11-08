-- Listar o nome e o salario dos empregados acrescidos de R$50,00

-- nao adiciona no bando, somente na tela
select Primeiro_Nome, Salario + 50.00
from empregado;

-- ultilizar ALIAS (apelido)
-- uma nova coluna (temporaria) com os valores
select Primeiro_Nome, Salario + 50.00 as Novo_Salario
from Empregado;

-- listar o nome e o salario dos empregados decrecidos de R$50,00
select Primeiro_Nome, Salario - 50.00 as Novo_Salario
from Empregado;

-- listar o nome e o salario dos emprgados acrescidos 10%
select Primeiro_Nome, truncate( Salario *1.1, 2) as Novo_Salario
from Empregado;

-- lisatr o nome e a metade do salario dos empregados 
select Primeiro_Nome, truncate(salario / 2, 2) as Novo_Salario
from Empregado;

-- Sempre arredonda pra cima
-- ROUND (15.654, 2) = 15.65
-- ROUND (15.655, 2) = 15.66

-- Mantem o mesmio numero
-- TRUNCATE (15.654, 2) = 15.65
-- TRUNCATE (15.655, 2) = 15.65

-- listar o nome e salrio dos empregados cujo salario seja divisivio po 3.

-- MOD %
select Primeiro_Nome, Salario
from Empregado
where Salario % 3 = 0;
