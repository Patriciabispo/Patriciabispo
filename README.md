- 👋 Hi, I’m @Patriciabispo
- 👀 I-- Criar tabela de Funcionários
CREATE TABLE Unidades (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    localizacao VARCHAR(255) NOT NULL
);

-- Criar tabela de Funcionários
CREATE TABLE Funcionarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    cargo VARCHAR(100) NOT NULL,
    unidade_id INT,
    FOREIGN KEY (unidade_id) REFERENCES Unidades(id) ON DELETE CASCADE
);

-- Inserir dados na tabela Unidades
INSERT INTO Unidade (Tudo gostoso) VALUES
(Tudo gostoso, Av. Paulista 2295 , São Paulo, Bela Vista'),



CREATE TABLE Funcionarios (
    FuncionarioID INT PRIMARY KEY AUTO_INCREMENT,
    Unidade Bela Vista ID INT,
    Nome João VARCHAR(100) NOT NULL,
    Cargo Gerente/Chef. VARCHAR(50),
    Telefone (11)98456-0983VARCHAR(15),
    HorarioEntrada 11🕥TIME,
    HorarioSaida 19:00TIME,
    Salario DECIMAL(6.000,00);
    FOREIGN KEY (UnidadeID) REFERENCES Unidades(UnidadeID)
  
  CREATE TABLE Funcionarios
    FuncionarioID INT PRIMARY KEY AUTO_INCREMENT,
    Unidade Bela Vista ID INT,
    Nome Rodrigo VARCHAR(100) NOT NULL,
    Cargo Garçom VARCHAR(50),
    Telefone (11)99346-2909 VARCHAR(15),
    HorarioEntrada 11🕥TIME,
    HorarioSaida 19:00TIME,
    Salario DECIMAL(2.500,00);
    FOREIGN KEY (UnidadeID) REFERENCES Unidades(UnidadeID)
);
CREATE TABLE Funcionarios
    FuncionarioID INT PRIMARY KEY AUTO_INCREMENT,
    Unidade Bela Vista ID INT,
    Nome Maria VARCHAR(100) NOT NULL,
    Cargo Auxiliar de Cozinha VARCHAR(50),
    Telefone (11)98730-1545 VARCHAR(15),
    HorarioEntrada 11🕥TIME,
    HorarioSaida 19:00TIME,
    Salario DECIMAL(2.500,00);
    FOREIGN KEY (UnidadeID) REFERENCES Unidades(UnidadeID)
);
CREATE TABLE Funcionarios
    FuncionarioID INT PRIMARY KEY AUTO_INCREMENT,
    Unidade Bela Vista ID INT,
    Nome Lucas VARCHAR(100) NOT NULL,
    Cargo Barman VARCHAR(50),
    Telefone (11)97656-3759 VARCHAR(15),
    HorarioEntrada 11🕥TIME,
    HorarioSaida 19:00TIME,
    Salario DECIMAL(2.000,00);
    FOREIGN KEY (UnidadeID) REFERENCES Unidades(UnidadeID)
);
CREATE TABLE Funcionarios
    FuncionarioID INT PRIMARY KEY AUTO_INCREMENT,
    Unidade Bela Vista ID INT,
    Nome Allana VARCHAR(100) NOT NULL,
    Cargo Auxiliar de limpeza VARCHAR(50),
    Telefone (11)97656-3759 VARCHAR(15),
    HorarioEntrada 11🕥TIME,
    HorarioSaida 19:00TIME,
    Salario DECIMAL(1.800,00);
    FOREIGN KEY (UnidadeID) REFERENCES Unidades(UnidadeID)
);

<!---
Patriciabispo/Patriciabispo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
