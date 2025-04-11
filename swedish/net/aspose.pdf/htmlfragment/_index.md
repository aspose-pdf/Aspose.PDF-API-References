---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlFragment klass. Representerar html-fragment
type: docs
weight: 5520
url: /sv/net/aspose.pdf/htmlfragment/
---
## HtmlFragment klass

Representerar html-fragment.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Initierar en ny instans av HtmlFragment-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller ställer in en horisontell justering av stycket |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Hämtar eller ställer in HtmlLoadOptions som kommer att användas för att ladda (och rendera) HTML i denna instans av klassen. Vänligen använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den instansen (t.ex. när denna eller den instansen ska använda specifik BasePath för importerad HTML eller ska använda specifik loader för externa resurser) Om parametern är standard (null), kommer standardalternativ för HTML-laddning att användas. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Hämtar eller ställer in ordavbrott |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Hämtar eller ställer in om stycket har standardmarginal, annars är marginalen 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Hämtar rektangeln av HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Hämtar eller ställer in typsnitt |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen av grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Klonar html-fragment. |

### Se Även

* klass [FormattedFragment](../formattedfragment/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)