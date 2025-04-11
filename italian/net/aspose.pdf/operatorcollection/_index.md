---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OperatorCollection. La classe rappresenta una collezione di operatori
type: docs
weight: 7080
url: /it/net/aspose.pdf/operatorcollection/
---
## Classe OperatorCollection

La classe rappresenta una collezione di operatori

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Ottiene il conteggio degli operatori nella collezione. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indica se la collezione è limitata all'estrazione rapida del testo |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Ottiene l'operatore in base al suo indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accetta l'oggetto visitatore IOperatorSelector per elaborare gli operatori. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Aggiunge alla collezione tutti gli operatori da un'altra collezione. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Aggiunge un nuovo operatore nella collezione. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Aggiunge operatori alla fine degli operatori di contenuto. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non dovrebbe generare un aggiornamento dei contenuti. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Rimuove tutti gli operatori dalla lista. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Restituisce true se la collezione contiene l'operatore dato. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copia gli operatori nella lista degli operatori. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Elimina operatori dalla collezione. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Elimina un operatore dalla collezione. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Elimina operatori dalla collezione. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, rilascio o ripristino delle risorse non gestite. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Restituisce l'enumeratore per la collezione |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Inserisce operatori nella posizione data. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Inserisce un operatore nella collezione. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Inserisce operatori nella posizione data. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Rimuove un operatore dalla collezione. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Sostituisce operatori nella collezione con altri operatori. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Riprende l'aggiornamento del documento. Aggiorna il flusso di contenuti nel caso ci siano modifiche in sospeso. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Riprende l'aggiornamento del documento. Aggiorna il flusso di contenuti nel caso ci siano modifiche in sospeso. Segna tutti gli operatori come "cambiati" se il parametro invalidate è true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Sopprime l'aggiornamento dei dati dei contenuti. Il flusso di contenuti non viene aggiornato fino a quando non viene chiamato ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Restituisce la rappresentazione testuale dell'operatore. |

### Vedi Anche

* classe [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)