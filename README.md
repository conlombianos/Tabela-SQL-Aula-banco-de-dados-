# Tabela-SQL-Aula-banco-de-dados-

-- create
CREATE TABLE jogos (
  nome TEXT NOT NULL,
  preço TEXT NOT NULL,
  ano TEXT NOT NULL
);
 
-- insert
INSERT INTO jogos VALUES ('Persona III', 40.00, 2006);
INSERT INTO jogos VALUES ('Danganronpa', 100.00, 2010);
INSERT INTO jogos VALUES ('Terraria', 15.00, 2011);

-- fetch 
SELECT * FROM jogos;
