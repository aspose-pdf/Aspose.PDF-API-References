---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection classe. La classe rappresenta la raccolta di tutti i destinazioni, un albero di nomi che mappa string di nomi a destinazioni. Vedere 12.3.2.3 Destinazioni denominate e vedere 7.7.4 Dizionario dei nomi nel documento PDF.
type: docs
weight: 3510
url: /it/net/aspose.pdf/destinationcollection/
---
## Classe DestinationCollection

La classe rappresenta la collezione di tutte le destinazioni (un albero dei nomi che mappa le stringhe dei nomi alle destinazioni (vedere 12.3.2.3, "Destinazioni nominate") e (vedere 7.7.4, "Dizionario dei nomi")) nel documento pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Ottiene il numero di elementi contenuti nella collezione. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Ottiene un valore che indica se la collezione è di sola lettura. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Ottiene l'oggetto destinazione per indice. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Aggiunge l'elemento specificato. La collezione è di sola lettura. Genera sempre un'eccezione NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | La collezione è di sola lettura. Genera sempre un'eccezione NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Determina se questa istanza contiene l'oggetto. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Restituisce l'enumeratore. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Restituisce la destinazione esplicita per nome. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Restituisce il numero di pagina della destinazione per nome. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Restituisce l'indice della destinazione nella collezione. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Rimuove l'elemento specificato. La collezione è di sola lettura. Genera sempre un'eccezione NotSupportedException. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)