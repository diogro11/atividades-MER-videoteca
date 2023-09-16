# atividades-MER-videoteca
CREATE TABLE Filmes (
    Titulo VARCHAR(255),
    Duracao INT,
    IdiomaOriginal VARCHAR(50),
    Preco DECIMAL(10, 2)
    );
    INSERT INTO Filmes (Titulo, Duracao, IdiomaOriginal, Preco)VALUES ('Aventuras no Tempo', '95 min', 'Espanhol', 8.99);
    INSERT INTO Filmes (Titulo, Duracao, IdiomaOriginal, Preco)VALUES ('Segredos da Floresta Mágica', '120 min', 'russo', 10.75);
    INSERT INTO Filmes (Titulo, Duracao, IdiomaOriginal, Preco)VALUES ('Segredos da Floresta Mágica', '160 min', 'Portugues', 12.75);
    INSERT INTO Filmes (Titulo, Duracao, IdiomaOriginal, Preco)VALUES ('Aventuras no ar', '99 min', 'ingles', 7.99);
    select*from filmes




CREATE TABLE Elenco (
    Nome VARCHAR(100) NOT NULL,
    DataNascimento DATE,
    Nacionalidade VARCHAR(50),
);

INSERT INTO Elenco (Nome, DataNascimento, Nacionalidade, IDFilme)VALUES ('Carlos Rodriguez', '1978-08-20', 'Espanha', 3);
INSERT INTO Elenco (Nome, DataNascimento, Nacionalidade, IDFilme)VALUES ('Sofia Hernandez', '1985-03-05', 'México', 3);
INSERT INTO Elenco (Nome, DataNascimento, Nacionalidade, IDFilme)VALUES ('Marcos Silva', '1993-06-12', 'Brasil', 4);
INSERT INTO Elenco (Nome, DataNascimento, Nacionalidade, IDFilme)VALUES ('Inês Fernandes', '1987-09-18', 'Portugal', 4);
select*from Elenco




