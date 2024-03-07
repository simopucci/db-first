|    FIELD     |     TYPE     |             ATTRIBUTES             | INDEXES |
| :----------: | :----------: | :--------------------------------: | :-----: |
|      id      |   SMALLINT   | not null - unique - auto_increment |         |
|    marca     | VARCHAR(30)  |              not null              |         |
|   modello    | VARCHAR(50)  |              not null              |         |
|    targa     | VARCHAR(10)  |              not null              |         |
| tipoMacchina | VARCHAR(50)  |  not null - default ('Sportiva')   |         |
|    porte     |   TINYINT    |      not null - default ('3')      |         |
|    prezzo    | DECIMAL(8,2) |              not null              |         |
|      km      |  FLOAT(8,2)  |    not null - default (30.000)     |         |
|   gasolio    | VARCHAR(20)  |              not null              |         |
|    cambio    | VARCHAR(10)  |   not null - default ('Manuale')   |         |
