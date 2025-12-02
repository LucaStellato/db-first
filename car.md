# DB CAR

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# table name : car

Columns:

- id PK NOT NULL INT AUTO_INCREMENT
- marca VARCHAR(50) NOT NULL 
- modello VARCHAR(50) NOT NULL 
- anno di costruzione YEAR NOT NULL
- anno di immatricolazione YEAR NOT NULL
- telaio INT NOT NULL
- colore VARCHAR(50) NULL
- optional TEXT ?NULL
- provenienza VARCHAR(60) NULL
- cilindrata INT NOT NULL
- alimentazione VARCHAR(30) NOT NULL
- chilometraggio INT NOT NULL
- cambio VARCHAR(30) NOT NULL
- prezzo INT NOT NULL
- descrizione TEXT