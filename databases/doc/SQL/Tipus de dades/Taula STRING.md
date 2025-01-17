
| CADENA                   | DEF                                                                                                                                                                                                                                                           | TAMANY                                               |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| CHAR (N)                 | Cadena de caràcters de longitud fixe. Longitud de 1 a 255 caràcters. Per defecte la longitud és 1                                                                                                                                                             | 1 byte per caràcter                                  |
| VARCHAR (N)              | Cadena de caràcters de longitud variable. Longitud de 1 a 255 caràcters.                                                                                                                                                                                      | Només es guarda la informació dels caràcters ocupats |
| BLOB, TEXT               | Camp amb una longitud de fins a 65.535 caràcters. BLOBs són "Binary Large Objects" i s'utilitzen per guardar informació binària com imatges, fitxers,... Els TEXT són per guardar text de longitud variable que faci distinció entre majúscules i minúscules. |                                                      |
| TINYBLOB or TINYTEXT     | A BLOB or TEXT amb un màxim de 255 caràcters                                                                                                                                                                                                                  |                                                      |
| MEDIUMBLOB or MEDIUMTEXT | A BLOB or TEXT amb un màxim de 16.777.215                                                                                                                                                                                                                     |                                                      |
| LONGBLOB or LONGTEXT     | A BLOB or TEXT amb un màxim de 4.294.967.295                                                                                                                                                                                                                  |                                                      |
| ENUM                     | Una enumeració, el camp pren el valor d'una llista de valors possibles. Per exemple ENUM(‘A','B','C')                                                                                                                                                         | 65.535 membres (1 o 2 bytes)                         |