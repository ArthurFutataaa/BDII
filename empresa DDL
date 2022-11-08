-- Tabela Departamento
CREATE TABLE Departamento (
Codigo	INT NOT NULL,
 	 Nome	VARCHAR(15) NOT NULL,
  	UF	CHAR(2) NOT NULL,
  	PRIMARY KEY (Codigo));

-- Tabela Empregado
CREATE TABLE IF NOT EXISTS Empregado (
  Matricula 		INT NOT NULL,
  Primeiro_Nome 	VARCHAR(20) NOT NULL,
  Familia_Nome 	VARCHAR(20) NOT NULL,
  Salario 		FLOAT NULL DEFAULT NULL,
  Departamento_Codigo 	INT NULL,
  	PRIMARY KEY (Matricula),
  	CONSTRAINT fk_empregado_departamento
    	FOREIGN KEY (Departamento_Codigo)
    	REFERENCES departamento (Codigo));