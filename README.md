CREATE TABLE IF NOT EXISTS cliente(
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  nome TEXT NOT NULL,
  telefone TEXT NOT NULL,
  cpf TEXT NOT NULL UNIQUE
  );
  /*
  INSERT INTO cliente (nome, telefone, cpf)
  VALUES
  /*
  ('Luís','459999999', '000.000.000.02');
  SELECT * FROM cliente;
