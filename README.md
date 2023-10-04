# Database First

## Consegna

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!

### Esercizio

| COLONNA          | TIPO        | ATTRIBUTI            |
| ---------------- | ----------- | -------------------- |
| Chassis          | BIGINT      | PRIMARY KEY          |
| Brand            | VARCHAR(50) | NOTNULL              |
| Model            | VARCHAR(50) | NOTNULL              |
| Displacemenet    | SMALLINT    | UNSIGNED\|NULL       |
| Production Year  | YEAR        | NOTNULL              |
| Price            | MEDIUMINT   | UNSIGNED\|NOTNULL    |
| Number of Owners | TINYINT     | UNSIGNED\|DEFAULT(1) |
| Note             | TEXT        | NULL                 |
| Plate IT         | CHAR(7)     | NOTNULL              |
| Kilometers       | MEDIUMINT   | UNSIGNED\|NOTNULL    |
| Fuel Type        | VARCHAR(25) | NOTNULL              |
| Condition        | TINYINT     | UNSIGNED\|DEFAULT(1) |
