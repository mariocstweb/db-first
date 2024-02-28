nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Colonne | Tipo        | Attributi
---     |---          |---
id      |BIGINT       | NOTNULL
marca   |VARCHAR      |NOTNULL
modello |VARCHAR      |NOTNULL
colore  |VARCHAR      |NOTNULL
km      |MEDIUM INT   |NOTNULL
immatricolazione|DATE|NOTNULL
cambio  |CHAR(1)      |NOTNULL
diesel  |TINYINT/BOOL |NOTNULL,DEFAULT(0)
benzina |TINYINT/BOOL |NOTNULL,DEFAULT(0)
elettrica|TINYINT/BOOL|NOTNULL,DEFAULT(0)
ibrida  |TINYINT/BOOL |NOTNULL,DEFAULT(0)
lunghezza|FLOAT       |NOTNULL
larghezza|FLOAT       |NOTNULL
n°telaio|MEDIUM INT   |NOTNULL
