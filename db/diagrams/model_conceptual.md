# Diagrama ER - Sistem Preluare Comenzi

```mermaid
erDiagram
    CLIENT ||--o{ COMANDA : "plaseaza"
    CATEGORIE ||--o{ PRODUS : "contine"
    PRODUS ||--o{ DETALII_COMANDA : "este inclus in"
    COMANDA ||--o{ DETALII_COMANDA : "contine"
    COMANDA ||--o| LIVRARE : "genereaza"
    CURIER ||--o{ LIVRARE : "efectueaza"
```
