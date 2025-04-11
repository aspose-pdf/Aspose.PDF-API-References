---
title: Class BaseParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseParagraph-Klasse. Stellt ein abstraktes Basisobjekt dar, das zu pagedoc.Paragraphs.Add hinzugefügt werden kann.
type: docs
weight: 2840
url: /de/net/aspose.pdf/baseparagraph/
---
## Klasse BaseParagraph

Stellt ein abstraktes Basisobjekt dar, das zur Seite (doc.Paragraphs.Add()) hinzugefügt werden kann.

```csharp
public abstract class BaseParagraph : ICloneable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Absatzes ab oder legt sie fest |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für den PDF-Generator) ab oder legt ihn fest. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte sein wird. Standard ist false. (für die PDF-Erstellung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für die PDF-Erstellung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für die PDF-Erstellung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für die PDF-Erstellung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für die PDF-Erstellung) |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Absatzes ab oder legt sie fest |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)