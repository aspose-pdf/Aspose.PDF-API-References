---
title: "Classe DestinationCollection"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.DestinationCollection class. La classe rappresenta la raccolta di tutte le destinazioni, un albero dei nomi che mappa le stringhe dei nomi alle destinazioni; vedi 12.3.2.3 Named Destinations e vedi 7.7.4 Name Dictionary nel documento pdf."
type: docs
weight: 3630
url: /it/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

La classe rappresenta la raccolta di tutte le destinazioni (un albero dei nomi che mappa le stringhe dei nomi alle destinazioni (vedi 12.3.2.3, "Named Destinations") e (vedi 7.7.4, "Name Dictionary")) nel documento pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Ottiene il numero di elementi contenuti nella raccolta. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Restituisce un valore che indica se la collezione è di sola lettura. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Ottiene l'oggetto destinazione per indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Aggiunge l'elemento specificato. La raccolta è di sola lettura. Lancia sempre l'eccezione NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | La raccolta è di sola lettura. Lancia sempre l'eccezione NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Determina se questa istanza contiene l'oggetto. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Restituisce l'enumeratore. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Restituisce la destinazione esplicita per nome. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Restituisce il numero di pagina della destinazione per nome. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Restituisce l'indice della destinazione nella raccolta. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Rimuove l'elemento specificato. La raccolta è di sola lettura. Lancia sempre l'eccezione NotSupportedException. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


