---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.MarkupParagraph klass. Representerar ett stycke
type: docs
weight: 10630
url: /sv/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph klass

Representerar ett stycke.

```csharp
public sealed class MarkupParagraph
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Lista över sidnummer där stycket fortsätter. Det kommer att matcha med sidan där stycket började om det fortsätter i nästa kolumn på samma sida. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Samling av icke-tomma [`TextFragment`](../textfragment/) objekt av stycket. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Rader av stycket. Varje rad representeras av en lista av textfragment. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Punkter av polygon som beskriver stycket. Startpunkt är nedre vänstra hörnet av stycket. Och nästa punkter är i motsols sekvens. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Punkter av sekundär polygon som beskriver styckets fortsättning. Den kommer inte att vara null om stycket fortsätter i nästa kolumn eller sida. Startpunkt är nedre vänstra hörnet av stycket. Och nästa punkter är i motsols sekvens. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Hämtar eller ställer in styckets text. |

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* samling [Aspose.PDF](../../)