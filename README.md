# Database First

## Consegna

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

### Esercizio

| COLONNA          | TIPO        | ATTRIBUTI            |
| ---------------- | ----------- | -------------------- |
| chassis          | BIGINT      | PRIMARY KEY          |
| brand            | VARCHAR(50) | NOTNULL              |
| model            | VARCHAR(50) | NOTNULL              |
| displacemenet    | SMALLINT    | UNSIGNED\|NULL       |
| production_year  | YEAR        | NOTNULL              |
| price            | MEDIUMINT   | UNSIGNED\|NOTNULL    |
| number_of_owners | TINYINT     | UNSIGNED\|DEFAULT(1) |
| note             | TEXT        | NULL                 |
| plate_it         | CHAR(7)     | NOTNULL              |
| kilometers       | MEDIUMINT   | UNSIGNED\|NOTNULL    |
| fuel_type        | CHAR(2)     | NOTNULL              |
| condition        | TINYINT     | UNSIGNED\|DEFAULT(1) |
