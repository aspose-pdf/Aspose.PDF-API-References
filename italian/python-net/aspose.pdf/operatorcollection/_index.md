---
title: "OperatorCollection"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "La classe rappresenta una raccolta di operatori"
type: docs
weight: 1010
url: /it/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

La classe rappresenta una raccolta di operatori

Il tipo OperatorCollection espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_fast_text_extraction_mode | Indica se la collezione è limitata all'estrazione rapida del testo |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Ottiene l'operatore per il suo indice. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| insert(index, op) | Inserisce l'operatore nella collezione. |
| insert(at, ops) | Inserisce gli operatori nella posizione indicata. |
| insert(at, ops) | Inserisce l'operatore nella collezione. |
| delete(index) | Elimina l'operatore dalla collezione. |
| delete(ops) | Elimina gli operatori dalla collezione. |
| delete(list) | Nessuno |
| add(ops) | Aggiunge gli operatori alla fine degli operatori dei contenuti. |
| add(ops) | Aggiunge un nuovo operatore alla collezione. |
| suppress_update() | Sopprime l'aggiornamento dei dati dei contenuti.<br/>            Il flusso dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate. |
| resume_update() | Riprende l'aggiornamento del documento.<br/>            Aggiorna il flusso dei contenuti nel caso ci siano modifiche in sospeso. |
| cancel_update() | Annulla l'ultimo aggiornamento.<br/>            Questo metodo può essere chiamato quando la modifica non dovrebbe generare l'aggiornamento dei contenuti. |
| accept(visitor) | Accetta l'oggetto visitatore IOperatorSelector per elaborare gli operatori. |
| replace(operators) | Sostituisci gli operatori nella collezione con altri operatori. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

