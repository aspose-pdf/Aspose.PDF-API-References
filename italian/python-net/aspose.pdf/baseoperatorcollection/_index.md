---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta la classe base per la collezione di operatori."
type: docs
weight: 70
url: /it/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Rappresenta la classe base per la collezione di operatori.

Il tipo BaseOperatorCollection espone i seguenti membri:
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
| suppress_update() | Sopprime l'aggiornamento dei dati dei contenuti.<br/>            Il flusso dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate. |
| resume_update() | Riprende l'aggiornamento del documento.<br/>            Aggiorna il flusso dei contenuti nel caso ci siano modifiche in sospeso. |
| insert(index, op) | Inserisce l'operatore nella collezione. |
| cancel_update() | Annulla l'ultimo aggiornamento.<br/>            Questo metodo può essere chiamato quando la modifica non dovrebbe generare l'aggiornamento dei contenuti. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

