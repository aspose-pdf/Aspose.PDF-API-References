---
title: "Klass MarkupParagraph"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.MarkupParagraph-klass. Representerar ett stycke"
type: docs
weight: 10810
url: /sv/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

Representerar ett stycke.

```csharp
public sealed class MarkupParagraph
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Lista över sidnummer där stycket fortsätts. Den kommer att matcha med sidan där stycket startade om det fortsätter i nästa kolumn på samma sida. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Samling av icke tomma [`TextFragment`](../textfragment/)-objekt för stycket. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Rader i stycket. Varje rad representeras av en lista med textfragment. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Punkter i polygonen som beskriver stycket. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Punkter i den sekundära polygonen som beskriver styckets fortsättning. Den kommer inte att vara null om stycket fortsätts i nästa kolumn eller på nästa sida. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Hämtar eller anger styckets text. |

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


