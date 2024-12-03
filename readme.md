# Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

1. Tabella
   
   ## Tabella: `Used_Cars`
       
|  ID  | BRAND |  MODEL | LICENSE PLATE |  YEAR  | CHASSIS NUMBER | KILOMETERS | PRICE | FUEL_TYPE | TRANSMISSION | COLOR | DESCRIPTION | IMAGE_URL | REGISTRATION_CITY | AVILABLE | HORSEPOWER | WARRANTY | SMOKER'S_VEHICLE | EXHAUST_EMISSIONS | ENGINE_DISPLACEMENT |
|------|-------|--------|---------------|--------|----------------|------------|-------|-----------|--------------|-------|-------------|-----------|-------------------|----------|------------|----------|------------------|-------------------|---------------------|
|      |       |        |               |        |                |            |       |           |              |       |             |           |                   |          |            |          |                  |                   |                     |
|      |       |        |               |        |                |            |       |           |              |       |             |           |                   |          |            |          |                  |                   |                     |
|      |       |        |               |        |                |            |       |           |              |       |             |           |                   |          |            |          |                  |                   |                     |
|      |       |        |               |        |                |            |       |           |              |       |             |           |                   |          |            |          |                  |                   |                     |
|      |       |        |               |        |                |            |       |           |              |       |             |           |                   |          |            |          |                  |                   |                     |




### Tipi di Dato

1. **ID**: `BIGINT` - `PRIMARY KEY`, `AUTO_INCREMENT` (Identificativo univoco dell'auto)
2. **BRAND**: `VARCHAR(50)` - `NOT NULL` (Marca dell'auto )
3. **MODEL**: `VARCHAR(50)` - `NOT NULL` (Modello dell'auto)
4. **LICENSE PLATE**: `VARCHAR(10)` - `UNIQUE`, `NOT NULL` (Targa dell'auto)
5. **YEAR**: `YEAR` - `NOT NULL` (Anno di Immatricolazione dell'auto)
6. **CHASSIS_NUMBER**: `VARCHAR(50)` - `UNIQUE`, `NULL` (Numero di telaio)
7. **KILOMETERS**: `INT` - `NOT NULL` (Kilometraggio dell'auto)
8. **PRICE**: `DECIMAL(10,2)` - `NOT NULL` (Prezzo)
9. **FUEL_TYPE**: `VARCHAR(50) - NULL`  (Tipo di carburante)
10. **TRANSMISSION**: `VARCHAR(10) - NULL` (Tipo di trasmissione)
11. **COLOR**: `VARCHAR(30)` - `NULL` (Colore)
12. **DESCRIPTION**: `TEXT` - `NULL` (Descrizione aggiuntiva)
13. **IMAGE_URL**: `VARCHAR(255)` - `NULL` (Immagine)
14. **REGISTRATION_CITY**: `VARCHAR(50)` (Citta' di immatricolazione)
15. **AVAILABLE**: `TINYINT - DEFAULT(0)` (Disponibilità)
16. **HORSEPOWER**: `SMALL INT - NULL(50)` (Cavalli)
17. **WARRANTY**: `VARCHAR(50)` (Garanzia)
18. **SMOKER'S_VEHICLE**: `DEFAULT(0)` (Veicolo di un fumatore)
19. **EXHAUST_EMISSIONS**: `VARCHAR(20) - NULL` (Tipo di emissioni)
20. **ENGINE_DISPLACEMENT**: `VARCHAR(10)` (Cilindrata)
