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


2. Tipo di dato :

-ID | BIGINT - PRIMARY KEY - AUTO_INCREMENT
-BRAND | VARCHAR(50) - NOT NULL
-MODEL | VARCHAR(50) - NOT NULL
-LICENSE PLATE | VARCHAR(20) - UNIQUE - NOT NULL
-YEAR | YEAR - NOT NULL
-CHASSIS NUMBER | VARCHAR(50) - UNIQUE - NULL
-KILOMETERS | INT - NOT NULL
-PRICE | DECIMAL (10,2) - NOT NULL
-FUEL_TYPE | 
-TRASMISSION | 
-COLOR | VARCHAR(30) - NULL
-DESCRIPTION | TEXT - NULL
-IMAGE_URL | VARCHAR(255) - NOT NULL
-REGISTRATION_CITY | VARCHAR  (50)

