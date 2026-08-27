---
title: "Classe OutlineCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.OutlineCollection. Rappresenta la gerarchia della struttura del documento"
type: docs
weight: 8140
url: /it/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Rappresenta la gerarchia della struttura del documento.

```csharp
public sealed class OutlineCollection : Outlines
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Conteggio degli elementi della raccolta. Per favore non confondere con VisibleCount: VisibleCount restituisce il numero di elementi della struttura visibili a tutti i livelli. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Ottiene un elemento della struttura che rappresenta il primo elemento di livello superiore nella struttura. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Restituisce un valore che indica se la collezione è di sola lettura. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Ottiene un valore che indica se l'accesso a questa raccolta è sincronizzato (thread-safe). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Ottiene un elemento della struttura dalla raccolta per indice. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Ottiene un elemento della struttura che rappresenta l'ultimo elemento di livello superiore nella struttura. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Ottiene un oggetto che può essere usato per sincronizzare l'accesso a questa raccolta. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Il conteggio è la somma del numero di elementi discendenti della struttura visibili a tutti i livelli. Nota: per favore non confondere con Count, che è il numero di elementi nella raccolta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Aggiunge un elemento di contorno alla raccolta. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Cancella tutti gli elementi dalla raccolta. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Verifica se la raccolta contiene l'elemento specificato. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copia gli elementi di contorno in un System.Array, iniziando da un indice specifico di System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Elimina tutti gli elementi di contorno dal contorno del documento. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Elimina l'elemento di contorno con il titolo specificato dal contorno del documento. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Rimuove l'elemento per indice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Lancia sempre NotImplementedException |

### Vedi anche

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


