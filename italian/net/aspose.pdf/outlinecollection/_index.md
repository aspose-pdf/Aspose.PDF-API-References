---
title: OutlineCollection
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta la gerarchia del profilo del documento.
type: docs
weight: 5760
url: /it/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Rappresenta la gerarchia del profilo del documento.

```csharp
public sealed class OutlineCollection : Outlines
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count) { get; } | Conteggio di elementi da collezione. Per favore non confondere con VisibleCount: VisibleCount ottiene il numero di elementi di struttura visibili a tutti i livelli. |
| [First](../../aspose.pdf/outlinecollection/first) { get; } | Ottiene un elemento della struttura che rappresenta il primo elemento di primo livello della struttura. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly) { get; } | Ottiene un valore che indica se la raccolta è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized) { get; } | Ottiene un valore che indica se l'accesso a questa raccolta è sincronizzato (thread safe). |
| [Item](../../aspose.pdf/outlinecollection/item) { get; } | Ottiene l'elemento della struttura dalla raccolta per indice. |
| [Last](../../aspose.pdf/outlinecollection/last) { get; } | Ottiene un elemento della struttura che rappresenta l'ultimo elemento di primo livello nella struttura. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso a questa raccolta. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount) { get; } | Conteggio è la somma del numero di elementi di contorno discendenti visibili a tutti i livelli. Nota: per favore non confondere con Count che è il numero se gli articoli sono in collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add)(OutlineItemCollection) | Aggiunge elemento struttura alla raccolta. |
| override [Clear](../../aspose.pdf/outlinecollection/clear)() | Cancella tutti gli elementi dalla raccolta. |
| override [Contains](../../aspose.pdf/outlinecollection/contains)(OutlineItemCollection) | La raccolta contiene un determinato articolo. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto)(OutlineItemCollection[], int) | Copia gli elementi della struttura in un System.Array, a partire da un particolare System.Array index. |
| [Delete](../../aspose.pdf/outlinecollection/delete#delete)() | Elimina tutti gli elementi della struttura dalla struttura del documento. |
| [Delete](../../aspose.pdf/outlinecollection/delete#delete_1)(string) | Elimina l'elemento della struttura con il titolo specificato dalla struttura del documento. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../aspose.pdf/outlinecollection/remove#remove_1)(int) | Rimuovi elemento per indice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove#remove)(OutlineItemCollection) | Lancia sempreNotImplementedException |

### Guarda anche

* class [Outlines](../outlines)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->