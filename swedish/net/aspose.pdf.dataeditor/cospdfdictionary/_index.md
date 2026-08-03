---
title: "Klass CosPdfDictionary"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.DataEditor.CosPdfDictionary-klass. En klass för att komma åt ett objekts ordbok"
type: docs
weight: 3540
url: /sv/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

En klass för att komma åt ett objekts ordbok.

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
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Hämtar eller anger elementet med den angivna nyckeln. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Samling av redigerbara nycklar. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Hämtar en ICollection som innehåller värdena i `CosPdfDictionary`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Skapar en tom ordbok som kommer att bifogas dokumentet. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Skapar en tom ordbok som kommer att bifogas sidan. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Ställ in [`ICosPdfPrimitive`](../icospdfprimitive/) till ordbok. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Ställ in [`ICosPdfPrimitive`](../icospdfprimitive/) till ordbok. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Tar bort alla objekt från `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Bestämmer om `CosPdfDictionary` innehåller ett specifikt värde. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Bestämmer om `CosPdfDictionary` innehåller ett element med den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Tar bort den första förekomsten av ett specifikt objekt från `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Tar bort elementet med den angivna nyckeln från `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Försöker kasta denna instans till [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Försöker kasta detta objekt till `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Försöker kasta detta objekt till [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Försöker kasta detta objekt till [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Försöker kasta detta objekt till [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer. |

### Se även

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


