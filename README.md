CREATE TABLE IF NOT EXISTS cliente(
  	cliente integer PRIMARY KEY AUTOINCREMENT,
  	nome text NOT NULL,
  	cpf text NOT NULL UNIQUE,
  	cep text NOT NULL,
  	telefone text NOT NULL
 
  );
 
  INSERT INTO cliente (nome,cpf,cep,telefone)
  VALUES
  ('felipe','116.545.654-65','Rua das rosas','45 9970-9876'),
  ('henrique','438.834.384-65','Rua da academia','45 5438-4854');
 
 
   select * FROM cliente;
   
