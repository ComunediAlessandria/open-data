
# Numeri civici

## Descrizione

Il dataset contiene i numeri civici presenti sul territorio del comune.  
E' fornito il file in formato tabellare CSV e in formato geografico GEOJSON.  

Set di caratteri: `UTF-8`  
Separatore di elenco: `;` (punto e virgola)  
Separatore decimale: `.` (punto)  
Delimitatore stringa: `"` (doppio apice)

## Struttura dati

- File CSV:  
  ***CodiceVia***: Codice anagrafico della via, relativo allo stradario dell'ente (INTEGER)  
  ***DUG***: DUG del numero civico (STRING)  
  ***DUF***: DUF del numero civico (STRING)  
  ***CAP***: CAP del numero civico (STRING)  
  ***QuartiereSobborgo***: Quartiere o sobborgo in cui si trova il civico (STRING)  
  ***Civico***: Numero civico (INTEGER)  
  ***Esponente***: Esponenente del numero civico, quando presente (STRING)  
  ***InizioValidita***: Data di inizio validità del civico (DATE ISO 8601)  
  ***SezCensimento***: Sezione di censimento all'interno della quale si trova il numero civico (INTEGER)  
  ***CoordX***: Longitudine del numero civico, SR EPSG:3003 - Monte Mario / Italy zone 1 (DOUBLE)  
  ***CoordY***: Latitudine del numero civico, SR EPSG:3003 - Monte Mario / Italy zone 1 (DOUBLE)  

- File GEOJSON:  
  Contiene le stesse informazione del file CSV ma già in formato geografico.

## Data ultimo aggiornamento

**2025-02-06**

