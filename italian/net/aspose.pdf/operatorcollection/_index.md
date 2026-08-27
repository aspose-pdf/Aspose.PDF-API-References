---
title: "Classe OperatorCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.OperatorCollection. La classe rappresenta una collezione di operatori."
type: docs
weight: 7220
url: /it/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

La classe rappresenta una raccolta di operatori

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Restituisce il conteggio degli operatori nella collezione. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indica se la collezione è limitata all'estrazione rapida del testo. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Restituisce un valore che indica se la collezione è di sola lettura. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Restituisce l'operatore in base al suo indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accetta un oggetto visitatore IOperatorSelector per elaborare gli operatori. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Aggiunge alla collezione tutti gli operatori da un'altra collezione. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Aggiunge un nuovo operatore nella collezione. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Aggiunge operatori alla fine degli operatori del contenuto. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento del contenuto. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Rimuove tutti gli operatori dall'elenco. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Restituisce true se la collezione contiene l'operatore specificato. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copia gli operatori nella lista degli operatori. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Elimina gli operatori dalla collezione. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Elimina l'operatore dalla collezione. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Elimina gli operatori dalla collezione. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Esegue le attività definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Restituisce l'enumeratore per la raccolta |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Inserisce gli operatori nella posizione indicata. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Inserisce l'operatore nella raccolta. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Inserisce gli operatori nella posizione indicata. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Rimuove l'operatore dalla raccolta. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Sostituisce gli operatori nella raccolta con altri operatori. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Riprende l'aggiornamento del documento. Aggiorna lo stream dei contenuti nel caso ci siano modifiche in sospeso. Contrassegna tutti gli operatori come "modificati" se il parametro invalidate è true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Sopprime l'aggiornamento dei dati dei contenuti. Lo stream dei contenuti non viene aggiornato finché non viene chiamato ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Restituisce la rappresentazione testuale dell'operatore. |

### Vedi anche

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


