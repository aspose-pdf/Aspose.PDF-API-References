---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.BaseOperatorCollection. Rappresenta la classe base per la collezione di operatori
type: docs
weight: 2830
url: /it/net/aspose.pdf/baseoperatorcollection/
---
## Classe BaseOperatorCollection

Rappresenta la classe base per la collezione di operatori.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Ottiene il conteggio degli operatori nella collezione. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indica se la collezione è limitata all'estrazione rapida del testo |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Restituisce true se la collezione è di sola lettura. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Ottiene l'operatore in base al suo indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Aggiunge un nuovo operatore nella collezione. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento dei contenuti. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Pulisce la collezione. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Controlla se l'operatore esiste nella collezione. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copia gli operatori nella lista degli operatori. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Restituisce l'enumeratore per la collezione |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Inserisce un operatore nella collezione. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Rimuove un operatore dalla collezione. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Riprende l'aggiornamento del documento. Aggiorna il flusso dei contenuti nel caso ci siano modifiche in sospeso. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Sopprime i dati di aggiornamento dei contenuti. Il flusso dei contenuti non viene aggiornato fino a quando non viene chiamato ResumeUpdate. |

### Vedi anche

* classe [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)