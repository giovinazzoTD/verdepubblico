# Dataset Open Data - Comune di Giovinazzo

## Descrizione
Questo dataset contiene informazioni dettagliate sulle alberature e le operazioni di manutenzione del verde pubblico nel Comune di Giovinazzo. Include dettagli su specie arboree, numero di alberi presenti e attività di piantumazione, sostituzione e potatura svolte negli anni. Inoltre, offre una classificazione delle tipologie di alberi e delle aree urbane in cui sono situati.

## Colonne del Dataset
- **anno**: Anno di riferimento per l'intervento o il censimento.
- **particella**: Identificativo della particella su cui è stato effettuato l'intervento.
- **sito**: Nome dell'area o della zona in cui sono presenti le alberature.
- **categoria_sito**: Classificazione dell'area in base al tipo di sito (Cimitero, Strade, Piazze, Lungomare, Aree Mercatali, Parchi, ecc.).
- **specie**: Nome della specie arborea.
- **categoria_albero**: Classificazione dell'albero in base alla sua tipologia (Latifoglie caducifoglie, Latifoglie sempreverdi, Conifere, Palme, Arbusti ornamentali, Alberi da frutto, Alberi esotici e tropicali, Altro).
- **numero_alberi**: Numero di alberi censiti o coinvolti nelle operazioni.
- **tipo_intervento**: Tipologia di intervento effettuato sull’albero (Nuova piantumazione, Sostituzione, Potatura e manutenzione, Non specificato).

## Operazioni di Pre-elaborazione
1. Rinominazione colonne per maggiore chiarezza e coerenza con gli standard open data.
2. Standardizzazione dei valori mancanti nelle colonne categoriali, sostituendoli con "Non specificato".
3. Conversione dei dati numerici nelle colonne "anno" e "numero_alberi" per garantire coerenza nei tipi di dati.
4. Rimozione di spazi extra nelle stringhe per uniformare la formattazione.
5. Creazione della colonna "tipo_intervento" per semplificare l'interpretazione delle operazioni svolte.
6. Creazione della colonna "categoria_albero" per categorizzare gli alberi in base alla loro tipologia botanica.
7. Creazione della colonna "categoria_sito" per classificare le zone in base alla loro destinazione d'uso.

## Fonte
**Comune di Giovinazzo - Settore Verde Pubblico**

## Licenza
Questo dataset è rilasciato sotto licenza **CC-BY 4.0**.

## Periodo di Riferimento
**Dati aggiornati al 2023**

## Formato
**CSV**

## Autore
**Comune di Giovinazzo**
