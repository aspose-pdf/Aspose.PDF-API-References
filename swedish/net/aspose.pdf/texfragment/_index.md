---
title: "Klass TeXFragment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.TeXFragment-klass. Representerar TeX‑fragment."
type: docs
weight: 10540
url: /sv/net/aspose.pdf/texfragment/
---
## TeXFragment class

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
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller anger en horisontell justering av stycket. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Hämtar eller sätter TeXLoadOptions som kommer att användas för inläsning (och rendering) av LaTeX i detta klass‑instans. Använd den när det är nödvändigt att använda specifika inställningar för import av LaTeX för denna eller den där instansen (t.ex. när denna eller den där instansen ska använda en specifik BasePath för importerad LaTeX eller ska använda en specifik laddare för externa resurser). Om parametern är standard (null) kommer standardalternativen för LaTeX‑inläsning att användas. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Klonar fragmentet. |

### Se även

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


