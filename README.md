- 👋 Hi, I’m @Patriciabispo
- 👀 I-- Criar tabela Funcionários
CREATE TABLE Unidades (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    localizacao VARCHAR(255) NOT NULL
);

-- Criar tabela Funcionários
CREATE TABLE Funcionarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    cargo VARCHAR(100) NOT NULL,
    unidade_id INT,
    FOREIGN KEY (unidade_id) REFERENCES Unidades(id) ON DELETE CASCADE
);

-- Inserir dados na tabela Unidades
INSERT INTO Funcionario (nome, localizacao) VALUES
('Unidade A', 'Rua 1, Bairro A'),
('Unidade B', 'Rua 2, Bairro B');

-- Inserir dados na tabela Funcionários
INSERT INTO Funcionarios (nome, cargo, unidade_id) VALUES
('João Silva', 'Gerente', 1),
('Maria Oliveira', 'Assistente', 1),
('Carlos Pereira', 'Analista', 2);
’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Patriciabispo/Patriciabispo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
