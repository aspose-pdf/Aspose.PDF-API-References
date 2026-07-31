---
title: "Classe BaseOperatorCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.BaseOperatorCollection. Rappresenta la classe base per la collezione di operatori"
type: docs
weight: 2940
url: /it/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

Rappresenta la classe base per la raccolta di operatori.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Restituisce il conteggio degli operatori nella collezione. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indica se la collezione è limitata all'estrazione rapida del testo. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Restituisce true se la collezione è di sola lettura. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Restituisce l'operatore in base al suo indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Aggiunge un nuovo operatore nella collezione. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Cancella la collezione. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Verifica se l'operatore esiste nella collezione. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copia gli operatori nella lista degli operatori. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Restituisce l'enumeratore per la raccolta |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Inserisce l'operatore nella raccolta. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Rimuove l'operatore dalla collezione. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Sopprime l'aggiornamento dei dati dei contenuti. Lo stream dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate. |

### Vedi anche

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


