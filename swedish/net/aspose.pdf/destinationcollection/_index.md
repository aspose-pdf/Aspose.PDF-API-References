---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection klass. Klassen representerar samlingen av alla destinationer en namntree som kartlägger namnsträngar till destinationer se 12.3.2.3 Namngivna destinationer och se 7.7.4 Namndokument i pdf-dokumentet
type: docs
weight: 3510
url: /sv/net/aspose.pdf/destinationcollection/
---
## DestinationCollection klass

Klassen representerar samlingen av alla destinationer (en namntree som kartlägger namnsträngar till destinationer (se 12.3.2.3, "Namngivna destinationer") och (se 7.7.4, "Namndokument")) i pdf-dokumentet.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Hämtar antalet element som ingår i samlingen. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Hämtar destinationobjektet efter index. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Lägger till det angivna objektet. Samlingen är skrivskyddad. Kastar alltid NotSupportedException undantag. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | Samlingen är skrivskyddad. Kastar alltid NotSupportedException undantag. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Bestämmer om denna instans innehåller objektet. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Returnerar enumeratorn. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Returnerar den explicita destinationen efter namn. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Returnerar sidnumret för destinationen efter namn. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Returnerar indexet för destinationen i samlingen. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Tar bort det angivna objektet. Samlingen är skrivskyddad. Kastar alltid NotSupportedException undantag. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)