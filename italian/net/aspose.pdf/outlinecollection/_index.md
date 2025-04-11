---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineCollection. Rappresenta la gerarchia dell'outline del documento
type: docs
weight: 8000
url: /it/net/aspose.pdf/outlinecollection/
---
## Classe OutlineCollection

Rappresenta la gerarchia dell'outline del documento.

```csharp
public sealed class OutlineCollection : Outlines
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Conteggio degli elementi della collezione. Si prega di non confondere con VisibleCount: VisibleCount ottiene il numero di elementi dell'outline visibili a tutti i livelli. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Ottiene un elemento dell'outline che rappresenta il primo elemento di livello superiore nell'outline. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso a questa collezione è sincronizzato (thread safe). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Ottiene un elemento dell'outline dalla collezione per indice. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Ottiene un elemento dell'outline che rappresenta l'ultimo elemento di livello superiore nell'outline. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso a questa collezione. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Il conteggio è la somma del numero di elementi discendenti dell'outline visibili a tutti i livelli. Nota: si prega di non confondere con Count che è il numero di elementi nella collezione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Aggiunge un elemento dell'outline alla collezione. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Pulisce tutti gli elementi dalla collezione. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Controlla se la collezione contiene l'elemento dato. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copia gli elementi dell'outline in un System.Array, a partire da un particolare indice di System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Elimina tutti gli elementi dell'outline dall'outline del documento. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Elimina l'elemento dell'outline con il titolo specificato dall'outline del documento. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Rimuove l'elemento per indice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Genera sempre NotImplementedException |

### Vedi Anche

* classe [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)