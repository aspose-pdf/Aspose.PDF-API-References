---
title: OperatorCollection
second_title: Aspose.PDF per .NET API Reference
description: La classe rappresenta la raccolta di operatori
type: docs
weight: 4860
url: /it/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

La classe rappresenta la raccolta di operatori

```csharp
public class OperatorCollection : BaseOperatorCollection
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count) { get; } | Ottiene il conteggio degli operatori nella raccolta. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode) { get; } | Indica che la raccolta è limitata all'estrazione rapida del testo |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| override [Item](../../aspose.pdf/operatorcollection/item) { get; set; } | Ottiene l'operatore in base al suo indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept)(IOperatorSelector) | Accetta l'oggetto visitatore IOperatorSelector per elaborare gli operatori. |
| [Add](../../aspose.pdf/operatorcollection/add#add_2)(ICollection&lt;Operator&gt;) | Aggiunge alla raccolta tutti gli operatori di altre raccolte. |
| override [Add](../../aspose.pdf/operatorcollection/add#add)(Operator) | Aggiunge un nuovo operatore alla raccolta. |
| [Add](../../aspose.pdf/operatorcollection/add#add_1)(Operator[]) | Aggiungi operatori alla fine dei contenuti operatori. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate)() | Annulla l'ultimo aggiornamento. Questo metodo può essere chiamato quando la modifica non deve generare l'aggiornamento dei contenuti. |
| override [Clear](../../aspose.pdf/operatorcollection/clear)() | Rimuove tutti gli operatori dall'elenco. |
| override [Contains](../../aspose.pdf/operatorcollection/contains)(Operator) | Restituisce true se la raccolta contiene un determinato operatore. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto)(Operator[], int) | Copia gli operatori nell'elenco degli operatori. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete_2)(IList&lt;Operator&gt;) | Elimina gli operatori dalla raccolta. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete_1)(int) | Elimina l'operatore dalla raccolta. |
| [Delete](../../aspose.pdf/operatorcollection/delete#delete)(Operator[]) | Elimina gli operatori dalla raccolta. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator)() | Restituisce l'enumeratore per la raccolta |
| [Insert](../../aspose.pdf/operatorcollection/insert#insert_2)(int, IList&lt;Operator&gt;) | Inserisce gli operatori nella posizione data. |
| override [Insert](../../aspose.pdf/operatorcollection/insert#insert)(int, Operator) | Inserisce l'operatore nella raccolta. |
| [Insert](../../aspose.pdf/operatorcollection/insert#insert_1)(int, Operator[]) | Inserisce gli operatori nella posizione data. |
| override [Remove](../../aspose.pdf/operatorcollection/remove)(Operator) | Rimuovi l'operatore dalla raccolta. |
| [Replace](../../aspose.pdf/operatorcollection/replace)(IList&lt;Operator&gt;) | Sostituisci gli operatori nella raccolta con altri operatori. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate)() | Riprende l'aggiornamento del documento. Aggiorna il flusso di contenuti in caso di modifiche in sospeso. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate)() | Sopprime i dati dei contenuti di aggiornamento. Il flusso di contenuti non viene aggiornato finché non viene chiamato ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring)() | Restituisce la rappresentazione testuale dell'operatore. |

### Guarda anche

* class [BaseOperatorCollection](../baseoperatorcollection)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
