# tabla_monedas
crete table and inser into con las monedas (Currency) del mundo 

CREATE TABLE your_name_db.monedas (
  id INT NOT NULL AUTO_INCREMENT,
  cod VARCHAR(45) NULL,
  name VARCHAR(45) NULL,
  PRIMARY KEY (id),
  UNIQUE INDEX id_UNIQUE (id ASC) VISIBLE);

INSERT INTO your_name_db.monedas (cod, name)
VALUE ('USD','Dólar estadounidense'),
	  ('EUR','Euro'),
      ('JPY','Yen japonés'),
      ('GBP','Libra esterlina'),
      ('AUD','Dólar australiano'),
      ('CAD','Dólar canadiense'),
      ('CHF','Franco suizo'),
      ('CNY','Renminbi/yuan chino'),
      ('HKD','Dólar de Hong Kong'),
      ('NZD','Dólar de Nueva Zelanda'),
      ('SEK','Corona sueca'),
      ('KRW','Won surcoreano'),
      ('SGD','Dólar de Singapur'),
      ('NOK','Corona noruega'),
      ('MXN','Peso mexicano'),
      ('INR','Rupia india'),
      ('RUB','Rublo ruso	'),
      ('ZAR','Rand sudafricano'),
      ('TRY','Lira turca'),
      ('BRL','Real brasileño'),
      ('TWD','Nuevo dólar taiwanés'),
      ('DKK','Corona danesa'),
      ('PLN','Zloty polaco'),
      ('THB','Baht tailandés'),
      ('IDR','Rupia indonesia'),
      ('HUF','Florín húngaro'),
      ('CZK','Corona checa'),
      ('ILS','Nuevo shekel israelí'),
      ('CLP','Peso chileno'),
      ('PHP','Peso filipino');
