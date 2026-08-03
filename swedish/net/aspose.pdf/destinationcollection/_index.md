---
title: "Klassen DestinationCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.DestinationCollection-klass. Klassen representerar samlingen av alla destinationer, ett namntre som mappar namnsträngar till destinationer, se 12.3.2.3 Namngivna destinationer och se 7.7.4 Namnordbok i PDF-dokumentet."
type: docs
weight: 3630
url: /sv/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

Klassen representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, "Named Destinations") och (se 7.7.4, "Name Dictionary")) i pdf-dokumentet.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Hämtar antalet element som finns i samlingen. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Hämtar destinationsobjektet efter index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Lägger till det angivna objektet. Samlingen är skrivskyddad. Kastar alltid ett NotSupportedException-undantag. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Samlingen är skrivskyddad. Kastar alltid ett NotSupportedException-undantag. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Bestämmer om den här instansen innehåller objektet. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Returnerar enumeratorn. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Returnerar den explicita destinationen efter namn. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Returnerar sidnumret för destinationen efter namn. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Returnerar indexet för destinationen i samlingen. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Tar bort det angivna objektet. Samlingen är skrivskyddad. Kastar alltid ett NotSupportedException-undantag. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


