# TabelaUsuarioPI
DROP TABLE IF EXISTS usuario CASCADE;

CREATE TABLE usuario (
    codUsuario INT PRIMARY KEY NOT NULL AUTO_INCREMENT,
    nomeUsuario VARCHAR(50) NOT NULL,
    emailUsuario VARCHAR(50) NOT NULL,
    anoUsuario VARCHAR (2) NOT NULL,
    serieUsuario VARCHAR(2) NOT NULL,
    senhaUsuario VARCHAR(20) NOT NULL
);

INSERT INTO usuario
 (nomeUsuario, emailUsuario, anoUsuario, serieUsuario, senhaUsuario)
 VALUES
 ('admin','admin@maua.br', '-', '-', 'admin');

 SELECT * FROM usuario
