---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXFragment klass. Representerar TeX-fragment
type: docs
weight: 10360
url: /sv/net/aspose.pdf/texfragment/
---
## TeXFragment klass

Representerar TeX-fragment.

```csharp
public class TeXFragment : FormattedFragment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Initierar en ny instans av HtmlFragment-klassen. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Initierar en ny instans av HtmlFragment-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av stycket |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om stycket är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Hämtar eller ställer in TeXLoadOptions som kommer att användas för att ladda (och rendera) LaTeX i denna instans av klassen. Vänligen använd det när det är nödvändigt att använda specifika inställningar för import av LaTeX för denna eller den instansen (t.ex. när denna eller den instansen ska använda specifik BasePath för importerad LaTeX eller ska använda specifik loader för externa resurser) Om parametern är standard (null), kommer standard LaTeX-laddningsalternativ att användas. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Klonar fragmentet. |

### Se Även

* klass [FormattedFragment](../formattedfragment/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)