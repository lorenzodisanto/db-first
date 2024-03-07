# Primo DB

nome repo: `db-first`

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Svolgimento

| FIELD           | TYPE        | ATTRIBUTES         | INDEXES     |
| --------------- | ----------- | ------------------ | ----------- |
| id              | INT         | AUTO INCREMENT     | PRIMARY KEY |
| brand           | VARCHAR(50) | NOT NULL           |             |
| model           | VARCHAR(50) | NOT NULL           |             |
| year_production | YEAR        | NOT NULL           |             |
| km_count        | MEDIUMINT   | NOT NULL, UNSIGNED |             |
| fuel            | VARCHAR(30) | NOT NULL           |             |
| displacement    | VARCHAR(10) | NOT NULL           |             |
| power           | VARCHAR(6)  | NOT NULL           |             |
| transmission    | VARCHAR(30) | NOT NULL           |             |
| traction        | VARCHAR(30) | NOT NULL           |             |
| number_seats    | TINYINT     | NULL, UNSIGNED     |             |
| numero_doors    | TINYINT     | NOT NULL, UNSIGNED |             |
| price           | FLOAT(8, 2) | NOT NULL, UNSIGNED |             |
| note            | TEXT        | NULL               |             |
