
# Alberi

## Descrizione

Il dataset contiene gli alberi gestiti dal Servizio Verde Pubblico.  
Sono forniti i file in formato tabellare CSV ed in formato geografico GEOPACKAGE  
e le versioni in formato compresso ZIP degli stessi.  

Set di caratteri: `UTF-8`  
Separatore di elenco: `;` (punto e virgola)  
Separatore decimale: `.` (punto)  
Delimitatore stringa: `"` (doppio apice, quando necessario)

## Struttura dati

- File CSV:  
  ***Identificativo***: Numero identificativo dell'albero (INTEGER)  
  ***Tipologia***: Tipologia albero (STRING)  
  ***Essenza***: Essenza albero, quando disponibilie (STRING)  
  ***Disposizione***: Disposizione albero, quando disponibile (STRING)  
  ***Posizione***: Posizionamento sul terreno, quando disponibile (STRING)  
  ***Portamento***: Forma di crescita dell'albero, quando disponibile (STRING)  
  ***EssenzaStorica***: Indica una essenza storica [Si/No] (STRING)  
  ***DataCensimento***: Data di censimento dell'albero (DATE ISO 8601)  
  ***AltezzaPrimoPalco***: Altezza primo palco, in **metri**, quando disponibile (DOUBLE)  
  ***RangeAltezza***: Range di altezza dell'albero, quando disponibile (STRING)  
  ***RangeDiametroFusto***: Range di diametro del fusto, quando disponibile (STRING)  
  ***Suolo***: Tipologia suolo, quando disponibile (STRING)  
  ***StatoVegetativo***: Stato vegetativo dell'albero, quando disponibile (STRING)  
  ***QualitaBiomeccanica***: Qualità biomeccanica, quando disponibile (STRING)  
  ***ClassificazioneCedimento***: Classificazione di Propensione al Cedimento, quando disponibile (STRING)  
  ***Interferenze***: Interferenze radici, quando disponibile (STRING)  
  ***TipoFoglia***: Tipo di foglia, quando disponibile (STRING)  
  ***CoordX***: Longitudine dell'albero, SR EPSG:3003 - Monte Mario / Italy zone 1 (DOUBLE)  
  ***CoordY***: Latitudine dell'albero, SR EPSG:3003 - Monte Mario / Italy zone 1 (DOUBLE)  

- File GPKG:  
  Contiene le stesse informazione del file CSV ma già in formato geografico GEOPACKAGE.

## Frequenza di aggiornamento

_Annuale_

## Data ultimo aggiornamento

**2025-02-06**

