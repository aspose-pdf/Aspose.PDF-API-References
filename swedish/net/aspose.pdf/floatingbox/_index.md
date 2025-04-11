---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /sv/net/aspose.pdf/floatingbox/
---
## FloatingBox klass

```csharp
public class FloatingBox : BaseParagraph
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Initierar en ny instans av `FloatingBox` klassen. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Initierar en ny instans av `FloatingBox` klassen med angiven bredd och höjd. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Hämtar eller sätter ett [`Color`](../color/) objekt som indikerar bakgrundsfärgen för den flytande rutan. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Hämtar eller sätter bakgrundsbild för sidan (endast för generator, inte ifylld vid läsning av dokument). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Hämtar eller sätter ett [`BorderInfo`](../borderinfo/) objekt som indikerar gränsinformationen för den flytande rutan. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Hämtar eller sätter kolumninformation |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Hämtar eller sätter ett flyttal som indikerar höjden på den flytande rutan. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Hämtar eller sätter en horisontell justering av stycket |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller sätter fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller sätter om stycket är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller sätter ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om det aktuella stycket förblir på samma sida som nästa stycke. Standard är falskt. (för pdf-generering) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Hämtar eller sätter ett bool-värde som indikerar om stycket behöver upprepas på nästa sida. Standardvärdet är falskt. Attributet är endast giltigt när stycket självt och objektet som dess ReferenceParagraphID hänvisar till båda ingår i RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Hämtar eller sätter tabellens vänstra koordinat. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller sätter en yttre marginal för stycket (för pdf-generering) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Hämtar eller sätter ett [`MarginInfo`](../margininfo/) objekt som indikerar padding för den flytande rutan. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Hämtar eller sätter en [`Paragraphs`](./paragraphs/) samling som indikerar alla stycken i cellen. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Anger variant för att bestämma platsen för FloatingBox på sidan. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Hämtar eller sätter tabellens övre koordinat. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller sätter en vertikal justering av stycket |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Hämtar eller sätter ett flyttal som indikerar bredden på den flytande rutan. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller sätter ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Klonar ett nytt `FloatingBox` objekt. Stycken i den flytande rutan klonas inte. |

### Se Även

* klass [BaseParagraph](../baseparagraph/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)