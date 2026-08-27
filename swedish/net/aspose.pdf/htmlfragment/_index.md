---
title: "Klass HtmlFragment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlFragment-klass. Representerar html-fragment"
type: docs
weight: 5650
url: /sv/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av stycket. |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Hämtar eller anger HtmlLoadOptions som kommer att användas för inläsning (och rendering) av HTML i denna klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den där instansen (t.ex. när denna eller den där instansen ska använda en specifik BasePath för importerad HTML eller ska använda en specifik laddare för externa resurser). Om parametern är standard (null) används standardalternativ för HTML-inläsning. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Hämtar eller anger ordbrytning |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Hämtar eller anger om stycket har standardmarginal, annars är marginalen 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Hämtar rektangeln för HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Hämtar eller anger teckensnitt |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Klonar html-fragment. |

### Se även

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


