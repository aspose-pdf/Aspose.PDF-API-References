---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor klass. En klass för att få åtkomst till ett dokuments trädordbok (dokumentordbok, sidordbok, resursordbok).
type: docs
weight: 3470
url: /sv/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor klass

En klass för att få åtkomst till ett dokuments trädordbok (dokumentordbok, sidordbok, resursordbok).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Hämtar antalet element som finns i `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Hämtar ett värde som indikerar om `DictionaryEditor` är skrivskyddad. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Hämtar eller sätter elementet med den angivna nyckeln. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Samling av redigerbara nycklar. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Hämtar en ICollection som innehåller värdena i `DictionaryEditor`. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Sätter [`ICosPdfPrimitive`](../icospdfprimitive/) till ordboken. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Sätter [`ICosPdfPrimitive`](../icospdfprimitive/) till ordboken. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Tar bort alla objekt från `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Bestämmer om `DictionaryEditor` innehåller ett specifikt värde. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Bestämmer om `DictionaryEditor` innehåller ett element med den angivna nyckeln. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Tar bort den första förekomsten av ett specifikt objekt från `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Tar bort elementet med den angivna nyckeln från `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | För åtkomst till enkla datatyper som sträng, namn, bool, nummer. Returnerar null för andra typer. |

### Se Även

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)