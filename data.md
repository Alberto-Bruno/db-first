
Struttura di una tabella per tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.



AUTO|TYPES|INDICI|ATTRIBUTI
-------|-----|------|--------|
ID|BIGINT|PRIMARY KEY|NOT NULL, UNIQUE, AUTO_INCREMENT|
Marca|INT|           |NOT NULL|
Modello|VARCHAR(30)|       |NOT NULL|
Nome Brand|VARCHAR(50)|     |NOT NULL|
Peso-Potenza|VARCHAR(4)|    |NOT NULL|
Trazione|CHAR(5)|           |NOT NULL|
Cambio|CHAR(1)|             |NOT NULL|
Tipo_Aliment|VARCHAR(6)|   |NOT NULL|
Consumo Medio|VARCHAR(3)|   |NULL    |
KM|MEDIUMMINT|              |NOT NULL|
Immatricolazione|DATETIME|     |NOT NULL|
Produzione|YEAR|            |NOT NULL|
Prezzo-Acq|FLOAT(8,2)|      |NULL    |
Prezo-Vend|FLOAT(8,2)|      |NOT NULL|
Targa|CHAR(7)|              |NOT NULL UNIQUE|
N-porte|CHAR(1)|            |NOT NULL|
Cap-Bagaglio|CHAR(2)|       |NULL    |
Clima|TINYINT(1)|           |NOT NULL, DEFAULT = 1|
Colore|VARCHAR(10)|         |NOT NULL, DEFAULT = 0|
Disponibilità|TINYINT(1)|   |NOT NULL, DEFAULT = 1|

