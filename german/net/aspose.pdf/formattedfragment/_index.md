---
title: Class FormattedFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FormattedFragment-Klasse. Stellt ein abstraktes formatiertes Fragment dar
type: docs
weight: 4940
url: /de/net/aspose.pdf/formattedfragment/
---
## FormattedFragment-Klasse

Stellt ein abstraktes formatiertes Fragment dar.

```csharp
public abstract class FormattedFragment : BaseParagraph
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Ruft die horizontale Ausrichtung des Absatzes ab oder legt sie fest |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Ruft den Fragment-Hyperlink (für PDF-Generator) ab oder legt ihn fest. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte steht. Standard ist false. (für PDF-Generierung) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. (für PDF-Generierung) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite generiert wird. Standard ist false. (für PDF-Generierung) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz auf derselben Seite wie der nächste Absatz bleibt. Standard ist false. (für PDF-Generierung) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Ruft einen äußeren Rand für den Absatz ab oder legt ihn fest (für PDF-Generierung) |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Ruft die vertikale Ausrichtung des Absatzes ab oder legt sie fest |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Ruft einen int-Wert ab oder legt ihn fest, der die Z-Reihenfolge des Graphen angibt. Ein Graph mit größerem ZIndex wird über dem Graphen mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Graph mit negativem ZIndex wird hinter dem Text auf der Seite platziert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klont diese Instanz. Virtuelle Methode. Gibt immer null zurück. |

### Siehe auch

* Klasse [BaseParagraph](../baseparagraph/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)