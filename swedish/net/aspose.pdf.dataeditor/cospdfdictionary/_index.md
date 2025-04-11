---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary klass. En klass för att få tillgång till ett objekts ordbok
type: docs
weight: 3420
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary klass

En klass för att få tillgång till ett objekts ordbok.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Skapar en ordbok från resurser. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Hämtar antalet element som finns i `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Hämtar ett värde som indikerar om `CosPdfDictionary` är skrivskyddad. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Hämtar eller ställer in elementet med den angivna nyckeln. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Samling av redigerbara nycklar. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Hämtar en ICollection som innehåller värdena i `CosPdfDictionary`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Skapar en tom ordbok som kommer att kopplas till dokumentet. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Skapar en tom ordbok som kommer att kopplas till sidan. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Sätter [`ICosPdfPrimitive`](../icospdfprimitive/) till ordboken. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Sätter [`ICosPdfPrimitive`](../icospdfprimitive/) till ordboken. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Tar bort alla objekt från `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Bestämmer om `CosPdfDictionary` innehåller ett specifikt värde. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Bestämmer om `CosPdfDictionary` innehåller ett element med den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Tar bort den första förekomsten av ett specifikt objekt från `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Tar bort elementet med den angivna nyckeln från `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Försöker konvertera denna instans till [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Försöker konvertera denna instans till `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Försöker konvertera denna instans till [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Försöker konvertera denna instans till [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Försöker konvertera denna instans till [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | För åtkomst till enkla datatyper som sträng, namn, bool, nummer. Returnerar null för andra typer. |

### Se Även

* klass [CosPdfPrimitive](../cospdfprimitive/)
* gränssnitt [ICosPdfPrimitive](../icospdfprimitive/)
* namnrymd [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)