# Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

1. Tabella

    Name : Auto Usate 

       
| ID   |  BRAND | MODEL  | LICENSE PLATE |  YEAR  | CHASSIS NUMBER | KILOMETERS | PRICE | FUEL_TYPE | TRASMISSION | COLOR | DESCRIPTION | IMAGE_URL | REGISTRATION_CITY |
|------|--------|--------|---------------|--------|----------------|------------|-------|-----------|-------------|-------|-------------|-----------|-------------------| 
|      |        |        |               |        |                |            |       |           |             |       |             |           |                   |                  
|      |        |        |               |        |                |            |       |           |             |       |             |           |                   |                  
|      |        |        |               |        |                |            |       |           |             |       |             |           |                   |                  
|      |        |        |               |        |                |            |       |           |             |       |             |           |                   |                  
|      |        |        |               |        |                |            |       |           |             |       |             |           |                   |              


## Tabella: `used_cars`

### Tipi di Dato

1. **ID**: `BIGINT` - `PRIMARY KEY`, `AUTO_INCREMENT`
2. **BRAND**: `VARCHAR(50)` - `NOT NULL`
3. **MODEL**: `VARCHAR(50)` - `NOT NULL`
4. **LICENSE PLATE**: `VARCHAR(20)` - `UNIQUE`, `NOT NULL`
5. **YEAR**: `YEAR` - `NOT NULL`
6. **CHASSIS NUMBER**: `VARCHAR(50)` - `UNIQUE`, `NULL`
7. **KILOMETERS**: `INT` - `NOT NULL`
8. **PRICE**: `DECIMAL(10,2)` - `NOT NULL`
9. **FUEL_TYPE**: 
10. **TRANSMISSION**: 
11. **COLOR**: `VARCHAR(30)` - `NULL`
12. **DESCRIPTION**: `TEXT` - `NULL`
13. **IMAGE_URL**: `VARCHAR(255)` - `NOT NULL`
14. **REGISTRATION_CITY**: `VARCHAR(50)` 
