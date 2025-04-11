---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.MarkupParagraph-Klasse. Stellt einen Absatz dar
type: docs
weight: 10630
url: /de/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph-Klasse

Stellt einen Absatz dar.

```csharp
public sealed class MarkupParagraph
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | Liste der Seitenzahlen, auf denen der Absatz fortgesetzt wird. Es wird mit der Seite übereinstimmen, auf der der Absatz begonnen hat, wenn er in der nächsten Spalte auf derselben Seite fortgesetzt wird. |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | Sammlung von nicht leeren [`TextFragment`](../textfragment/) Objekten des Absatzes. |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | Linien des Absatzes. Jede Linie wird durch eine Liste von Textfragmenten dargestellt. |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | Punkte des Polygons, das den Absatz beschreibt. Der Startpunkt ist die linke untere Ecke des Absatzes. Die nächsten Punkte sind in gegen den Uhrzeigersinn angeordnet. |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | Punkte des sekundären Polygons, das die Fortsetzung des Absatzes beschreibt. Es wird nicht null sein, wenn der Absatz in der nächsten Spalte oder Seite fortgesetzt wird. Der Startpunkt ist die linke untere Ecke des Absatzes. Die nächsten Punkte sind in gegen den Uhrzeigersinn angeordnet. |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | Ruft den Absatztext ab oder legt ihn fest. |

### Siehe auch

* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)